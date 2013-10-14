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
  2. Setup git
      a) rm -rf .git
      b) git add .
      c) git commit -m 'Initial commit'
      d) git remote add origin https://github.com/<username>/your_app_name.git
      e) git push -u origin master
  2. Confirm you have local postgresql server running (use Postgres.app for MAC)
  3. Edit [your_app_name_here] in database.yml
  4. Bundle
      a) bundle install --without production
      b) bundle update
      c) bundle install
  5. rake db:migrate
