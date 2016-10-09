# README

* [Ruby](http://http//rubyinstaller.org/)
* [Development Kit](http://rubyinstaller.org/downloads/)
* [SQLite3](https://www.sqlite.org/download.html)
* [heroku](https://devcenter.heroku.com/articles/heroku-command-line)

```
gem update --system
gem install bundler --without production
gem install rails
```

```
rails s
rails generate controller StaticPages home help
```
http://localhost:3000/

```
git init
git add -A
git commit -a -m "Initialize repository"
git log
git push --all

git checkout -b modify-README
git branch

git checkout master
git merge modify-README
git branch -d modify-README

git remote rm origin
git remote add origin git@github.com:azureberry/myrails.git
git config --global push.default matching
git config --global alias.co checkout
```

```
heroku --version
heroku login
heroku keys:add
heroku create
git push heroku master
```


=========================

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
