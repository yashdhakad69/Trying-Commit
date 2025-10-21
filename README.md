# 1. Create a new folder
mkdir my-first-repo

# 2. Go inside it
cd my-first-repo

# 3. Initialize Git
git init

# 4. Create a file (example: README.md)
echo "# My First Repo" > README.md

# 5. Add the file to Git
git add .

# 6. Commit your first change
git commit -m "Initial commit"

# 7. Link this folder to your GitHub repo
git remote add origin https://github.com/YOUR-USERNAME/my-first-repo.git

# 8. Push your code to GitHub
git push -u origin main
