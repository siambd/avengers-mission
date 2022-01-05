#for creating a new repository
echo "# avengers-mission" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/siambd/avengers-mission.git
git push -u origin main

#For updating repository
git add .
git commit -m " your message"
git push 
