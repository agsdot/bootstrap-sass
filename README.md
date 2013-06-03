A small project to test the Bootstrap-Sass gem integration with the
Rails project.

Followed guidelines of the following Daniel Kehoe page :
http://railsapps.github.io/twitter-bootstrap-rails.html

Continued the project in this branch to see if Twitter Bootstraps were
in effect.  Indeed they were.

I applied the following lines of code:

-rails g nifty:scaffold location address:string latitude:float
longitude:float
-rake db:migrate
-rails s

but first removed navigation partials pertaining to devise
