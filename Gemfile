source "http://rubygems.org"

ruby "2.1.1"
gem "rails", "4.0.4"

gem "awesome_print"
gem "bourbon"
gem "coffee-rails"
gem "ember-rails"
gem "ember-source"
gem "font-awesome-sass"
gem "jquery-rails"
gem "local_time"
gem "neat", "~> 1.5.0"
gem "newrelic_rpm"
gem "pg"
gem "puma"
gem "roadie"
gem "sass-rails", "~> 4.0.2"
gem "spree", "2.2.0"
gem "spree_auth_devise", github: "spree/spree_auth_devise", branch: "2-2-stable"
gem "spree_gateway",     github: "spree/spree_gateway",     branch: "2-2-stable"
gem "spree_on_the_rocks", path: "../spree_on_the_rocks"
gem "uglifier"

group :development, :test do
  gem "better_errors"
  gem "binding_of_caller"
  gem "dotenv-rails"
  gem "foreman"
  gem "letter_opener"
  gem "quiet_assets"
  gem "rspec-rails"
end

group :test do
  gem "capybara"
  gem "database_cleaner"
  gem "factory_girl_rails"
  gem "faker"
  gem "guard"
  gem "guard-rspec"
  gem "rb-fsevent"
  gem "terminal-notifier-guard"
  gem "vcr"
  gem "webmock"
end

group :production do
  gem "rails_12factor"
end
