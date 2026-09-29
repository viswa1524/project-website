# Project Website

[![Deploy Project Website to GitHub Pages](https://github.com/viswa1524/project-website/actions/workflows/deploy.yml/badge.svg)](https://github.com/viswa1524/project-website/actions/workflows/deploy.yml)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-2ea44f?style=flat&logo=github)](https://viswa1524.github.io/project-website/)

> Modern project showcase website with automated GitHub Actions continuous integration and continuous deployment (CI/CD) to GitHub Pages.

---

## 🚀 Live Site

- **Live URL**: [https://viswa1524.github.io/project-website/](https://viswa1524.github.io/project-website/)
- **Repository**: [https://github.com/viswa1524/project-website](https://github.com/viswa1524/project-website)
- **Deployment Status**: [View Actions Workflow Runs](https://github.com/viswa1524/project-website/actions)

---

## ⚡ Automated CI/CD Workflow with GitHub Actions

Every commit pushed to the `main` branch triggers the automated deployment pipeline defined in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml):

1. **Trigger**: Triggers on `push` to `main` or manually via `workflow_dispatch`.
2. **Checkout**: Checks out source code via `actions/checkout@v4`.
3. **Setup**: Configures GitHub Pages metadata via `actions/configure-pages@v4`.
4. **Artifact Packaging**: Archives site assets with `actions/upload-pages-artifact@v3`.
5. **Deployment**: Deploys securely to GitHub Pages CDN with `actions/deploy-pages@v4` using modern OIDC token authentication.

---

## 🛠️ Local Development

To run or preview the project website locally:

```bash
# Clone the repository
git clone https://github.com/viswa1524/project-website.git

# Navigate into the project
cd project-website

# Open in browser or serve locally
python3 -m http.server 8000
# or
npx serve .
```

---

## 👤 Author

- **GitHub**: [@viswa1524](https://github.com/viswa1524)
- **Repository**: [viswa1524/project-website](https://github.com/viswa1524/project-website)
