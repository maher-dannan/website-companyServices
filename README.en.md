# Your Own Website Project

Build a website about a topic you enjoy. Think about the content you would like to show.

## Getting Started

Clone the course repository and create your own branch. Replace `YOUR-PROJECT` with the repository name and `YOUR-BRANCH` with, for example, your first name:

```bash
git clone git@github.com:ctf-26d/YOUR-PROJECT.git webprojekt
cd webprojekt
git switch -c YOUR-BRANCH
```

The basic HTML structure in [index.html](index.html) is already linked to [style.css](style.css). Build a small version on top of it, check it in the browser, and expand it step by step.

Find layout tips, ideas, and links in [Help and Inspiration](help/hilfen.en.md). You may use AI and new techniques for help.

## Saving Your Progress

Work on your own branch. Commit your progress and push it to the course repository (`origin`):

```bash
git add .
git commit -m "Project updated"
git push origin YOUR-BRANCH
```

## Finishing Up

Before the final push, you can delete the help files in `help/` and briefly describe your project in `README.md`. Commit these changes and push your work to `origin` as shown above.

## Optional: Publish Your Project

Create a **public, empty repository** in your own GitHub account – without a README, license, or `.gitignore`. Add it once as a remote called `deploy` and push your branch to its `main` branch. **In the example and diagram, `solution` means your own branch – replace it with your branch name.**

```bash
git remote add deploy git@github.com:YOUR-USERNAME/YOUR-REPO.git
git push deploy YOURBRANCH:main
```

For later changes, repeat both push commands with your branch name after committing.

Publish your public repository with GitHub Pages from `main` and share the link in Slack. Unfinished and experimental projects can be published too.

![Git workflow: work on your own branch and push to origin and optionally deploy](assets/Git-Workflow_%20Lokal%20und%20zwei%20GitHub-Repos.png)
