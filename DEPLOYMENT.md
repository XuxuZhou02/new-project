# Public deployment

The graduation date (June 2028) and LinkedIn URL have been updated from supplied information. Email, biography, languages, project timelines and tool claims still need review before this is a finished application portfolio.

## GitHub Pages

1. Push this checkout, including `.github/workflows/pages.yml`, to `codex/deploy-portfolio`, `claude/exciting-lamport-kmryxl`, or `main`.
2. In this GitHub repository, open Settings → Pages and select **GitHub Actions** as the source. GitHub plan restrictions may apply to private repositories.
3. Open Actions → Deploy portfolio to GitHub Pages and inspect the run. Use the URL in the successful deployment output; do not assume that an expected URL is already live.
4. Check the public page, June 2028, LinkedIn destination, navigation, interactive case studies and mobile layout.

The workflow uploads only `index.html`; source and documentation are not included in the website artifact. It does not provision a custom domain.
