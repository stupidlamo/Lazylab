Lazylab
======
Lazylab is Network lab deployment automation tool.

Lazylab using KVM as a hypervisor.

It's easy implemented in already running libvirt setup.
Lazylab fully compatible with virt-manager, Ovirt, cockpit-machines.

Install
======

## Fedora/Ubuntu

install libvirt

add your user to libvirt group
```
sudo usermod -a -G libvirt $(whoami)
```
clone lazylab with
```
git clone https://github.com/haddystuff/lazylab
```

Supported network devices
======
Juniper VMX: 14, 18(vcp only)
Cisco iosxrv: 5
