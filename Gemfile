source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.7'

gem 'bootsnap',   '~> 1.7', require: false
gem 'jbuilder',   '~> 2.10'
gem 'puma',       '~> 5.3'
gem 'rails',      '~> 6.1'
gem 'sass-rails', '~> 6.0'
gem 'turbolinks', '~> 5.2'
gem 'webpacker',  '~> 5.4'
gem 'pg', '~> 1.2'

group :development, :test do
  gem 'byebug',  '~> 11.1', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'listen',             '~> 3.4'
  gem 'rack-mini-profiler', '~> 2.3'
  gem 'spring',             '~> 2.1'
  gem 'web-console',        '~> 4.1'
end

group :test do
  gem 'capybara',           '~> 3.35'
  gem 'selenium-webdriver', '~> 3.142'
  gem 'webdrivers',         '~> 4.6'
end

group :production do
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# Uncomment the following line if you're running Rails
# on a native Windows system:
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
