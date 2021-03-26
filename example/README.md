# Equinix Network Edge example: Check Point CloudGuard firewall device

This example shows how to create redundant Check Point CloudGuard firewall devices
on Platform Equinix using Equinix CloudGuard Terraform module
and Equinix Terraform provider.

In addition to pair of CloudGuard devices, following resources are being
created in this example:

* SSH public key that will be configured on both devices
* two ACL templates, one for each of the device

The devices are created in self managed, bring your own license modes.
Remaining parameters include:

* small hardware platform (2CPU cores, 8GB of memory)
* STD software package
* 50 Mbps of additional internet bandwidth on each device
