# Overview
This is a GitHub tutorial.

## What is Git, and GitHub?
**Git:**  
Git is a distributed version control system that lets you track changes in your code, revert to previous versions, and collaborate with others efficiently. It works locally on your computer and does not require the internet to store your history.

**GitHub:**  
GitHub is a cloud-based hosting platform for Git repositories. It allows you to store your code online, share it with others, collaborate through pull requests, and manage projects.

---

## Workflow

<img width="800" height="568" alt="image" src="https://github.com/user-attachments/assets/0ad27ab2-a8b1-4db0-a859-3b85decff2e7" />

<img width="1160" height="981" alt="image" src="https://github.com/user-attachments/assets/45ce298d-de79-4593-a45c-2b62811aa330" />

### Common Steps
1. **Clone a repository** – Get a local copy of a remote project:  
   ```bash
   git clone <repository-url>
    ```

2. Make changes – Edit files in your working directory.

3. Stage changes – Select which changes will go into the next commit:
```bash
git add <file>

```
4. Commit changes – Save the staged changes in your local history:
```bash
git commit -m "Describe your change"

```
5. Push changes – Send commits from your local repository to GitHub:
```bash

git push origin main

```
6. Pull updates – Bring the latest changes from GitHub to your local repo:

```bash
git pull origin main

```