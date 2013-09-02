ChatServer
==========

Simple Ruby Chat Server

Chat server runs on localhost port 1235. The server can be customized with a Public IP address and a different port number, by re-editing line 45 ( server = ChatServer.new(1235, '127.0.0.1')), where 1235 is the TCP port number, and '127.0.0.1' is the current localhost IP address.
To run the server, from the CLI, type "ruby ChatServer.rb", or "ruby ChatServer-dm.rb" if you wish to run the server as deamonized background process.

