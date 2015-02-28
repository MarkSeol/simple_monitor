# simple_monitor
It's a simple monitor, which consist of two parts, the agent and server.
The agent used to collect data from machines, currently it can collect cpu usage, memory usage, disk usage, netflow, connection count.
The agent will send these data to the server, the server will save the data to Round Robin Database.
Finally the collected data can be demonstrated in graph.
