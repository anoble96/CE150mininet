README
CE150 Final Project
Alexander Noble

The finals submitted for this assignment are final_skel.py and finalcontroller_skel.py. The final_skel.py file creates the topology of the subnets. There are four switches each 
connected to two hosts or only one in the case of subnet 4. The four switches are also all connected to switch 1 which enables allowed traffic to travel through. 
The finalcontroller_skel.py file contains the logic for the controller to program rules to the switches based on what type of packets it receives. The controller is
programmed to implement the following policies, taken from the final specifications: "All hosts from the same subnet can communicate with other hosts within the same subnet.Hosts on subnet 10.0.1.0/24 can communicate ONLY with hosts on subnet
10.0.3.0/24 and vice versa. Hosts on subnet 10.0.2.0/24 can communicate ONLY with hosts on subnet 10.0.4.0/24 and vice versa. "