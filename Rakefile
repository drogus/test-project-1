require 'rake' # we need rake!!

task :test do
  if rand(2) == 1
    echo 'fail'
    exit 1
  else
    echo 'pass'
  end
end

task :default => :test
