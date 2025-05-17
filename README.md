
cd /path/to/your/project    # go to your project's folder

git init                    # initialize Git (if not already done)
git add .                   # stage all files
git commit -m "Initial commit"    # commit your code

# Add the GitHub repository as a remote
git remote add origin https://github.com/YOUR_USERNAME/my-website.git

# Push the code
git branch -M main
git push -u origin main