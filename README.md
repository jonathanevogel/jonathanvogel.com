# Jonathan Vogel website

This repository is the source for <https://jonathanvogel.com>.

## Updating a paper or slide deck

1. Replace the existing PDF while retaining its exact filename, for example `BBLV.pdf`.
2. Update the description or revision date in `index.html` if needed.
3. Commit and push the changes to the `main` branch. GitHub Pages will publish the revision at the same URL, for example <https://jonathanvogel.com/BBLV.pdf>.

Do not rename or remove a published PDF merely because a newer version is available. The unchanged filename is what keeps links from seminar pages, CVs, and other websites valid. If an archival version is useful, add it under a new, dated filename while retaining the canonical file.

## Publishing

GitHub Pages should be configured to deploy from the `main` branch at the repository root. The `CNAME` file assigns the published site to `jonathanvogel.com`; GitHub's Pages settings must also have this custom domain configured and verified before GoDaddy DNS records are changed.
