# FinanzWissen – Redirect Repository

This is **only** a redirect repository for GitHub Pages.  
It automatically forwards visitors to the main **FinanzWissen** project website.

---

## ℹ Project Info

- **Main repository**: [Tomato6966/FinanzWissen](https://github.com/Tomato6966/FinanzWissen)  
- **Main website**: [https://tomato6966.github.io/finanzwissen/](https://tomato6966.github.io/finanzwissen/)

---

## 📌 Purpose of this Repo
- GitHub Pages allows one **unique sub-URL per repository** for each user account.  
- This repo contains a simple `index.html` file that instantly redirects to the main website.  
- Benefit: Visitors who access an old website or a website alias will be redirected directly to the correct site — without the need for a backend — e.g., `https://tomato6966.github.io/finanzwissen/`.

---

## 🛠 Structure
- `public/index.html` → contains an HTML meta refresh redirect.
- `.github/workflows/deploy-redirect.yml` → GitHub Actions workflow that automatically deploys to GitHub Pages.

---

## 🚀 Deployment
Every push to the `main` branch triggers the **Deploy to GitHub Pages** workflow.  
The site will be available within a few seconds at the redirect URL mentioned above.

---

## 📝 License
This redirect setup is freely available under the MIT license. No warranty provided.
