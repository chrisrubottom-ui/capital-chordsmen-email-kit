# Capital Chordsmen Email HTML Builder

This repository contains a simple single-page HTML/CSS/JavaScript app (`index.html`) that generates copy/paste email HTML.

## Important source-material requirement

This builder is intended to mirror approved Capital Chordsmen source materials. In this repository snapshot, those source files are **not present**. The app therefore runs in a safe baseline mode and does **not** claim to match approved final branding/layout.

To produce a template-accurate builder, add these files to this repo:

1. Email Brand Kit file (the exact file shared by your team).
2. Approved Communique example HTML template.
3. Approved Weekly member newsletter (“What's Happening!”) example HTML template.

If filenames differ, update this README and the tool comments to point to the exact paths.

## How to run locally

1. Open `index.html` directly in a browser, or serve the folder with a static server.
2. Fill out the form fields.
3. Copy generated HTML using the **Copy HTML** button.

## How to test generated email HTML

1. **Visual review in browser preview**
   - Confirm both email types render.
   - Confirm Communique includes compliance/unsubscribe area.
   - Confirm Newsletter excludes unsubscribe by default.

2. **Paste into your email platform editor**
   - Confirm table layout, spacing, and links.
   - Confirm platform-specific unsubscribe/footer merge tags are applied as required.

3. **Inbox/device test**
   - Send test to Gmail/Outlook/Apple Mail.
   - Verify headline, body text, CTA button, footer, and preheader appearance.

## Current known limitations

- No automatic import/parsing of brand kit files yet.
- No strict parity with approved templates until source template files are added to the repository.
