---
title: "Incremental snapshots/backups in KVM plugin of Apache CloudStack"
slug: incremental-snapshots-backups-in-kvm-plugin-of-apache-cloudstack
speakers:
 - João Jandre Paraquetti
 - Daniel Augusto Veronezi Salvador
 - Bryan Lima
 - Rafael Weingärtner
time_start: 2024-06-04 15:20:00
time_end: 2024-06-04 15:50:00
track: CloudStack
day: 2
timeslot: 11
room: Melody
---

Apache CloudStack (ACS) and KVM are a combination that many organizations decided to adopt. KVM is a widely used hypervisor with a vibrant community and support in different operating system distributions. While developing the KVM plugin functionalities, one normally tries to make use of the full potential of the hypervisor; however, while Libvirt, the toolkit used by ACS to manage KVM VMs, already supports native incremental snapshots, every volume snapshot/backup taken with ACS is a full snapshot/backup. In many situations, always taking full snapshots of volumes is costly for both the storage network and storage systems.This presentation will address the design and efforts of the ACS community to support incremental snapshots/backups for the KVM plugin. Thus, creating a native backup solution in ACS that supports differential copies.