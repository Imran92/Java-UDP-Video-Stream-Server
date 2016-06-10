# Java-UDP-Video-Stream-Server

This server is based UDP protocol as most of the streaming server in the world are based on. What it actually does is taking
continuous screenshots of the video playing window using the Java Robot class and send it via UDP Datagram packets. 

This also includes chatting option. As packet loss is not acceptable in case of chatting or file transfer, we use TCP protocol for
the chatting server. 

To run this project, you need to run the server in 32 bit netbeans or eclipse. Because for video playing, it uses VLC 32 bit java core.
We could use the 64 bit version of VLC, but the core is not stable yet and throws errors. You can run the client from anywhere you want.

For this project to function, you have to have VLC media player installed in it's default directory. If you use your custom directory,
don't forget to change the part of the code where necessary.

In the repo, there are some JAR libs like Java Native Library and VLCJ, you must add them in your project path. 
