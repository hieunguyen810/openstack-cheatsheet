# SINGLE NODE INSTALL WITH MICROSTACK

## Installation
### Install:
``` sudo snap install microstack --devmode --beta ``` 

### Enable 
``` sudo snap enable microstack ```

### Disable Microstack:
``` sudo snap disable microstack ```

### Disable
``` sudo snap restart microstack ```	

### Init control node:
``` sudo microstack init --auto --control ```

### Access horizon dashboard
*Dashboard*: https://10.20.20.1

*Login with: admin/<keystone_password>*

### Get keystone password:
``` sudo snap get microstack config.credentials.keystone-password ```

## Get info
### Get flavor list
``` microstack.openstack flavor list ```
### Get image list:
``` microstack.openstack image list ```
### Get networks list 
``` microstack.openstack network list ```
### Get keypair list 
``` microstack.openstack keypair list ```
### Get images list
``` microstack.openstack image list ```
### Get security group list 
``` microstack.openstack security group rule list ```

### Launch VM  
``` microstack launch cirros --name test ```

## List of services:

- snap.microstack.cinder-scheduler.service
- snap.microstack.cinder-uwsgi.service
- snap.microstack.cluster-uwsgi.service
- snap.microstack.glance-api.service
- snap.microstack.horizon-uwsgi.service
- snap.microstack.keystone-uwsgi.service
- snap.microstack.mysqld.service
- snap.microstack.neutron-api.service
- snap.microstack.neutron-ovn-metadata-agent.service
- snap.microstack.nova-api.service
- snap.microstack.nova-api-metadata.service
- snap.microstack.nova-conductor.service
- snap.microstack.nova-spicehtml5proxy.service
- snap.microstack.ovn-ovsdb-server-nb.service
- snap.microstack.ovsdb-server.service
- snap.microstack.placement-uwsgi.service
- snap.microstack.rabbitmq-server.service
- snap.microstack.nova-compute.service
- snap.microstack.ovs-vswitchd.service





















