# MD File Inline Comments

GitHub doesn't support inline comments on rendered Markdown files — this idea explores solutions to bridge that gap.

## Details

- GitHub's PR review inline comments don't carry over to rendered `.md` views, making it hard to annotate documentation or specs collaboratively.
- **Potential solutions to explore:**
  - **HackMD** — collaborative Markdown editor with native inline commenting; evaluate as a drop-in layer over GitHub-hosted docs.
  - **Notion import** — import MD files into Notion to leverage its inline comment and discussion features.
  - **Lightweight custom layer** — build a thin web app that renders GitHub MD files and overlays a commenting system (using something like GitHub Gists or a small backend to persist comments).
- Key challenge: keeping comments in sync when the underlying `.md` file changes (line-number drift, content edits).
- Could also explore browser extensions that inject a commenting UI directly onto `github.com` rendered MD pages.
