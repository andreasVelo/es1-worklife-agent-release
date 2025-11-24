## Setup: Create a GitHub repository

1. Open GitHub and click **New repository**.

2. Fill in the repository details:
	- **Repository name:** e.g., `MyApp`
	- **Description:** e.g., "Installer and releases for MyApp"
	- **Visibility:** choose **Private** initially (you can make it public later)
	- **Initialize with a README:** optional (recommended)

3. Click **Create repository** to finish.

If you plan to publish releases or host installers in this repository, consider adding a `RELEASES.md` or a `docs/` folder to track packaging and publishing steps.

## Step 2: Push Your Project (Optional)

If you already have your source code or files locally:

1. Navigate to your project directory:
   ```
   cd path\to\your\project
   ```

2. Initialize a Git repository and push to GitHub:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/MyApp.git
   git push -u origin main
   ```

*This step is optional if you only want to upload installers. GitHub Releases does not require source code, only the repository to attach releases to.*