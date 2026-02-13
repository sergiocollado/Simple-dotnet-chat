# Simple-dotnet-chat

 References:

  - http://www.csc.villanova.edu/~mprobson/courses/sp21-csc2405/chat.html 
  - https://medium.com/@va.riley/building-a-simple-multi-user-chat-application-and-server-in-c-in-3-steps-b33dee824000
  - https://github.com/sergiocollado/Simple-C-chat
  - https://github.com/sergiocollado/Simple-Rust-chat
  - https://dotnet.microsoft.com/en-us/download/dotnet/10.0


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
 cd Client
 dotnet add reference ./../ChatStream
 cd ../Server
 dotenet add reference ./../ChatStream
 cd ..
 dotnet build
 
 $:~/repos/Simple-dotnet-chat$ dotnet build
Restore complete (1.0s)
  ChatStream netstandard2.0 succeeded (0.3s) → ChatStream/bin/Debug/netstandard2.0/ChatStream.dll
  Client net10.0 succeeded (0.4s) → Client/bin/Debug/net10.0/Client.dll
  Server net10.0 succeeded (0.4s) → Server/bin/Debug/net10.0/Server.dll

 ```
