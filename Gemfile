source 'https://rubygems.org'

gem 'rails', '3.2.2'

# for deployment on Heroku
gem "heroku"
group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'webrat'
  gem 'spork', '> 0.9.0.rc'
  gem 'ZenTest'
  gem 'autotest-growl'

end
group :production do
  gem 'pg'
  gem 'thin'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'