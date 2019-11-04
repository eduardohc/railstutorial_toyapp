source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails',        '5.0.0'
gem 'pg'
gem 'puma',         '3.4.0'
gem 'sass-rails',   '5.0.5'
gem 'uglifier',     '3.0.0'
gem 'coffee-rails', '4.2.1'
gem 'jquery-rails', '4.1.1'
gem 'turbolinks',   '5.0.0'
gem 'jbuilder',     '2.4.1'

group :development, :test do
  gem 'byebug', '9.0.0', platforms: [:mri]
end

group :development do
  gem 'web-console',            '3.1.1'
  gem 'listen',                 '3.0.8'
  gem 'spring',                 '1.7.2'
  gem 'spring-watcher-listen',  '2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
