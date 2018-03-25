# frozen_string_literal: true
source 'https://rubygems.org'

group :development do
  gem 'rspec'
  gem 'rake'
  gem 'rdoc'
  gem 'json'
  gem 'simplecov'
  gem 'samus'
  gem 'coveralls', :require => false
  gem 'rubocop'  , :require => false
end

group :asciidoc do
  gem 'asciidoctor'
end

group :markdown do
  gem 'redcarpet'
  gem 'kramdown', :platforms => :jruby
end

group :textile do
  gem 'RedCloth', :platforms => [:ruby, :mingw, :x64_mingw]
end

group :server do
  gem 'rack'
end

group :i18n do
  gem 'gettext', '>= 2.2.1'
end
