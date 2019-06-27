# p2p Democracy

> Distributed and participative (real) democracy

## Description

I don't trust in actual voting system. They are centralized under 
cliente-server architecture, so compromising the server meand 
compromising the whole system. 

This should be a voting system based on p2p tools ([Dat](https://github.com/datproject/dat)). 
The benefit of this p2p technology, is that ever peer (voter) has 
read access to every other peer, and writing access to their own files.
With no central server with voting results, hacking on this system becomes virtually 
impossible, if some peers get compromised, the rest of them will have the actual info, so
to hack this system it would be necesary to hack every single peer of the network.

## How should it work

- When a peer cast a vote, it will broadcast an update to every 
other peer.
- Every peer must have a reference to a resume file.
- Resume files must be updated ONLY when votes are casted. Only once per peer.
