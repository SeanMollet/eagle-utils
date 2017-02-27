Command line instructions

Git global setup

git config --global user.name "Rachael"
git config --global user.email "rachael@rachellie.co.uk"

Create a new repository

git clone git@gitlab.com:rachaelp/eagle-utils.git
cd eagle-utils
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder

cd existing_folder
git init
git remote add origin git@gitlab.com:rachaelp/eagle-utils.git
git add .
git commit
git push -u origin master

Existing Git repository

cd existing_repo
git remote add origin git@gitlab.com:rachaelp/eagle-utils.git
git push -u origin --all
git push -u origin --tags
