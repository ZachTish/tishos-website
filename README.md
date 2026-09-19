# TishOS website

Public app information and privacy policy for the native TishOS companion.
This repository contains only the static website, not the private app source,
vault data, credentials, or app binaries.

- Website: https://zachtish.github.io/tishos-website/
- Privacy policy: https://zachtish.github.io/tishos-website/privacy/
- Support: https://github.com/ZachTish/tishos-website/issues

## Publishing

GitHub Pages publishes `docs/` from `main`. There is no package installation,
JavaScript, build step, custom domain, analytics, or external font dependency.
The repository root is not the Pages publishing directory.

For local preview, run `python3 -m http.server 4173 --bind 127.0.0.1 --directory docs`.

## Content maintenance

The September 18, 2026 policy was checked against the native app's specification,
privacy manifests, Health client, Apple Intelligence bridge, and Relay boundaries.
It distinguishes optional cloud/file-provider transfers from local processing,
and current internal-test behavior from the unimplemented FinanceKit plan.
Review the policy whenever permissions, providers, data destinations, retention,
or feature availability change. Keep the effective date current.

This website does not assert FinanceKit approval, App Store availability, or
completion of Apple's App Privacy questionnaire. Publishing it changes no native
app, entitlement, user permission, or Apple submission.

## Validation

Check both HTML entrypoints, language/title/viewport metadata, heading hierarchy,
local links and styles, responsive rules, focus treatment, and the absence of
private data or third-party scripts before pushing. After publication, verify both
public URLs and the stylesheet return HTTP 200 and match this checkout.

Support issues are public. Do not request or upload private health/financial
records, notes, screenshots, credentials, or runtime settings.
