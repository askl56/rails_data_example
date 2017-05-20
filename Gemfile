source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails',          '5.1.1'
gem 'pg',             '0.20'
gem 'puma',           '3.8.2'
gem 'sass-rails',     '5.0.6'
gem 'uglifier',       '3.2.0'
gem 'turbolinks',     '5.0.1'
gem 'jbuilder',       '2.6.4'
gem 'jquery-rails',   '4.3.1'

group :development, :test do
  gem 'rspec-rails',  '3.6.0'
  gem 'pry',          '0.10.4'
  gem 'pry-rails',    '0.3.6'
  gem 'lograge',      '0.5.1'
end

group :development do
  gem 'web-console',           '3.5.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.1'
  gem 'spring-watcher-listen', '2.0.1'
end
