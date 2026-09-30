# Hardware inventory

This is a working inventory. Specifications and roles should be verified on each device before being treated as final.

| Device | Known or reported details | Intended or current role | Status |
| --- | --- | --- | --- |
| HP Z2 Mini G9 | Core i9-12900, 32 GB DDR5, 1 TB storage; NVIDIA T1000 reported | Planned primary Proxmox host | OS and final configuration pending |
| [Dell Precision Tower 5810](dell-precision-t5810.md) | Xeon E5-1620 v3 @ 3.50 GHz, four cores; 64 GB DDR4 ECC RDIMM, two 32 GB modules, BIOS speed 2133; BIOS A09; two 256 GB SATA SSDs installed | Planned secondary Proxmox host | Video restored; original HDDs checked and removed; H310 removed; SATA changed to AHCI; Proxmox and ZFS mirror pending |
| [Dell Precision T3600](dell-precision-t3600.md) | 250 GB HDD and optical drive observed; initially 16 GB DDR3, reduced to two 4 GB DIMMs during testing | To be decided | Powers on without display; graphics and cabling assessment unresolved |
| [Dell PowerEdge T310](dell-poweredge-t310.md) | 32 GB RAM; PERC 6/i; four 500 GB drives in RAID 10 (~1 TB usable); Windows 10 Pro | Unassigned; storage and server-management lab candidate | Boot and RAID recovered; four disks online; initial health checks passed; evaluation paused |
| Cisco Catalyst 2960-S | Managed switch; exact model and firmware to verify | Networking lab | Configuration pending |
| BayStack 5520-48T-PWR | 48-port PoE switch; firmware to verify | Networking lab | Configuration pending |
| Personal desktop | Ryzen 7 7800X3D, 32 GB DDR5, 2 TB Samsung 980 Pro, Radeon RX 6950 XT | Administration/testing | Existing workstation |
| Lenovo X1 Carbon Gen 5 | 8 GB RAM; remaining specs to verify | Portable administration/testing | Existing laptop |

The exact Dell specifications, disk health, RAID layout, firmware, and final roles should be captured in dedicated build notes after validation. Avoid publishing serial numbers and identifying labels in photos.

## Inventory procedure

For each machine, record model, CPU, memory, storage, network interfaces, firmware version, operating system, role, and known faults. Link a dated build note and selected evidence when available.
