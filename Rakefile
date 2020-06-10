namespace :greeting do

 desc 'outputs hello to the terminal'
 task :hello do
   puts "hello from Rake!"
 end
 
 desc 'outputs hola to the terminal'
 task :hola do
   puts "hola de Rake!"
 end
end

namespace :db do
  desc 'creates stusents table in database'
  task :migrate => :environment do
  Student.create_table
  end
  
  task :environment do
  require_relative './config/environment'
  end
end

desc 'drops into pry'
task :console do
  Pry.start  
end
  