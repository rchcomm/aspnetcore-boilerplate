# aspnetcore-boilerplate

Web server on Desktop & Corss platform web server boilerplate
======
concept design
------
  1. trayicon ux
  2. aspnet web server, api service
  3. using SQLite, LiteDB
  4. EntityFrameworkCore
  5. IDentityFramework - EndityFrameworkCore
  6. IdentityServer 4
  7. support signalR
  

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

> trayicon * console * windows service host start life cycle event
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
