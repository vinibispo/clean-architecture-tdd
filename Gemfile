# frozen_string_literal: true

source "https://rubygems.org"

gem "sinatra", github: "sinatra/sinatra"

group :development, :test do
  gem "rspec"
end
group :development do
  gem "lefthook", require: false
  gem "solargraph", require: false
  gem "standard"
  gem "tapioca", require: false
end

group :test do
  gem "simplecov", require: false
end
