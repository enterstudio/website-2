# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~> 3.3.7"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.1"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Windows does not come with time zone data
gem "tzinfo-data", platforms: [:mswin, :mingw]

gem 'haml'

group :production do
  gem 'unicorn', '>= 4.8.2'
  gem 'puma'
end

group :development, :test do
  gem 'gh_contributors'
  gem 'rake', '~> 10.3'
  gem 'rspec'
  gem 'capybara', '>= 2.2.1'
end

