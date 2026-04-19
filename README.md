# francofierro.github.io

Personal site. Plain HTML + CSS, no build step.

## Stack

- HTML + CSS (no framework, no JavaScript)
- Hosted on GitHub Pages
- Auto-deployed on push to `main` via GitHub Actions

## Local preview

```sh
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

```
/
  index.html          # homepage
  posts/
    index.html        # posts stub
  assets/
    css/
      styles.css      # all styles
```
