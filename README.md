# max-bpatcher
Use of bpatcher in Max 7.

This patcher demonstrates how to use the same bpatcher multiple times, processing unique buffers. 
This method works only in abstractions (not in sub-patchers).

Within the bpatcher a random name is assigned using the #0 syntax.
If you need to access that buffer outside the bpatcher, return the name as demonstrated.

PLEASE IGNORE code uploaded before 1 March 2017.
