# CIS 658 - RAILS GETTING STARTED

Completion of the tutorial [Ruby on Rails - Getting Started](http://guides.rubyonrails.org/getting_started.html)

## Heroku deployment

Before deploying to heroku, make sure that the *pg* gem version is set to '~>
0.18', otherwise it won't work up there.

1. Create a new heroku application with `heroku create`
2. Deploy by executing `git push heroku master`
3. Run the migration process `heroku run rails db:migrate`
4. Enjoy your deployed app!
