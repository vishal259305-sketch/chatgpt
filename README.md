# chatgpt

echo "# chatgpt" >> README.md   # Creates a README file
git init                        # Initializes a local Git repo
git add README.md               # Stages the README file
git commit -m "first commit"    # Commits the change
git branch -M main              # Renames branch to main
git remote add origin https://github.com/vishal259305-sketch/chatgpt.git
git push -u origin main         # Pushes your code to GitHub
If you already have an existing local repo:
You don’t need to re-run git init or echo. Just do:

bash
Copy code
git remote add origin https://github.com/vishal259305-sketch/chatgpt.git
git branch -M main
git push -u origin main
⚠️ Common Issues:

If you see fatal: remote origin already exists, run:

bash
Copy code
git remote remove origin
git remote add origin https://github.com/vishal259305-sketch/chatgpt.git
If you get authentication errors, make sure you’re logged in via SSH or HTTPS with a token:

bash
Copy code
git config --global credential.helper store
and then push again.

