# vmware-administration-guide

# 🖥️ VMware Administration Guide

## Overview

This repository documents VMware administration tasks including virtual machine provisioning, migration, snapshot management, and troubleshooting.

This project reflects hands-on experience managing enterprise VMware infrastructure environments.

---

## VMware Environment

- VMware vSphere 5.x / 6.x
- VCenter Server
- ESXi Hosts
- Horizon View

---

## Key Administration Tasks

### Virtual Machine Provisioning

1. Login to VCenter Server
2. Create new Virtual Machine
3. Select datastore
4. Configure CPU and Memory
5. Attach ISO image
6. Install Operating System

---

### VM Migration (vMotion)

Steps:

1. Right click Virtual Machine
2. Select Migrate
3. Choose Change compute resource
4. Select destination host
5. Complete migration

---

### Storage vMotion

Steps:

1. Right click Virtual Machine
2. Select Migrate
3. Choose Change storage
4. Select destination datastore
5. Complete migration

---

### Snapshot Management

Create Snapshot:

1. Right click VM
2. Snapshot
3. Take snapshot
4. Enter description

Delete Snapshot:

1. Snapshot manager
2. Select snapshot
3. Delete snapshot

---

## Troubleshooting

### VM Not Powering On

- Check datastore availability
- Check host resources
- Verify network connectivity

---

### High CPU Usage

- Check VM resource allocation
- Review host utilization
- Restart services if needed

---

## Use Case

- VMware Administration
- Infrastructure Management
- Virtual Machine Lifecycle
- Enterprise Virtualization Support

---

## Technologies

- VMware vSphere
- VCenter Server
- ESXi
- Horizon View

---

## Author

Mary Jain  
Systems Administrator / Systems Engineer
