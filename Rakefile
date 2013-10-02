require 'rubygems'
require 'rake'

task :default => :deploy

task :deploy do
  sh "cp -rf ./_site/tags ."
  sh "git add ."
  sh "git commit -m 'deploy'"
  sh "git push"
end
