source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby '2.5.1'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.0'
# Use sqlite3 as the database for Active Record
gem 'pg'
# Use Puma as the app server
gem 'puma', '~> 3.11'
gem 'bcrypt', '~> 3.1.7'
gem 'jwt', '~> 1.5', '>= 1.5.4'
gem 'pry'
#facker
gem 'faker'
#pagination
gem 'will_paginate', '~> 3.1.0'
#serializer
gem 'active_model_serializers', '~> 0.10.2'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 3.4', '>= 3.4.2'
  gem 'factory_bot_rails', '~> 4.8', '>= 4.8.2'
  gem 'faker'
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.1'
  gem 'database_cleaner', '~> 1.5', '>= 1.5.3'

end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
