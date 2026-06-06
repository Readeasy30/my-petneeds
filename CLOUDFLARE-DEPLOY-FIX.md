# Cloudflare Deploy Fix for PetNeeds.ai

Date: 2026-06-06

## Problem

The GitHub repo `Wholelychit/my-petneeds` has the corrected PetNeeds.ai upload page, but the live domain still serves an older deployment.

Live stale page text found on `https://www.petneeds.ai/upload-photo`:

- `Status: the public page is ready, but the live Google Form link still needs to be connected here after the form is created.`

Current GitHub source has the corrected text:

- `Status: upload form connected.`

## Latest GitHub commits related to the fix

- `7fa9055562f41387aa54475bfcb47402ab2179d5` — Confirm pet photo upload form is connected
- `30280f71554524695d614d965b4e219140dd4fdf` — Add clean URL upload photo page
- `be0ac8bcbbd7c162dd795b53506c4fc8c925967c` — Add upload photo route rewrites
- `2b1ab225db552ead336c3bd080121a6a64bad8f1` — Add deploy check page

## Files that should be live after a correct deploy

- `upload-photo.html`
- `upload-photo/index.html`
- `_redirects`
- `deploy-check-2026-06-06.html`

## Test URLs

After Cloudflare deploys the latest repo state, these should work:

```text
https://petneeds.ai/deploy-check-2026-06-06.html
https://petneeds.ai/upload-photo
https://petneeds.ai/upload-photo.html
```

The deploy check page should show:

```text
DEPLOY CHECK 2026-06-06 PETPHOTO-FORM-CONNECTED
```

The upload page should show:

```text
Status: upload form connected.
```

## Cloudflare settings to check

Open Cloudflare:

1. Go to Workers & Pages.
2. Open the PetNeeds.ai Pages project.
3. Go to Settings > Builds and deployments.
4. Confirm Git repository is `Wholelychit/my-petneeds`.
5. Confirm production branch is `main`.
6. Confirm automatic production branch deployments are enabled.
7. Confirm build command is blank or none for this plain HTML site.
8. Confirm output directory is blank, `/`, or root.
9. Go to Deployments and create/retry a production deployment from the latest `main` commit.

## If there is no Git repository setting

The Cloudflare Pages project may have been created as a Direct Upload project.

If it is Direct Upload, either:

1. Create a new Cloudflare Pages project using Git integration and connect `Wholelychit/my-petneeds`, or
2. Deploy manually with Wrangler using the repo root as the output directory.

## Do not change

Do not remove the Google Form link from `upload-photo.html` or `upload-photo/index.html`.

Google Form ID currently used:

```text
1xg-QoofTFZ7J5BF2TrHrMYCrIEG2b-zggWScUU5ipo8
```
