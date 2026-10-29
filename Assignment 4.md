Repository with at Least Three Meaningful Commits?

Aim: To create a Git repository and save project changes using at least three meaningful commits.

Introduction:
Git is a version control system used to track changes in files. A repository stores project files, and a commit saves a version of the changes with a meaningful message.

Procedure:
Step 1: Set Git Identity
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
Step 2: Create a Repository
mkdir html-css-assignments
cd html-css-assignments
git init
git branch -M main
Step 3: First Commit
Create a README file and save it.
echo "# HTML & CSS Assignments" > README.md
git add README.md
git commit -m "docs: add README"
Step 4: Second Commit
Add assignments 1–5 and save the changes.
git add 01-*.md 02-*.md 03-*.md 04-*.md 05-*.md
git commit -m "docs: add assignments 1-5"
Step 5: Third Commit
Add HTML assignments 6–10 and save the changes.
git add 06-*.html 07-*.html 08-*.html 09-*.html 10-*.html
git commit -m "feat: add HTML assignments 6-10"
Step 6: Check Commit History
git log --oneline
This command displays the commit history.

Result:
A Git repository is created, and the project changes are saved using at least three meaningful commits.