source "https://rubygems.org"

gem "rails", "~> 8.1.2"
gem "propshaft"

# データベース：本番環境でもビルド時にインストールされるよう、グループ指定を削除
gem "sqlite3", "~> 1.4", group: [:development, :test]
gem "pg", "~> 1.1"  # グループ指定を削除

gem "carrierwave", "~> 3.0"
gem "net-ssh"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"

gem "tzinfo-data", platforms: %i[ windows jruby ]

gem "solid_cache"
gem "solid_queue"
gem "solid_cable"

gem "bootsnap", require: false

gem "kamal", require: false
gem "thruster", require: false

gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "bundler-audit", require: false
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
  gem "dockerfile-rails", ">= 1.7"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end

gem "aws-sdk-s3", "~> 1.211", require: false