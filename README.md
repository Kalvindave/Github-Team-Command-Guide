# GitHub Team Command Guide

## Project Information

- **Course:** Integrative Programming Technologies 2
- **Week:** Week 6 - GitHub Basics and Integration
- **Group:** Group 2 | Semi;colon
- **Section:** BSIT 3C AMG B
- **Repository:** [Paste repository URL]

## Project Purpose

This project demonstrates how our team uses Visual Studio Code, Git, and
GitHub for version control and collaboration. The website explains Git setup,
repository initialization, branching, commits, pushing, pull requests,
reviews, merging, and synchronization.

## Group Members and Contributions

| Member | GitHub Username | Assigned File | Feature Branch | Contribution |
|---|---|---|---|---|
| Gian Carlo Gomez | giangomez | index.html | feature-homepage | Homepage and group information |
| Krystel Anne Lina | krystelannelina-collab | setup.html | feature-setup-guide | Git installation and setup guide |
| Cristine Joy Montes | cristinmontes | workflow.html | feature-team-workflow | Team collaboration workflow |
| Kalvin Dave Ramos | kalvindave | css/style.css | feature-styles | Layout and visual design |

## Required Team Workflow

```bash
git switch main
git pull origin main
git switch -c feature-name
git status
git diff
git add .
git commit -m "Describe the completed change"
git push -u origin feature-name
```

After pushing, the member creates a pull request on GitHub. Another member
reviews the changes before merging. After the merge, every member runs:

```bash
git switch main
git pull origin main
```

## How to Open the Website

1. Clone or download the repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a web browser.
4. Use the navigation links to view the Git Setup and Team Workflow pages.

## Security Reminder

This repository must not contain passwords, personal access tokens,
verification codes, recovery codes, or other private information.
Final check: open index.html in a browser, test every navigation link, confirm that the stylesheet loads, and compare the README member/branch records with GitHub's commit and pull-request history.
