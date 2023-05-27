# Internet-Radio-Application
In a GNS topology i implement an Intenert Radio Station that streams songs using multicast in a single AS, and a client that will connect the radio station. 
The server itself is a multithread machine, and it is always online. The server streams multiple songs and handles multiple clients at the same time.
The client plays the song that are streamed from the server, and send queries to the server (change station or upload a new song). 
I used TCP for the control data between the client and the server and UDP for the song data.
