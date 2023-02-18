source 'https://rubygems.org'

gemspec

is_unix = RUBY_PLATFORM =~ /(aix|darwin|linux|(net|free|open)bsd|cygwin|solaris|irix|hpux)/i

if is_unix && ENV['WITH_VTERM']
  gem "vterm", github: "ruby/vterm-gem"
end

gem "yamatanooroti", github: "ruby/yamatanooroti"

gem 'bundler'
gem 'rake'
gem 'test-unit'
gem 'irb', github: "ruby/irb"
