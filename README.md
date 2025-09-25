# Digital Card App

This bundle includes:
- `index.html` with your info, Add to Contacts button, and links.
- `mycard.vcf` with your vCard details.
- `add.html` for manual entry (points to a Microsoft Form).
- `assets/` with style.css and a placeholder QR.

## Usage

1. Replace placeholders in `mycard.vcf` and `index.html` with your real details.
2. Replace the Form link placeholders with your Microsoft Form link.
3. Host this folder on GitHub Pages (Settings > Pages > select main branch, root folder).
4. The live URL is your digital card. Share it via QR.

## SharePoint integration

- Build a Power Automate flow: Forms submission → Get details → Create item in SharePoint list (Contacts).
- Add deduplication logic with `NormalizedEmail`.
- Test with duplicate emails to confirm behavior.

