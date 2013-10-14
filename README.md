# Ruby on Rails Vanilla Application:

This is Anthony Wijnen's vanilla application code for bootstrapping a new Ruby on Rails project:

Core components
- Rails
- Bootstrap
- PSQL
- RSPEC
- HEROKU

Based on the [*Ruby on Rails Tutorial*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).

Get Started

  1. cp -r rails_vanilla_app [your app folder] 
  2. cd [your app folder]
  3. Bundle
      a) bundle install --without production
      b) bundle update
      c) bundle install
  4. Edit [your_app_name_here] in database.yml
  5. Confirm you have local postgresql server running (use Postgres.app for MAC)
  6. Edit readme.rd to relevant documentation for your app
  7. Setup git
      a) rm -rf .git
      b) git init
      b) git add .
      c) git commit -m 'Initial commit'
      d) git remote add origin https://github.com/<username>/your_app_name.git
      e) git push -u origin master 
  8. rake db:create:all
  9. rails server 

  You should now see a vanilla bootstrap-styled rails app in @ http://localhost:3000/
