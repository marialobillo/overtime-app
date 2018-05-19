source 'https://rubygems.org'

git_source(:github) do |repo_name|
	repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
	"https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.4'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'sqlite3', '~> 1.3', '>= 1.3.13'
gem 'devise', '~> 4.4', '>= 4.4.3'

group :development, :test do
	gem 'byebug'
	gem 'rspec-rails', '~> 3.0'
	gem 'capybara'
	gem 'database_cleaner'
end

group :development do
	gem 'listen', '~> 3.1.5'
	gem 'web-console', '~> 2.0'
	gem 'spring'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
