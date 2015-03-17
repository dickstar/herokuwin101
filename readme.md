在Windows安裝HEROKU需要注意到的地方

改安裝新的pg
gem install pg --pre

gem 'pg', '~> 0.18'
#http://stackoverflow.com/questions/23022258/tzinfodatasourcenotfound-error-starting-rails-v4-1-0-server-on-windows
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]