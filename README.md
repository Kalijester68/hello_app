# Ruby on Rails Tutorial

         ___        ______     ____ _                 _  ___
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/
 -----------------------------------------------------------------


Hi there! Welcome to AWS Cloud9!

To get started, create some files, play with the terminal,
or visit https://docs.aws.amazon.com/console/cloud9/ for our documentation.

Happy coding!

==========================================================

## "hello, world!"

This is the first application for the
[*Ruby on Rails Tutorial*](https://www.railstutorial.org/)
by [Michael Hartl](https://www.michaelhartl.com/). Hello, world!

==========================================================

#CLI

rvm get stable
rvm install 3.1.2
rvm --default use 3.1.2

echo "gem: --no-document" >> ~/.gemrc

gem install rails -v 7.0.4
gem install bundler -v 2.3.14

source <(curl -sL https://cdn.learnenough.com/resize)

rails _7.0.4_ new hello_app --skip-bundle

bundle _2.3.14_ install

Click on url 'shield' icon to turn off enhanced tracking protection
This is for Firefox, not necessary in Chrome
Preview should now be available in AWS Cloud9

git config --global user.name "Your Name"
git config --global user.email your.email@example.com
git config --global init.defaultBranch main
git config --global alias.co checkout

Default is 900 or ~15min per day
git config --global credential.helper "cache --timeout=86400"

cd directory

git init
git add -A
git status
git commit -m "Initialize repository"
git log
git checkout -f
git remote add origin https://github.com/Kalijester68/hello_app.git
git branch -M main

Github Access Token Settings Developer

git push

git checkout -b modify-README

git branch

git commit -a -m "Improve the README file"
git checkout main
git merge modify-README
git branch -d modify-README

git add .

git push

:}
