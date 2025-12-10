---
description: How to host your static website on GitHub Pages
---

This workflow guides you through hosting your HTML/CSS website on GitHub Pages.

1.  **Initialize Git Repository**
    If you haven't already, initialize git in your project folder:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    ```

2.  **Create a GitHub Repository**
    *   Go to [GitHub.com](https://github.com) and log in.
    *   Click the "+" icon in the top right and select "New repository".
    *   Name your repository (e.g., `company-website`).
    *   Keep it "Public" (required for free GitHub Pages).
    *   Click "Create repository".

3.  **Push to GitHub**
    Follow the instructions shown on GitHub to push an existing repository. It will look something like this (replace `YOUR_USERNAME` and `REPO_NAME`):
    ```bash
    git branch -M main
    git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
    git push -u origin main
    ```

4.  **Enable GitHub Pages**
    *   Go to your repository's **Settings** tab.
    *   Click on **Pages** in the left sidebar.
    *   Under **Build and deployment** > **Source**, select **Deploy from a branch**.
    *   Under **Branch**, select `main` and folder `/ (root)`.
    *   Click **Save**.

5.  **Access Your Site**
    *   Wait a minute or two.
    *   Refresh the Pages settings page. You will see your live URL (usually `https://YOUR_USERNAME.github.io/REPO_NAME/`).
