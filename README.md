# Anynines Rails 4.1.0.rc2

[Live demo](http://anynines-rails-beta.de.a9sapp.eu/)

```
bundle
gem install a9s
cf login
bundle exec rake assets:precompile
cf set-env anynines-rails-beta SECRET_KEY_BASE YOUR_SECRET_VALUE
cf push --buildpack https://github.com/heroku/heroku-buildpack-ruby
```
