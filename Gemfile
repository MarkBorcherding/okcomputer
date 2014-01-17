source "http://rubygems.org"


core_path = File.expand_path("../../okcomputer-core", __FILE__)
if File.exist?(core_path)
  gem "okcomputer-core", path: core_path
end

case ENV['RAILS_VERSION'];
when /3.2/
  gem "rails", "~> 3.2.0"
else
  gem "rails", "~> 4.0.0"
end
gemspec
