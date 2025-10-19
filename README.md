# xen-to-vmware-conversion
Field-proven manual migration method from Citrix XenServer 7.2 to VMware ESXi 6.7 using a nested hypervisor bridge and P2V conversion.
# Cross-Hypervisor Migration – XenServer 7.2 to VMware ESXi 6.7 (Manual P2V Conversion via Nested Hypervisor Bridge)

**Author:** Alessandro Giussani  
**Year:** 2019  

## Overview
This repository provides a complete, field-tested procedure for migrating virtual machines from **Citrix XenServer 7.2** to **VMware ESXi 6.7**, using a **manual P2V (Physical-to-Virtual) conversion** method through a **nested hypervisor bridge**.

## Motivation
No direct or compatible tool existed for this kind of migration.  
This document was written as a contribution for system administrators who need to move workloads from XenServer to VMware without commercial migration software.

## Key Concepts
- Nested XenServer environment running inside VMware ESXi 6.7  
- Windows 10 Control VM with *XenCenter* and *VMware vCenter Converter*  
- Internal Virtual LAN connecting the nested Xen and Windows control VMs  
- Full step-by-step conversion with post-migration fixes for Linux and Windows guests

## Files
- `Cross-Hypervisor_Migration_AlexGiussani.pdf` – main document with technical diagram  

- `README.md` – this file  

## Author Note
*This is a contribution for those who need to move from Xen to VMware.*

---

