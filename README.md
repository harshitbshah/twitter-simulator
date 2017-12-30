Date: December 15th, 2017

Group Members:
1. Pradeep Rajan UFID: 1995-­‐3544
2. Harshit Shah UFID: 1211-­‐6976

How to run?
1. hello is the folder containing the code

2. To Build:
a. Unzip the file
b. cd hello
c. running mix deps.get (to fetch the dependences)
d. running mix deps.compile (compile)
e. running cd assets && npm install && node node_modules/brunch/bin/brunch build
f. mix ecto.create
g. mix phx.server

3. Start browser and open two tabs
4. Connect to “localhost:4000”
5. Start tweeting 

Operations supporting
1. Create account
2. Follow
3. Tweet with hash and mentions
4. Retweet
5. Login/logoff
6. Search by Hashtags
7. Search by Mentions

Implementation details
1. We are using Phoenix’s Sockets to communicate with the engine (Server) from clients
2. Sockets internally using web-­‐sockets and transfers data in JSON format.

Video demo link:
https://youtu.be/VBEbz8Tgl44
