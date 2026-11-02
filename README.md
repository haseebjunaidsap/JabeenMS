# Office Mastery Path

A self-paced course website for learning Microsoft Excel, Word, PowerPoint, Outlook and OneNote, from beginner to advanced, in about 45 days at 2 hours a day.

The whole site is one file, `index.html`. It needs no build step and no server code.

## Publish on GitHub Pages

1. Sign in at https://github.com and click **New repository**.
2. Name it, for example `office-mastery-path`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**, drag in `index.html` (and this `README.md`), then click **Commit changes**.
4. Go to **Settings > Pages**.
5. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/(root)**, and click **Save**.
6. After a minute or two, the site is live at:
   `https://<your-github-username>.github.io/office-mastery-path/`

## Updating the site

Edit `index.html` on GitHub (pencil icon) or upload a new version. GitHub Pages republishes automatically within a few minutes.

## Notes

- Lesson content lives in the `TRACKS` array inside the `<script>` section of `index.html`; projects, resources and glossary are in `PROJECTS`, `LIBRARY` and `GLOSSARY`.
- "Mark as done" progress is saved in the visitor's own browser (localStorage), so it is per device.
- Fonts load from Google Fonts; the page still works offline with system fonts.
