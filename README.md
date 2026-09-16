# yibinsun.github.io

Yibin (Spencer) Sun’s static academic website for GitHub Pages.

## Public pages

- `index.html`: root homepage, biography, research, selected publications, talks, and contact.
- `publications/`, `cv/`, `talks/`, and `teaching/`: academic pages with shared masthead and author sidebar.
- `assets/css/main.css`: imported AcademicPages / Minimal Mistakes template styles.
- `assets/css/yibin.css`: responsive navigation and local layout refinements.
- `assets/yibin-headshot.jpeg`: Yibin’s existing portrait.
- `sitemap.xml`, `robots.txt`, and `feed.xml`: Yibin’s site metadata.

Content is carried over from the prior Yibin homepage and CV. Coauthor and supervisor credits are preserved. Copied sample pages redirect to the relevant public pages.

## GitHub Pages

Publish from the repository root on the configured Pages branch. No front matter, JavaScript runtime, or package installation is required for the public HTML pages. GitHub Pages’ standard Jekyll processing uses `_config.yml` to exclude the original `code/heitorgomes.com/` reference snapshot and development files from publication. Do not add `.nojekyll` or deploy the whole repository with a raw upload, since that would bypass these exclusions.

Canonical and social metadata use `https://yibinsun.github.io/`. Navigation and assets use root-relative URLs.

## Preview locally

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000/>. This simple preview server serves the full working directory, including the excluded reference folder; it does not simulate Jekyll exclusions.
