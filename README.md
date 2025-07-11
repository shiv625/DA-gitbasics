

git config --global user.name "Your Name"





git config --global user.email "you@example.com"




⸻

2. Check Status

git status

If you see:

fatal: not a git repository

It means Git is not initialized. Run:

git init


⸻

3. Stage & Commit

git add .
git commit -m "Your commit message"


⸻

4. Add Remote & Push

git remote add origin <repository-url>
git push -u origin main   # or 'master' if your branch is named so


⸻

5. Clone a Repo

git clone <repository-url>
