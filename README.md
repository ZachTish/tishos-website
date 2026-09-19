# TishOS website

Documentation and privacy policy for my personal experiment bringing my life's
data into Markdown. I am the developer and the app's only current user.
This is a project description for reviewers, not a product marketing site.

- Website: https://zachtish.github.io/tishos-website/
- Privacy policy: https://zachtish.github.io/tishos-website/privacy/
- Contact: https://github.com/ZachTish/tishos-website/issues

This public repository contains only static website files. It contains no private
app source, vault data, credentials, or app binaries.

## Publishing

GitHub Pages serves `docs/` from `main`. No package installation, JavaScript,
build step, custom domain, analytics, or external font dependency is needed.
The repository root is not the Pages publishing directory.

Local preview: `python3 -m http.server 4173 --bind 127.0.0.1 --directory docs`.

## Content and presentation

Use first-person, factual language. Preserve the personal, single-user context.
Explain why Markdown is useful, how the vault/plugins/native companion relate,
what currently exists, and why FinanceKit access is being requested. Describe the
entity/transaction idea as an organizing approach, not a universal implemented
schema. Do not add slogans, calls to sign up, feature cards, invented audiences,
or claims of broad commercial availability.

The privacy policy retains the actual boundaries between vault-file sync,
CloudKit display Relay, and the proposed financial-data relay. It covers local
storage, system surfaces, Health and Watch features, AI requests, retention,
disconnection, deletion, website hosting, and correspondence. Personal use does
not mean all data stays on one device or remove the need for accurate disclosures.

Both pages are text-only at the owner's request. The presentation is a plain,
single-column document with modest headings, light/dark colors, wrapping links,
keyboard focus, semantic markup, and a skip link. There is no persisted UI state.

## Accuracy and maintenance

The September 18, 2026 data-flow descriptions were checked against the native
app's specification, privacy manifests, Health client, Apple Intelligence bridge,
Watch workout/capture contracts, and Relay boundaries. Preserve the distinction
between internal-test behavior and the unimplemented FinanceKit connection.
Update the policy when data handling or the personal-use/distribution scope changes.

The site does not claim Apple approval, public App Store availability, completed
App Privacy attestations, guaranteed background execution, or blanket end-to-end
encryption. Publishing it changes no app entitlement, permission, or submission.

## Validation

Before publishing, check HTML structure, metadata, IDs and label references,
local links and fragments, asset paths, keyboard-focus and narrow-screen rules,
light/dark text contrast, and the absence of images, scripts, external assets,
private data, and placeholders. Check the diff and preserve unrelated work.
After GitHub Pages reports a successful build, verify both pages and the stylesheet
return HTTP 200 and match the committed files. No browser visual or assistive-
technology acceptance is claimed by those source and HTTP checks.

GitHub issues are public. Do not request or publish private health/financial
records, notes, screenshots, credentials, or runtime settings.
