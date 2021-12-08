task :serve do
  sh "bundle exec jekyll serve"
end 

task :build do
  sh "bundle exec jekyll build"
end

task :bw do
  sh "bundle exec jekyll build --watch"
end 

task :deploy do
  sh "cd _site; git add .; git commit -am new-deploy; git push -u origin master"
end

task :deploy do
  sh "cd _site; git init; git remote add origin https://github.com/alu0100879902/alu0100879902.github.io; touch .nojekyll; git add .; git commit -am new-deploy; git push -u --force origin master"
  end