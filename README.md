hartnse
=======

<b>UPDATE:</b> repository moved to BitBucket: https://bitbucket.org/dark_k3y/hartnse

HART-IP slave gateway RTU devices scan NSE script.
The HART Communications Protocol (Highway Addressable Remote Transducer Protocol) is
a digital industrial automation protocol. HART is used for communicating between master 
(i.e. host computer with HART modem, PLC or HART field communicator) and slave (RTU 
device, Remote Transmitter Unit, like transmitter or actuator). The main task of HART
is configuring and monitoring state of field devices. HART-IP is a HART protocol lower 
level. HART-IP using standard HART master-slave communication scheme, i.e. master device 
sends commands to slave devices. Slave devices are listening for master commands on UDP 
or TCP port. This script is intended for checking opened HART port whether gateway or 
RTU is running on it. 
