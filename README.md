# peersim-generic-DHT
Generic DHT anonymous protocol simulator build on the PeerSim framework.

Main class: peersim.Simulator
Arguments: example.cfg
Class Path: add contents of /lib


## Notes

DHTProtocol
 - linkable - peer connection. Topology
 - transport - connections used for communications
 - address = node location
 - router - processes messages and routes to next node
   - loop_detection = how loops are detected
   - can_backtrack
   - route_store_file

TODO
 - Add address table to DHTProtocol, gets passed to router
 - Add topology generation controllers
