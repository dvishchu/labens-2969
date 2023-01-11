TASK 02: Provisioning of underlay configuration
===============================================

.. image:: assets/underlay.JPG

In this task, we will provision underlay configuration on our devices. This will include configuration of loopback and physical interfaces and as well OSPF and PIM protocols between spine and leaf devices. As a result, we will have full IP reachability between spine and leaf switches and our underlay network will support multicast routing which we can later use for replication of BUM traffic.

Prior we can provision our configuration on devices, we must define variables like interface name, IP address, router IDs… for every device based on which can ansible playbook generate proper configuration for every device. Definition of these device variables can be found in below location. 