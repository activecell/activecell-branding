# A sample Guardfile
# More info at https://github.com/guard/guard#readme

# guard 'coffeescript', :input => 'app/assets/javascripts'

guard 'sass', :input => 'sass', :output => 'stylesheets'

guard :jammit, :config_path => '_assets.yml', :output_folder => 'javascripts/'  do
  watch(%r{^javascripts/(.*)\.js$})
end

# Any files created or modified in the 'source' directory
# will be copied to the 'target' directory. Update the
# guard as appropriate for your needs.

guard :copy, :from => 'stylesheets', :to => 'dist/stylesheets', :run_at_start => true, :mkpath => true, :delete => true
guard :copy, :from => 'javascripts', :to => 'dist/javascripts', :run_at_start => true, :mkpath => true, :delete => true
# guard :copy, :from => 'fonts', :to => 'dist/fonts', :run_at_start => true, :mkpath => true, :delete => true
