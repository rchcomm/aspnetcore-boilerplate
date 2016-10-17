# aspnetcore-boilerplate

Web server on Desktop & Corss platform web server boilerplate
======
concept design
------
  ## trayicon ux
  ## aspnet web server, api service
  ## using SQLite, LiteDB
  ## EntityFrameworkCore
  ## IDentityFramework - EndityFrameworkCore
  ## IdentityServer 4
  ## support signalR
  

solution structure
------

> function
  + multi port & multi host in inner process
  + support multi tenant

> web server project
  + user management
  + role management
  + menu management
  + menu-role management

> trayicon * console host start life cycle event
  + prestart
  + start
  + started
  + prepause
  + pause
  + paused
  + preresume
  + resume
  + resumed
  + prestop
  + stop
  + stoped
  + preexit
  + exit
  + exited
