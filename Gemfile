# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~> 4.4.0"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.1"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Windows does not come with time zone data
gem "tzinfo-data", platforms: [:mswin, :mingw]

gem 'haml', '>= 5.0.0'

group :production do
  gem 'unicorn'
  gem 'puma', '>= 4.3.12'
end

group :development, :test do
  gem 'gh_contributors'
  gem 'rake', '~> 12.3', '>= 12.3.3'
  gem 'rspec'
  gem 'capybara'
end

