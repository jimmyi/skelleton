source 'https://rubygems.org'

gem 'rails', '3.2.1'
gem 'pg'
gem 'jquery-rails'
gem 'haml-rails'
gem 'tinymce-rails'
gem 'dynamic_form'
gem 'devise'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem "uglifier"
  gem 'compass',      '~> 0.12.alpha'
  gem "zurb-foundation"
end


group :development do
  # The next two are needed by ruby-debug when running in 1.9.3
  platform :ruby_19 do
    gem 'linecache19', :git => 'git://github.com/mark-moseley/linecache'
    gem 'ruby-debug-base19x', '~> 0.11.30.pre4'
    gem "ruby-debug19"
  end
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rspec-rails'
end

group :test do
  gem 'database_cleaner'
end
