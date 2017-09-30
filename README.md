# Projects
Multi-threaded Skype like application which has three major components: 1) Authentication server, 2) Super node and 3)Peers (Users). Authentication server allows users to register and login. To make the registration persistent it stores all the user credentials to text file in encrypted format. After the user has successfully logged- in, the user is assigned to one of the super node. The peers can become friends with the help of super node. After the peers are connected, they can directly connect to each other as long as the other peer is online. The program uses the concept of critical section, threading, forking, randomization, file I/O etc.
