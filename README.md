# CAP Theorem

## Consistency :
Any read that happens after a write, all the nodes in the system should return the latest value of that write.

## Availability :
Every available node in the system should respond in a non error format to any read request without the guarantee of returning the latest write

## Partition Tolerance :
System should respond to all read and write requests even if the communication between the nodes is broken.
