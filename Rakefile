require 'bundler/setup'


desc "upload to S3"
task :upload do
  `s3sync _site/ gollum-sila:  -p`
end
