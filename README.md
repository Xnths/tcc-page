## Deployment to GitHub Pages

This project is configured to deploy to GitHub Pages using `gh-pages`.

### Prerequisites

- Node.js installed
- Git initialized and connected to a GitHub repository

### How to Deploy

1.  **Run the deploy script:**

    ```bash
    npm run deploy
    ```

    This script will:
    - Build the project using `npm run build`.
    - Push the contents of the `dist` folder to the `gh-pages` branch of your repository.

2.  **Configure GitHub Pages:**

    - Go to your repository on GitHub.
    - Navigate to **Settings** > **Pages**.
    - Under **Source**, select **Deploy from a branch**.
    - Select the `gh-pages` branch and the `/ (root)` folder.
    - Click **Save**.

Your application will be available at `https://Xnths.github.io/tcc-page/`.
