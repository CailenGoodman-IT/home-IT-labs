# Virtual Machine Setup – Windows 11 Lab

## Objective
Create a Windows 11 virtual machine using VirtualBox to simulate a real-world IT environment.

## What is Virtualization?
Virtualization allows multiple operating systems to run on one physical machine by allocating system resources (RAM, CPU, storage) to virtual machines.

## Configuration Details

**VM Name:** Win11-Lab-1  
**Type:** Microsoft Windows  
**Version:** Windows 11 (64-bit)  

### Resource Allocation
- RAM: 8GB (allocated from host system)
- Storage: 80GB
- Disk Type: Dynamically Allocated (Thin Provisioning)

## Why Dynamic Allocation?
Dynamic allocation allows the virtual disk to grow as storage is used rather than reserving the full 80GB immediately. This is more storage-efficient for lab environments.

## Key Concepts Learned
- Virtual machines act as separate computers inside a host system
- Resource allocation impacts performance
- Thin vs thick provisioning affects storage usage
