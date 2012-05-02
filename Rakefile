task :install do
  # put this guy in the same place as jekyll
  # because presumably it's in PATH
  loc = `which jekyll`

  raise 'Jekyll not installed' if loc.empty?

  base = '/' + ( loc.split('/')[1..-2] * '/' ) + '/'

  require 'fileutils'
  FileUtils.copy_file('quickpost', base + 'quickpost')
end