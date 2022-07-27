# This is sample rails app for developing with VSCode devcontainer.

I am playing with it to see how it works.
I started by following with the article 

https://dev.to/imiked/starting-a-rails-app-using-vscode-containers-1gj9

It did not work!!!
and I has to change on database.yml
I had to set user as postgres not LocalPassword as article say.
  adapter: postgresql
  encoding: unicode
  host: db
  user: postgres
  password: LocalPassword xxx not working
  password: postgres      000 this worked

And it worked !!!

My goal now is to push this to github and clone this setup to an other host and run it on another host from my local machine.
without local Docker 