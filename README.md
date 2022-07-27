# This is sample rails app for developing with VSCode devcontainer.

I am playing with it to see how it works.
I started the article 

https://dev.to/imiked/starting-a-rails-app-using-vscode-containers-1gj9


on database.yml
I had to set user as postgres not LocalPassword as article say.
  adapter: postgresql
  encoding: unicode
  host: db
  user: postgres
  # password: LocalPassword
  password: postgres


my goal is to push this to github and
run it with another host from my local machine.