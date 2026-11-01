git --version
git config --global user.name "Your Full Name"
git config --global user.email "your.email@example.com"cd web-development-practice
git init# Create index.html (or create it in VS Code)
echo "<!DOCTYPE html><html><head><title>My Project</title></head><body><h1>Welcome</h1></body></html>" > index.html

git status
git add index.html
git commit -m "feat: add initial HTML boilerplate"
git status
git add index.html
git commit -m "feat: add footer section with copyright"
git log --oneline