# Simple-dotnet-chat

 References:
  - https://medium.com/@va.riley/building-a-simple-multi-user-chat-application-and-server-in-c-in-3-steps-b33dee824000
  - http://www.csc.villanova.edu/~mprobson/courses/sp21-csc2405/chat.html 
  - https://github.com/sergiocollado/Simple-C-chat
  - https://github.com/sergiocollado/Simple-Rust-chat


 ## commands to create the solution and projects: 

 ```
 dotnet new sln --name ChatFramework
 git status
 dotnet new classlib --framework "netstandard2.0" -o ChatStream
 dotnet new console -o Server
 dotnet new console -o Client
 dotnet sln add ChatStream
 dotnet sln add Client
 dotnet sln add Server
 ```
