source "https://rubygems.org"

gemspec name: "mixlib-shellout"

gem "parallel", "< 1.20" # pin until we drop ruby < 2.4

group :docs do
  gem "github-markup"
  gem "redcarpet"
  gem "yard"
end

group :test do
  gem "chefstyle", "1.2.0"
  gem "rake"
  gem "rspec", "~> 3.0"
end

group :debug do
  gem "pry"
  gem "pry-byebug"
  gem "pry-stack_explorer", "~> 0.4.0" # pin until we drop ruby < 2.6
  gem "rb-readline"
end
