# Make sure you're on helloworld branch
git checkout helloworld

# Create README.md file
echo "# Hello World" > README.md

# Stage and commit (Take Screenshot #1)
git add README.md
git commit -m "Add README.md"

# Push to GitHub (Take Screenshot #2)
git push origin helloworld

# After creating and merging pull request on GitHub (Take Screenshot #3 of merged state)

# Update local main (Take Screenshot #4)
git checkout main
git pull

# Update local branch (Take Screenshot #5)
git checkout helloworld
git merge main

# Push updated branch (Take Screenshot #6)
git push origin helloworld
