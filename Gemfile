source 'http://rubygems.org'

# Specify your gem's dependencies in gridinit-jmeter.gemspec
gemspec

gem 'nokogiri'
gem 'rest-client'
gem 'json'

platforms :jruby do
  gem 'json-jruby'
end

group :development do
  gem 'pry', :require => 'pry'
  gem 'pry-nav', :require => 'pry-nav'
  gem 'pry-debugger'
  gem 'awesome_print', :require => 'ap'
end

group :test do
  gem 'rake'
  gem 'rspec'
  gem 'sinatra'
  gem 'haml'
end
