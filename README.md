# 📘 GitHub Collaboration Assignment

## 📌 Project Overview

This repository was created as part of our **GitHub Collaboration Assignment**. The goal is to practice Git best practices, branching strategies, branch protection rules, pull requests, code reviews, and collaborative workflows.  

Each team member contributed by:

- Creating a personal feature branch.
- Adding a markdown file with their **Name**, **Favorite DevOps Tool**, and **One Git Command Learned**.  
- Opening a Pull Request (PR) into the `develop` branch.  
- Reviewing and approving another team member’s PR.  
- Finally, merging `develop` into `main` (done by the Team Lead with approval).  

## 📂 Repository Structure

```bash
├── .github/
│ └── workflows/ # CI workflow checks (assignment validation)
├── *.md # Each member’s markdown file
├── README.md # This file
└── Github-assignment.pdf # Original assignment instructions
```

## 🔄 Workflow Summary

1. **Team Lead** created the repository, `main` and `develop` branches, and set branch protection rules.  
2. **Each member** cloned the repo, created a feature branch, and added their markdown file.  
3. **Pull Requests (PRs)** were opened into `develop`.  
4. **Reviews**: Each member reviewed at least one PR.  
5. **Merging**: Team lead created a final PR to merge `develop` → `main`.  

## 👥 Contributors  

| Name                 | GitHub Profile                                 | PR Link |
|----------------------|------------------------------------------------|---------|
| **Omotomiwa afonja** | [@omotomiwa26](https://github.com/omotomiwa26) | [PR #1](https://github.com/...) |
| **foluso ajayi**     | [@ajayifoluso](https://github.com/ajayifoluso) | [PR #2](https://github.com/...) |
| **bola omoniyi**     | [@bolaomoniyi](https://github.com/AishaIbrahim) | [PR #3](https://github.com/...) |
| **john eniu**        | [@johneniu](https://github.com/DavidJohnson) | [PR #4](https://github.com/...) |

## 📑 Assignment Document

The original assignment instructions can be found here:  
📄 [GitHub Assignment PDF](https://drive.google.com/file/d/1FEJT9lU0x-jbg5mxpAUNZXvHZOu7HeqE/view?usp=drive_link)  

## ✅ Requirements Validation

To ensure compliance, a GitHub Actions workflow (`check-assignment.yml`) automatically validates:

- Each member has a `.md` file (not `README.md`).
- The file contains:  
  - **Name**  
  - **Favorite DevOps Tool**  
  - **Git Command Learned**  

PRs cannot be merged unless all checks pass.  

## 🚀 How to Contribute

1. Clone the repository

   ```bash
   git clone `https://github.com/omotomiwa26/Team14-github-collab.git`
   cd `https://github.com/omotomiwa26/Team14-github-collab.git`
   ```

2. Create a feature branch

    `git checkout -b feature-yourname`

3. Add your markdown file

```bash
# Your Name

- **Name:** Your Full Name
- **Favorite DevOps Tool:** ToolName
- **Git Command Learned:** git checkout -b branchname
```

4. Commit and push

```bash
    git add yourname.md
    git commit -m "Added my assignment file"
    git push origin feature-yourname
```

5. Open a Pull Request to develop branch.

🏆 Challenges & Lessons Learned

- Setting up branch protection rules for collaborative work.
- Using Pull Requests for peer reviews and approvals.
- Understanding status checks and GitHub Actions.
- Resolving merge conflicts in collaborative environments.

📌 Final Note

This repository demonstrates team collaboration on GitHub using real-world workflows that mirror software development practices.
