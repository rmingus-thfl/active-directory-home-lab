# Lab Architecture

## Overview

This Active Directory home lab is designed to simulate a small enterprise network using Oracle VirtualBox. The environment will consist of a Windows Server virtual machine configured as a Domain Controller and a Windows 11 virtual machine joined to the Active Directory domain.

The goal is to provide a realistic environment for learning Windows Server administration, Active Directory, DNS, Group Policy, and Identity and Access Management (IAM) concepts.

## Planned Environment

| Virtual Machine | Operating System | Purpose |
|-----------------|------------------|---------|
| DC01 | Windows Server 2025 Evaluation | Domain Controller, Active Directory Domain Services (AD DS), DNS |
| CLIENT01 | Windows 11 Evaluation | Domain-joined workstation |

## Planned Services

- Active Directory Domain Services (AD DS)
- Domain Name System (DNS)
- Group Policy
- User and Group Management

## Active Directory Domain

The Active Directory domain for this lab will be:

**corp.home**

This domain name was selected to represent a small corporate environment that can be expanded in future projects. The lab is designed to support additional servers and workstations as new technologies are added.

## Network Design

The virtual machines will communicate over a private virtual network within Oracle VirtualBox. This configuration allows the lab environment to function independently while maintaining internet access for software installation and updates.

Additional networking details will be documented during the Virtual Environment Setup phase.

## Architecture Diagram

*A network diagram will be added after the virtual environment has been configured.*



