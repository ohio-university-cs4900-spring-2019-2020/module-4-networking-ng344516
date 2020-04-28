# Module 4: Networking

Set to sync commands over sockets. When 'f' is pressed,
an object will be spawned and its location will be sent
over the connection and spawned in the other instance 
as well.

### Current build runs and sends commands, however the
### message is not received and the object does not
### spawn on the other instance.

Set up to run on ports 12684 and 12683. Ports can be set
for each instance in aftr.conf by adjusting the value of
NetServerListenerPort.
