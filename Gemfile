# gemを'https://rubygems.org'から引用する
source 'https://rubygems.org'
# Gemfileの中で:gihubオプションをつけたgemについて、HTTPS経由でGitHubから取得
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
# rubyバージョン3.0.1を指定
ruby '3.0.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
# gem rails 6.0..3verを取得
gem 'rails', '6.0.3'
# Use Puma as the app server
gem 'puma', '4.3.6'
# Use SCSS for stylesheets
gem 'sass-rails', '5.1.0'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '4.0.7'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '5.2.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.9.1'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
# rails起動時の処理を最適化することで、起動時間を短縮してくれるgemを取得：インストール必須ではない時に記載
# 必要であればターミナルでインストールを実行
gem 'bootsnap', '1.4.5', require: false

# 開発環境下のテストの時に実行するグループ
group :development, :test do
  # Use sqlite3 as the database for Active Record
  # gem sqlite3 を取得
  gem 'sqlite3', '~> 1.4'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

# 開発環境で実行するグループ
group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '4.0.1'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '3.1.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '2.1.0'
  gem 'spring-watcher-listen', '2.0.1'
end

# テストの時に実行するグループ
group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '3.28.0'
  gem 'selenium-webdriver', '3.142.4'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers', '4.1.2'
end

# production寛容で実行するグループ
group :production do
  gem 'pg', '1.1.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
