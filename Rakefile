namespace :greeting do
  desc 'outputs hello to the terminal'
    task :hello do
      puts "hello from Rake!"
    end
  
    desc 'outputs hello to the terminal, but in Spanish'
    task :hola do
      puts "hola de Rake!"
    end
  end

  namespace :db do
    desc 'migrate changes to your database'
    task :migrate => :environment do
      Student.create_table
    end
  end
