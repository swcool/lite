require 'rubygems'
require 'rake'

task :default => :deploy

task :deploy do
  sh "cp -rf ./_site/tags ."
  sh "git add ."
  sh "git commit -m 'copy generated tags fold to root and deploy'"
  sh "git push origin master"
end
