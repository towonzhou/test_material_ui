# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

spec = Gem::Specification.find_by_name 'materialUi-rails'
load "#{spec.gem_dir}/lib/material-ui-rails/tasks/muirails.rake"

Rails.application.load_tasks
