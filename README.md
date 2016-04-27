Wireless Sensor Networks -Project

This project is a multi-hop sensor network developed by programming TelosB motes in NesC language on TinyOs platform. The network is self configuring - Each node senses if there are existing nodes around it or not and then according transforms to either Root node or worker Node. Each node generates a heartbeat signal periodically to communicate to the network that it is alive. All worker nodes in the network gathers temperature and light sensor data and propogate it through the root node to the gateway which further sends the infomation to the host computer. This host computer recieves the information and converts it into readable graphs using Matlab.
