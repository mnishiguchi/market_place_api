source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'

# https://github.com/rails-api/active_model_serializers
gem 'active_model_serializers'

gem 'awesome_print'
gem 'devise' # 4.2
gem 'faker'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

group :development, :test do
  gem 'factory_girl_rails'
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-byebug'
end

group :development do
  gem 'annotate'
  gem 'guard'
  gem 'guard-minitest'
  gem 'listen', '~> 3.0.5'
  gem 'rails-erd'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'minitest-power_assert'
  gem 'minitest-rails'
  gem 'minitest-reporters'
  gem 'shoulda-context'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
