# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "graphael-rails"
  gem.homepage = "http://github.com/cschwartz/graphael-rails"
  gem.license = "MIT"
  gem.summary = %Q{raphael and graphael bundle for rails}
  gem.description = gem.summary
  gem.email = "christian.schwartz@informatik.uni-wuerzburg.de"
  gem.authors = ["christian schwartz"]
  gem.files.include Dir['vendor/**/*'].to_a
end
Jeweler::RubygemsDotOrgTasks.new

