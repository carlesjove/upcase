source 'https://rubygems.org'

ruby '2.0.0'

gem 'RedCloth', '4.2.9', require: 'redcloth'
gem 'active_model_serializers', '~> 0.7.0'
gem 'acts_as_list', '0.2.0'
gem 'airbrake', '3.1.14'
gem 'aws-sdk', '= 1.6.2' # Bug https://github.com/thoughtbot/paperclip/issues/751
gem 'bluecloth'
gem 'bourbon', '3.1.6'
gem 'clearance', '1.0.1'
gem 'csv_rails', '0.6.1'
gem 'curb', '0.8.1'

gem 'delayed_job_active_record', '4.0.0'
gem 'delayed_job', '~> 4.0.0'

gem 'doorkeeper', '~> 0.7.1'
gem 'dynamic_form', '1.1.4'
gem 'escape_utils', '0.2.4' # Fix UTF-8 regexp match warning
gem 'flutie', '2.0.0'
gem 'formtastic', '2.2.0'
gem 'gravatarify', '~> 3.1.0'
gem 'high_voltage', github: 'thoughtbot/high_voltage'
gem 'httparty', '0.8.1'
gem 'intercom-rails', '~> 0.2.21'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'kissmetrics', '2.0.0'
gem 'nokogiri', '1.5.2'
gem 'octokit', '~> 1.24.0'
gem 'omniauth', '~> 1.1.0'
gem 'omniauth-github', '1.0.2'
gem 'paperclip', '3.4.2'
gem 'paypal-express', '0.4.6', require: 'paypal'
gem 'pg', '0.13.2'
gem 'rack-rewrite', '1.2.1'
gem 'rack-ssl-enforcer', '0.2.4'
gem 'rails', '4.0.1'
gem 'rails_admin', '~> 0.5.0'
gem 'ruby-freshbooks', '0.4.0'
gem 'split', '0.4.1', require: 'split/dashboard'
gem 'stripe', github: 'stripe/stripe-ruby'
gem 'stripe_event', '0.6.0'
gem 'typhoeus', '0.3.3'
gem 'to_js', git: 'git://github.com/cpytel/to_js.git'
gem 'validates_email_format_of', '1.5.3'
gem 'gibbon', '0.4.6'
gem 'sprockets-redirect', github: 'arunagw/sprockets-redirect', branch: 'aa-rails4'
gem 'unicorn'

# Gems used only for assets and not required
# in production environments by default.
gem 'sass-rails', '4.0.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'uglifier', '1.3.0'
gem 'heroku-deflater'

group :development do
  gem 'hirb', '0.6.2'
end

group :development, :test do
  gem 'foreman', '0.46.0'
  gem 'rspec-rails'
  gem 'debugger'
  gem 'pry-rails'
end

group :production, :staging do
  gem 'memcachier'
  gem 'dalli', '2.1.0'
  gem 'newrelic_rpm'
  gem 'rack-cache', '1.2'
  gem 'rails_12factor'
end

group :staging do
  gem 'safety_mailer', '0.0.3'
end

group :test do
  gem 'bourne'
  gem 'capybara'
  gem 'capybara_discoball',
    github: 'thoughtbot/capybara_discoball'
  gem 'capybara-webkit'
  gem 'database_cleaner'
  gem 'email_spec', '1.2.1'
  gem 'factory_girl_rails'
  gem 'launchy'
  gem 'selenium-webdriver'
  gem 'rubyzip', '0.9.9'
  gem 'sham_rack', '1.3.1'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'sinatra'
  gem 'timecop', '0.3.5'
  gem 'webmock', '1.8.7'
end
