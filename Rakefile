require 'bundler'
Bundler::GemHelper.install_tasks

require 'rubygems'
require 'rake'
require 'rspec/core/rake_task'

desc "Run specs"
RSpec::Core::RakeTask.new(:spec) do |t|
  t.rspec_opts = ["-c"]
end

task :default => :spec
