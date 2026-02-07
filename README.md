# Cyber Home Lab

## Overview
This repository documents the design, deployment, testing, and analysis of a practical cybersecurity home lab environment.

The lab is built around a bare-metal Ubuntu Server installation, hardened and monitored while being assessed from a Kali Linux virtual machine.

---

## Lab Architecture

- Bare-metal Ubuntu Server 24.04 LTS
- UFW firewall enabled (SSH-only exposure)
- OpenSSH configured and validated
- Internal network (192.168.1.x)
- Kali Linux (Hyper-V VM) for reconnaissance and attack simulation
- Windows Terminal for remote SSH administration

---

## Phase 1: Initial Deployment

- Installed Ubuntu Server on bare metal hardware
- Configured LVM storage
- Enabled and tested SSH access
- Restricted firewall to OpenSSH only
- Verified service exposure using Nmap

---

## Phase 2: Internal Reconnaissance

- Nmap service version detection
- Aggressive OS fingerprinting
- SSH host key identification
- Network path validation (traceroute)

---

## Planned Expansion

- Deploy web services
- Expose additional ports intentionally
- Capture and analyze traffic using Wireshark
- Simulate attack scenarios
- Analyze system logs and attack artifacts
- Implement defensive hardening improvements

---

## Goal

To develop hands-on experience in:

- Linux server administration
- Network reconnaissance
- Service enumeration
- Firewall configuration
- Log analysis
- Attack/defense validation
