## About

Manage dynamic information for the CSQB client without the need for recompilation, such as tunnel tokens and server metadata. 

Hosts - managed during the setup, need to recompile hostconf.dll in csqb-client

Tunnels - auto updated by the csqb server, the client synchronizes these updates upon starting up the executable. when adding or removing a service, need to recompile hostconf.dll on new setup update.