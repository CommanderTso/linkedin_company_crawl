README
------

This is an install of Rails 4.2.6 with the following options:
* Postgres database
* Test-Unit disabled
* Turbolinks disabled


It has the following additional gems installed and configured:
* pry-rails - Replaces IRB for `rails console`
* rspec-rails
* capybara
* launchy
* factory_girl_rails
* dotenv

Misc changes:
* Added flash rendering code to `app/views/layouts/application.html.erb` 

To use this in your own repository:
* Clone this repository
* Delete the .git folder from the project directory
* `git init` and set up your repro

Please hit me up if you have any questions or issues!
