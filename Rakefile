require 'bundler/setup'
require 'erubis'

task :build do
  input = File.read('README.erb')
  eruby = Erubis::Eruby.new(input)
  output = eruby.result(binding())
  File.open('README.md', 'w') { |file| file.write(output) }
end

task :default => [:build]
