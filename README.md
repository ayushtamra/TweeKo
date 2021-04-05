# TweeKo
### A twitter clone built using ruby on rails currently having a basic User interface
<p align="center">
    <img src="screenshots/demo.gif">
</p>
<!-- ![Demo](screenshots/demo.gif) -->

> Hey, Welcome to the world of tweeks

## 🧐Key features:

- Works on CRUD
    - [x] Creation of a tweek
    - [x] Read a tweek
    - [x] Deletion of a tweek
    - [ ] Updation of a tweek
- Uses sqlite3 for database <br>
#### :octocat:Implementations:
- [x] User signup/signin
- [x] Create a tweek
- [x] Delete a tweek
- [x] Can see other user's profile
- [x] Follow/Unfollow another user
- [x] Can see tweeks by other users
- [x] User can edit profile and can add profile photo through Gravatar
- [ ] Update a tweek

## 🏁Getting started:

### Step 1:
Install ruby on your system: [Ruby official](https://rubyinstaller.org/ "Ruby installer")

### Step 2:
Setup ruby on rails: [Getting Started with Rails](https://guides.rubyonrails.org/getting_started.html "Ruby on rails")

Glad you came to this point, now follow this:
### Step 3:
Check webpacker is installed globally in your system:
```
webpacker -v
```
If not installed:
```npm
npm install --global webpack
```
### Step 4 (🚀Deployment):
Clone this repository on your local system and cd to the directory <br>
Using terminal write this:
- For installing the bundles
```
bundle install
```
- Migration into the database:
```
bundle exec rails db:migrate
```
- Executing the rails server on Localhost
```
bundle exec rails server
```
### 🎉Voila..!! the rail server starts:
<p align="center">
    <img src="screenshots/rails-server-terminal.png">
</p>
<!-- ![Rails server starting](screenshots/rails-server-terminal.png) -->
<br> <br>
With just three commands we whipped up a Rails server listening on port 3000. Go to your browser and open http://localhost:3000, you will see TweeKo running.



## How to contribute to this repository✨

* Fork this repository (Click the Fork button in the top right of this page, click your Profile Image)
* Clone your fork down to your local machine

```markdown
git clone https://github.com/ayushtamra/TweeKo.git
```

* Create a branch

```markdown
git checkout -b branch-name
```

* Make your changes (There are some folders for different category so upload the file accordingly)
* Commit and push

```markdown
git add .
git commit -m 'Commit message'
git push origin branch-name
```
or
* Add the file in the forked repository using upload file option then commit the changes in a new branch. 

* Create a new pull request from your forked repository (Click the `New Pull Request` button located at the top of your repo)
* Wait for your PR review and merge approval!

If you are still facing any problem follow steps given in this [website](https://thenewstack.io/getting-legit-with-git-and-github-your-first-pull-request/)


> Made in India :india: by Ayush❤️

