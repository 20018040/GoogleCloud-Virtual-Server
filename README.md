TCP connection with virtual device. 

client_code.py
- Client file that connects client to server.
  1. Asks for the server IP address and its port number
  2. If the servr address and port is valid, creates TCP Connection.
  3. Users are given queries :
       "Q1": "What is the average moisture inside my kitchen fridge in the past three hours?",
       "Q2": "What is the average water consumption per cycle in my smart dishwasher?",
       "Q3": "Which device consumed more electricity among my three IoT devices?"

server_code.py
- Server to create connection and receive user queries.
  1. Asks server host to enter server ip address and port number.
  2. Listens for a conenction, once its built, waits for user query.
  3. Given valid query, answers the query and replies.
 
database_utils.py
- Connects to the database
  1. Reads database and stores information.
  2. Functions to answer queries given by clients.
