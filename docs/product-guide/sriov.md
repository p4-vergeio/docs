# SR-IOV NICs

one of the types of passthrough supported
pass to VMs or tenants

!!! note "NVFVergeOS provides full network virtualization, including emulated (virtio) NICs. SR-IOV for NVFs is supported (as of version 4.13) for scenarios where hardware-assisted virutalization is desired."

## Host Installation/Configuration

add to an existing resource group
or create a new resource group
perhaps link to the page that explains this?

Note: When using multiple physical devices for hardware-assisted virtualization, it is often desirable to place multiple physical pci devices of the same type in a resource pool so that the virtual resources can be allocated dynamically to VMs as needed.  VMs can be configured to 

Resource Pools/Rules allow you to create a pool of like devices to allocate to VMs as needed.

Installation/Configuration will need to be completed on each physical node that will house a

1. Consult manufacturer documentation for the SR-IOV NIC hardware; upload any necessary drivers to the VergeIO vSAN. For directions on uploading to the vSAN, see:
[**Uploading to the vSAN (Media Images)**](/public/ProductGuide/uploadingtovSAN)

2. From the Main Dashboard, click **Nodes**.
3. The Nodes listing page appears. **Double-click the appropriate node**.
4. Click **SR-IOV NICs** on the left menu.
5. Click **Add Resource** on the left menu.
6. 


