Using emptyDir As type of Volume:
1.An emptyDir volume is first created when a Pod is assigned to a Node, and exists as long as that Pod is running on that node. As the name says, it is initially empty. Containers in the Pod can all read and write the same files in the emptyDir volume, though that volume can be mounted at the same or different paths in each Container. When a Pod is removed from a node for any reason, the data in the emptyDir is deleted forever.
2.A Container crashing does NOT remove a Pod from a node, so the data in an emptyDir volume is safe across Container crashes.

