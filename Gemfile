source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'jquery-rails'

gem 'popolo-billy', '0.0.2', require: 'popolo/billy', path: 'vendor/gems/popolo-billy-0.0.2'
gem 'decorators', '~> 1.0.0'
gem 'chronic'

gem 'popolo', '0.0.2' # @todo remove on 0.0.3 release

gem 'unicorn'

group :production do
  gem 'newrelic_rpm'
end

group :test, :development do
  gem 'heroku' # Rake task
  gem 'rspec-rails'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'compass-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end
