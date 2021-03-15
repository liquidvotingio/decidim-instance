# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", "0.24.0.rc2"
gem "decidim-proposals", "0.24.0.rc2"
gem "decidim-liquidvoting", path: "../decidim-module-liquidvoting"

gem "bootsnap", "~> 1.4.6"

gem "puma", ">= 5.0.0"
gem "uglifier", "~> 4.1"

gem "faker", "~> 1.9"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri

  gem "decidim-dev", "0.24.0.rc2"
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end
