source 'https://rubygems.org'
ruby '2.3.0'

gem 'rails',       github: 'rails/rails'
gem "devise"
gem 'rails_admin', github: 'sferik/rails_admin'
gem "rack-pjax",   github: 'afcapel/rack-pjax'
gem 'remotipart',  github: 'mshibuya/remotipart'

gem 'arel'
gem 'geokit'
gem 'haml'
gem 'http_accept_language'
gem 'nokogiri'
gem 'pg'
gem 'validates_formatting_of'

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
  gem 'rubocop'
  gem 'simplecov', require: false
  gem 'sqlite3'
  gem 'webmock'
end

group :production do
  gem 'rails_12factor'
  gem 'puma'
  gem 'skylight'
end
