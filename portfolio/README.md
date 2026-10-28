# Portfolio site

A single static page. No build step, no dependencies.

Files:
- `index.html`: the whole site (styles and script are inside it)
- `Srishti_Shree_Nidhi_Resume.pdf`: the file behind the "Download resume" buttons
- `render.yaml`: optional Render config

## Deploy on Render

1. Create a new GitHub repository and upload these files to its root.
2. In Render, choose **New > Static Site** and connect that repository.
3. Leave **Build Command** empty and set **Publish Directory** to `.`
4. Click **Create Static Site**. Render gives you a `onrender.com` link when it finishes.

You can also use `render.yaml` instead: choose **New > Blueprint** and pick the repository.

## Before you publish

- The "Source on GitHub" links under each project all point to your GitHub profile. Replace each one in `index.html` with the link to that project's repository.
- To update your resume, replace `Srishti_Shree_Nidhi_Resume.pdf` and keep the same file name.
- Preview locally by opening `index.html` in a browser.
