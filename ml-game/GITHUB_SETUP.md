# GitHub Setup Guide

After creating your GitHub repository, follow these steps to push your code and set up GitHub Pages:

## Connecting Your Local Repository to GitHub

1. After creating your repository on GitHub, you'll see a page with setup instructions.
2. Copy the commands under "…or push an existing repository from the command line"
3. Run these commands in your terminal (they will look something like this):

```
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPOSITORY-NAME` with your actual GitHub username and repository name.

## Setting Up GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (tab at the top)
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes for your site to be published
7. You'll see a message saying "Your site is published at https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/"

## Verifying Your Site

1. Click on the URL provided in the GitHub Pages section
2. Ensure your ML Quiz Game loads correctly
3. Test the functionality to make sure everything works as expected

Congratulations! Your ML Quiz Game is now hosted on GitHub Pages and accessible to anyone with the URL.