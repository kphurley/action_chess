# README

## Dependencies

Ruby 3.2.2
Sqlite 3
Redis

## Getting this running

- clone
- `bundle install`
- `yarn install`
- `rails db:migrate`
- `rails db:seed`
- (seperate terminal) - `redis-server`

This gets us pretty close.  We can use the accounts in the seeds file to login after this point, and you can see a list of challengers.

TODO

- login/logout doesn't appear to be implemented
