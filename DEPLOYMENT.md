# Deploying Saffron Cafe to Vercel

You have two easy ways to deploy this project.

## Option 1: Vercel CLI (Fastest for testing)
This allows you to deploy directly from your terminal.

1.  Open your terminal in this directory.
2.  Run the following command:
    ```bash
    npx vercel
    ```
3.  Follow the interactive prompts:
    -   **Set up and deploy?** [Y]
    -   **Which scope?** [Select your account]
    -   **Link to existing project?** [N]
    -   **Project Name?** [Press Enter for default]
    -   **In which directory?** [Press Enter for ./]
    -   **Want to modify these settings?** [N]

Vercel will build and deploy your site. You'll get a production URL (e.g., `https://saffron-cafe.vercel.app`).

## Option 2: Git Integration (Best for production)
This sets up automatic deployments whenever you push to GitHub/GitLab.

1.  Push this project to a git repository (if you haven't already).
2.  Go to [Vercel.com](https://vercel.com/new).
3.  Click **Add New...** -> **Project**.
4.  Import your Git repository.
5.  Vercel will detect it's a static site. Click **Deploy**.

## Note on Assets
Your video files are in the `assets/` folder.
-   `burger.mp4` (~12MB)
-   `shawarma.mp4` (~10MB)
-   `juice.mp4` (~25MB)
Total size is < 50MB, which is well within Vercel's limits for static deployments.
