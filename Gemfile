source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "coffee-rails", "~> 4.2"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "puma", "~> 3.0"
gem "rails", "~> 5.0.2"
gem "rubocop", require: false
gem "sass-rails", "~> 5.0"
gem "simple_form"
gem "slim-rails"
gem "sqlite3"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "byebug", platform: :mri
end

group :development do
  gem "web-console", ">= 3.3.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
