source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.0'

# => Application Stack
gem 'rails', '~> 5.2.2'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'redis', '~> 4.0'
gem 'bcrypt', '~> 3.1.7'

# => Frontend Stack
gem 'uglifier', '>= 1.3.0'
gem 'mini_racer', platforms: :ruby
gem 'turbolinks', '~> 5'
gem 'optimist'
gem 'webpacker'
gem 'react_on_rails', '11.1.4' # Use the exact gem version to match npm version
# gem 'redux_rails' # TODO: See if this is worthwhile to better manage code for dispatchers, etc.,.

# => Core Application Libraries
gem 'rspotify'

# Authorization
gem 'devise'
gem 'omniauth-oauth2'
gem 'omniauth-spotify'
gem 'mailgun_rails'

# => Performance
gem 'bootsnap', '>= 1.1.0', require: false

# => Development Infrastructure
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'dotenv-rails'
  gem 'rspec-rails'
  gem 'rubocop', '~> 0.61.1'
end

# => Development Workflow
group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  gem 'better_errors'
  gem 'binding_of_caller'
end

# => Edge Case Dependencies
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
