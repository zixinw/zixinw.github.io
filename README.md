# zixinw.github.io

Personal academic homepage of **Zixin Wang** — Ph.D. student, University of Michigan School of Information.

Built with [Jekyll](https://jekyllrb.com/) on the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) template.

## Editing

Almost everything lives in two files:

| File | What it controls |
|---|---|
| `_config.yml` | Name, avatar, email, social links, Google Scholar ID, SEO |
| `_pages/about.md` | All page content: bio, News, Publications, Education, Experience, Service, Teaching |
| `_data/navigation.yml` | Top navigation bar |

Images go in `images/`; PDFs (CV, papers) go in `files/`.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000

## Google Scholar citation badge

The workflow in `.github/workflows/google_scholar_crawler.yaml` runs daily and pushes
citation counts to a `google-scholar-stats` branch.

To enable it:
1. Repo **Settings → Secrets and variables → Actions → New repository secret**
2. Name: `GOOGLE_SCHOLAR_ID`, value: `6qxfN_4AAAAJ`
3. **Settings → Actions → General → Workflow permissions** → "Read and write permissions"
