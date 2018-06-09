# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~> 4.1.2"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.1"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Windows does not come with time zone data
gem "tzinfo-data", platforms: [:mswin, :mingw]

gem 'haml', '>= 5.0.0'

group :production do
  gem 'unicorn'
  gem 'puma'
end

group :development, :test do
  gem 'gh_contributors'
  gem 'rake', '~> 10.3'
  gem 'rspec'
  gem 'capybara', '>= 2.2.1'
end

