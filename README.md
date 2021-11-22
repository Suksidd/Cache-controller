# Cache-controller

The controller cache is a physical memory region that speeds up two types of I/O (input/output) operations: communication between controllers and hosts, and communication between controllers and discs. The hosts and controllers interact via high-speed links to read and write data. However, because discs are sluggish devices, communications from the controller's back end to the discs are slower. 

When the controller cache gets data, it notifies the host apps that the data is now in its possession. The host programmes will not have to wait for the I/O to be written to disc in this manner. Instead, apps can carry on with their work. Server programmes can also access the cached data directly, reducing the need for further disc accesses. In this project report we have implemented a simple cache controller and its simulation is done.
