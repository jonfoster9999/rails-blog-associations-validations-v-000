# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

RailsBlog::Application.load_tasks


task :console do
require 'irb'
require './config/environment'
ARGV.clear
IRB.start
end
