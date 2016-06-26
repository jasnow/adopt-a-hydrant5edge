source 'https://rubygems.org'
ruby '2.3.1'

gem 'rails', '5.0.0.racecar1'
gem 'rails_admin', github: 'sferik/rails_admin'
gem 'rack-pjax',   github: 'afcapel/rack-pjax'
gem 'remotipart',  github: 'mshibuya/remotipart'

gem 'arel'
gem 'geokit'
gem 'haml'
gem 'http_accept_language'
gem 'nokogiri'
gem 'pg'
gem 'validates_formatting_of'
gem 'devise'

platforms :ruby_18 do
  gem 'fastercsv'
end

group :assets do
  gem 'sass-rails'
  gem 'uglifier'
end

group :development do
  gem 'spring'
end

group :test do
  gem 'rails-controller-testing'
  gem 'coveralls', require: false
  gem 'rubocop', '0.40.0' # LOCKED DOWN
  gem 'simplecov', require: false
  gem 'sqlite3'
  gem 'webmock'
end

group :production do
  gem 'rails_12factor'
  gem 'puma'
  gem 'skylight'
end
