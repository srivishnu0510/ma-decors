Git-Based Version Control Workflow for M A Decorators

This repository contains a complete demonstration of an industry-standard Git workflow used for managing the website project of M A Decorators.
It includes branching strategies, Pull Requests, merge conflict handling, release management, and documentation—exactly like real software companies work.

📌 Project Overview

This project shows how to manage a website using Git and GitHub with:

Feature branches

Develop and main branches

Pull Request review process

Merge conflicts (simulated + resolved)

Release branches and tagging

The goal is to provide clear version control and real-world collaboration experience.


🚀 Objectives of This Project

Learn and implement real Git branching strategies

Understand how Pull Requests work

Experience code review process

Simulate and resolve merge conflicts

Manage release versions using tags

Submit a complete Git workflow demonstration for academic/industry training

🧠 Technologies Used

Git – Version control

GitHub – Remote repository hosting

HTML, CSS, JavaScript – Website files

Markdown / Word / PDF – Documentation

🛠️ Git Workflow Used in This Project

Below is a summary of the workflow implemented in this repository:

✔ Initialize Git locally
git init
git add .
git commit -m "initial commit"

✔ Create main & develop branches
git branch -M main
git checkout -b develop

✔ Connect project to GitHub
git remote add origin <repo-url>
git push -u origin main
git push -u origin develop

✔ Create feature branches
git checkout develop
git checkout -b feature/homepage


Work → Commit → Push

git add .
git commit -m "added homepage section"
git push -u origin feature/homepage

✔ Open Pull Request → Review → Merge

Done on GitHub.

✔ Simulate a merge conflict

Edit same line on main and feature/conflict-demo, then merge.

✔ Resolve merge conflict manually

After fixing file:

git add index.html
git commit -m "resolved merge conflict"

✔ Create a release branch
git checkout develop
git checkout -b release/v1.0

✔ Merge release → main
git checkout main
git merge release/v1.0

✔ Create tag v1.0
git tag -a v1.0 -m "Website Release v1.0"
git push origin v1.0



⭐ Conclusion

This project successfully demonstrates a complete Git-based version control workflow following professional industry standards.
It includes:

Branch strategy

Pull Requests

Merge conflict handling

Release management

Documentation & proof

Perfect for training, academic submission, interviews, and real-world practice.
