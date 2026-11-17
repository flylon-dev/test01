echo "# test01" >> README.md
git init
git add README.txt
git commit -m "first commit"
git branch -M main
git config --local user.name "flylon-dev"
git config --local user.email "flylon-dev@example.com"
git remote add origin https://flylon-dev@github.com/flylon-dev/test01.git
git remote add origin https://github.com/flylon-dev/test01.git
git push -u origin main