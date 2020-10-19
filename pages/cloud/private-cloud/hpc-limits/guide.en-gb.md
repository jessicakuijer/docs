---
title: Technical capabilities
slug: hpc-limits
excerpt: 'Learn the technical capabilities and limitations of the OVHcloud Hosted Private Cloud'
section: FAQ
order: 1
---

**Last updated 19th October 2020**

## Objective

**This page provides an overview of the technical capabilities and limitations of the OVHcloud Hosted Private Cloud service.**

## Capabilities and known limits


| Item | Value | Description |
|:-----:|:-----:|:----------:|
| Max. number of hosts per customer ID |  Depends on # of PCCs | ESXi hosts per organization |
| Number of pcc per nic |   No limit | Number of vCenters or packs per organization |
| Number of linked pccs |  Depends on # of PCCs 0 (not allowed) | vCenters linked Enhanced Linked Mode |
| Minimum hosts per pcc for SLA |  2| Number of hosts per vcenter to maintain SLA |
| Minimum hosts per pcc w/o SLA |  0 | Bare minimum hosts to work with vCenter w/o SLA |
| Max number of hosts per cluster |  Depends on # of PCCs 0 (not allowed) | vCenters linked Enhanced Linked Mode |
| Max number of clusters per pcc |  No limit | Number of cluster within the same virtual Datacenter |
| Max number of virtual DataCenters per pcc |  400 | Virtual Datacenters the customer can add per vCenter |
| Max number of hosts per pcc |  range Hosts: 340 hosts, 70 zpools range Hybrid: 241 hosts, 120 zpools range BigDS: 76 hosts, 205 zpools | Maximum limit of hosts per vCenter |
| Max number of VMs per SDDC |  25000 | VMs managed by the same vCenter |
| Max number of VMs per host |  1024 | VMs hosted in the same physical host |
| Max number of IPs per pcc |  1 x  /23 | Max number of Public IPs assignable and usable per vCenter  |
| vCPUs, RAM and Disk consumed by regular vCenter |  4 vCPU, 16GB RAM, 290GB Disk | Resources assigned to vCenter (VCSA) |
| vCPUs, RAM and Disk consumed by regular NSX |  4 vCPU, 4GB RAM, 60GB Disk; 4 vCPU, 2GB RAM, 28GB Disk | Resources assigned to NSX Manager and Controller |
| vCPUs, RAM and Disk consumed by regular vROPS |  4 vCPU, 16GB RAM | Resources assigned to vROPS |
| Max number of edge nodes |  2000 | Max number of edge devices to be deployed per NSX |
| Max number of IPSec VPN Tunnels |  512 compact edge, 1600 large edge, 4096 quad large edge, 6000 extra large edge | Max number of VPN tunnels per Edge |
| Max number of vRack per vDC |  1 | Max number of Private Networks per vDC |
| Max number of L2 VPN Clients |  5 | Number of VPN clients to connect |



## Go further

Join our community of users on <https://community.ovh.com/en/>.
