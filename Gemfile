source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem "bootsnap", ">= 1.1.0", require: false
gem "jbuilder", "~> 2.5"
gem "puma", "~> 3.11"
gem "rails", "~> 5.2.0"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "byebug", platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

group :production do
  gem "pg"
  gem "rails_12factor"
end

group :development, :test do
  gem "awesome_print"
  gem "better_errors"
  gem "binding_of_caller"
  gem "console_ip_whitelist", github: "firstdraft/console_ip_whitelist"
  gem "dotenv-rails"
  gem "draft_log", github: "firstdraft/draft_log"
  gem "grade_runner", github: "firstdraft/grade_runner"
  gem "pry-rails"
  gem "sqlite3"
  gem "web_git", github: "firstdraft/web_git"
end

group :development do
  gem "annotate"
  gem "dev_toolbar", github: "firstdraft/dev_toolbar"
  gem "draft_generators", github: "firstdraft/draft_generators"
  gem "letter_opener"
  gem "meta_request"
end

group :test do
  gem "capybara"
  gem "factory_bot_rails"
  gem "rspec-html-matchers"
  gem "rspec-rails"
  gem "webmock"
end
