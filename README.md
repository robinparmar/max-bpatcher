# max-bpatcher
Use of bpatcher in Max 7.

This is a sketch (incomplete patcher) showing how to use the same bpatcher multiple times, to process different buffers. There are two methods.

METHOD 1
Explicitly name the buffers. In this case we can define the buffers in the calling (master) patch. This has the advantage of clarity, but perhaps faces scaling problems. (What if we need 84 buffers?)

METHOD 2
Use randomly generated names. This method works only in abstractions, so it is perfect for a bpatcher. However, the buffer name is not known to the main patch. If you need to process the buffer anywhere else, return the name from the bpatcher.
