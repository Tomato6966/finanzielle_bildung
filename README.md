# GitHub Pages Redirect Repository

This repository is designed to automatically redirect the GitHub Pages URL

https://tomato6966.github.io/finanzwissen/   -->    https://tomato6966.github.io/finanzielle_bildung/

---

## How it works

- The page under `/finanzwissen/` performs a redirect to `/finanzielle_bildung/` using an HTML meta refresh tag.
- The redirect page is styled with a dark mode theme for a modern and pleasant look.
- If the automatic redirect does not work, a clickable link is provided.

---

## Repository structure

- `public/index.html`  
  The HTML redirect file with the dark mode styling, located in the repository root.

- `.github/workflows/deploy-redirect.yml`  
  The GitHub Actions workflow that deploys the contents of the `public` folder to the `gh-pages` branch upon every push to `main`.

---

## Deployment

### Prerequisites

- GitHub Pages is enabled and configured to serve from the `gh-pages` branch.

### Workflow process

1. When you push to the `main` branch, the workflow runs automatically.
2. The `public` folder is deployed to the `gh-pages` branch.
3. GitHub Pages updates and serves the redirect page at  
   `https://tomato6966.github.io/finanzwissen/`.

---

## Customization

- You can edit the target URL in `index.html` by changing the `meta refresh` content attribute.
- Feel free to customize the styles within `index.html` (dark mode colors, font sizes, etc.).

---

## Example index.html (Dark Mode)

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="refresh" content="0; URL='https://tomato6966.github.io/finanzielle_bildung/'" />
    <title>Redirecting...</title>
</head>
<body>
    <p>
        If you are not redirected automatically,  
        <a href="https://tomato6966.github.io/finanzielle_bildung/">click here</a>.
    </p>
</body>
</html>
```

---

## Contact

If you have any questions or issues, feel free to open an issue or contact me directly.

---

**Good luck with your GitHub Pages redirect!**