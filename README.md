
# 🚀 React + Vite Portfolio with GitHub Pages Deployment

This project is a personal portfolio built using **React** and **Vite**, with automated deployment to **GitHub Pages** using **GitHub Actions**. It highlights proficiency in modern frontend development, continuous integration, and workflow automation.

<br/>

## 🌐 Live Demo

🔗 [View Portfolio](https://klu2200031399.github.io/Githubpages_deployment-portifolio/)

<br/>

## 📁 Project Structure

- ⚛️ **React + Vite** for fast and modular development.
- 💅 Styled with **CSS**.
- 🛠 **GitHub Actions** for CI/CD.
- 🚀 Hosted on **GitHub Pages**.

<br/>

## ⚙️ Configuration Details

### `vite.config.ts`

To ensure proper routing on GitHub Pages, the base path was set:

```ts
export default defineConfig({
  base: '/Githubpages_deployment-portifolio/',
  // other configs...
});
```

### `package.json`

Added the `homepage` field and a deploy script:

```json
"homepage": "https://klu2200031399.github.io/Githubpages_deployment-portifolio/",
"scripts": {
  "deploy": "gh-pages -d dist"
}
```

<br/>

## 🛠 Deployment Workflow

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Build the project**:
   ```bash
   npm run build
   ```

3. **Deploy to GitHub Pages**:
   ```bash
   npm run deploy
   ```

This uses the [`gh-pages`](https://www.npmjs.com/package/gh-pages) package to push the `dist` folder to the `gh-pages` branch.

<br/>

## 🤖 GitHub Actions

A GitHub Actions workflow is set up to deploy automatically on every push to the `main` branch. The workflow performs the following:

- Installs dependencies
- Builds the project
- Deploys to GitHub Pages

<br/>

## 📦 Technologies Used

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [GitHub Pages](https://pages.github.com/)
- [GitHub Actions](https://docs.github.com/en/actions)
- [gh-pages](https://www.npmjs.com/package/gh-pages)

<br/>

## 💡 What I Learned

- Setting up and configuring **CI/CD pipelines**
- Automating deployments with **GitHub Actions**
- Using **Git** for source control
- Understanding and customizing **Vite configs** for production environments


## 📬 Feedback

Feel free to create an issue or pull request if you'd like to suggest improvements or report bugs.

