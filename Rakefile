require 'rubygems'
require 'bundler'
require 'bundler/setup'
require 'appraisal'

Bundler::GemHelper.install_tasks

require 'rspec/core/rake_task'

desc "Run specs"
RSpec::Core::RakeTask.new("spec") do |t|
  t.pattern = "spec/postgresql_spec.rb"
end
