ENV["SINATRA_ENV"] ||= "development"

require './app'
require_relative './environment'
require 'sinatra/activerecord/rake'
require 'pry'
# Type `rake -T` on your command line to see the available rake tasks.

task :console do
  Pry.start
end