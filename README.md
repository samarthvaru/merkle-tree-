# Description
There are three Python programs in this repo:

### buildmtree.py
Creates a merkle tree and writes the tree output into a file "merkle.tree" to represent in a user friendly format. 


### checkinclusion.py
This program takes a certain string as input and returns whether the string exists in the merkle tree constructed by the         buildmtree.py program and the hashes of the intermediate nodes used to verify the output


### checkconsistency.py
This program takes two lists of nodes as input, verifies that they are consistent and outputs the consistency proof. **Assumption: First list is always smaller than second list**


