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
  Students.create_table
  
end

desc 'drops into pry'
task :console do
  Pry.start  
end
  