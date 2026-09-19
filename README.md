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

## Page structure and scope

The home page explains the vault/plugin/native-app roles, the note-first
methodology, entity-versus-transaction examples, atomic notes and lines,
daily workflows, per-device connection setup, background limits, current internal
availability, and the unimplemented FinanceKit plan. The methodology is explicitly
not a universal schema claim or a requirement to use fixed property names.

The privacy page has a short summary, linked contents, data-category table,
integration-specific sections, retention by store, security boundaries, and support
and privacy-request routes. Native CloudKit display Relay, vault-file sync, and
the proposed finance relay are different transports. Health exports and internal
Watch journal/draft behavior are described separately from direct Health stores.
No Apple approval, legal compliance certification, guaranteed background execution,
or blanket end-to-end encryption is claimed.

Both pages are intentionally text-only at the user's request. No screenshots,
photos, icon assets, illustrations, or user data are included. Responsive rules
collapse the two-column methodology and contents into one column. Light/dark
palettes, keyboard focus, anchor destinations, semantic headings, table captions,
and a skip link support reading and navigation. There is no persisted UI state.

## Content maintenance

The September 18, 2026 policy was checked against the native app's specification,
privacy manifests, Health client, Apple Intelligence bridge, Watch workout/capture
contracts, and Relay boundaries.
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

The September 18 expansion passed local HTTP entrypoint checks, HTML nesting and
metadata checks, unique-ID/label checks, internal-link/fragment and asset-path
checks, text-only/no-script/no-external-asset checks, private-data pattern review,
and WCAG AA normal-text contrast calculations in both themes. No browser visual
or assistive-technology acceptance is claimed. Public deployment is verified
against the exact source bytes after GitHub Pages finishes building.
