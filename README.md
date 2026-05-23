# Raúl Vieytes

Personal site and writing portfolio built with **Jekyll** (GitHub Pages) and **Tailwind CSS**.

## Pages
| Path            | Source          | Purpose                                                  |
| --------------- | --------------- | -------------------------------------------------------- |
| `/`             | `index.html`    | Home grid that lists all posts from `_posts`.            |
| `/acerca-de-mi` | `about.md`      | About page with bio and contact info from `_config.yml`. |
| `/libros`       | `books.html`    | Books grid powered by `_data/books.yaml`.                |
| `/linktree`     | `linktree.html` | Link hub layout.                                         |
| `/404.html`     | `404.html`      | Not found page.                                          |
| `/*` posts      | `_posts/*.md`   | Individual stories (Jekyll permalinks).                  |
| `/feed.xml`     | plugin          | RSS feed from `jekyll-feed`.                             |
| `/sitemap.xml`  | plugin          | Sitemap from `jekyll-sitemap`.                           |

## Content & structure
- **Posts:** `_posts/*.md` with front matter like `title`, `layout: post`, `author`, and `image` (used on the home grid).
- **Data:** `_data/books.yaml`, `_data/navigation.yaml`, `_data/months.yaml`.
- **Layouts/partials:** `_layouts/` and `_includes/`.
- **Styles/assets:** `_tailwind.css` (Tailwind input) and `assets/`.

## Local development
```bash
bundle install
bundle exec jekyll serve --livereload
```
If you change `_config.yml`, restart the server (Jekyll doesn't reload it automatically).

## Documentation
- Jekyll docs: https://jekyllrb.com/docs/
- GitHub Pages: https://docs.github.com/en/pages
- GitHub Pages dependency versions: https://pages.github.com/versions/
- jekyll-tailwindcss: https://rubygems.org/gems/jekyll-tailwindcss

## Ideas to explore
- Categories and tags for posts.
- Drafts workflow (`_drafts/` + build flags).
- Search or filter UI for stories.
- Pagination or infinite scroll on the home grid.
- Related posts and reading time.
- Social sharing metadata (Open Graph/Twitter cards).
- Image optimization (responsive sizes, lazy loading).
- Accessibility audit (contrast, focus states, alt text).

## Resources
- https://www.argentina.gob.ar/educacion/materiales-didacticos/clasicos-universales/cuentos
- https://unsplash.com/
