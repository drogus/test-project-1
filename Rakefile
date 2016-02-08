require 'rake' # we need rake!!

task :test do
  if rand(2) == 1
    puts 'fail'
    exit 1
  else
    puts 'pass'
  end
end

task :default => :test
