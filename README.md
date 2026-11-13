# IT Help Desk Home Lab

A virtual lab I built to practice IT help desk fundamentals: Active Directory, DNS, DHCP, Group Policy, permissions, and troubleshooting real-world tickets.

## Lab Environment

| Machine  | OS                         | Role                        | IP          |
|----------|----------------------------|-----------------------------|-------------|
| DC01     | Windows Server 2025 (Eval) | Domain Controller, DNS, DHCP | 10.0.2.10 (static) |
| CLIENT01 | Windows 10/11              | Domain-joined employee PC   | DHCP        |

- **Hypervisor:** Oracle VirtualBox
- **Network:** NAT Network `LabNet` — 10.0.2.0/24, gateway 10.0.2.1
- **Domain:** `corp.lab`

## Progress

- [ ] Create NAT Network (LabNet)
- [ ] Build DC01 and install Windows Server
- [ ] Static IP + rename server
- [ ] Install AD DS and promote to domain controller
- [ ] Configure DHCP scope and DNS forwarder
- [ ] Build CLIENT01 and join it to the domain
- [ ] Create OUs, users, and groups
- [ ] Group Policy (drive mapping, password policy)
- [ ] File shares and NTFS permissions
- [ ] Ticketing system (osTicket)

## Repository Layout

```
docs/          Step-by-step build notes
tickets/       Practice tickets: problem, diagnosis, fix
screenshots/   Images referenced in docs and tickets
```

## Skills Practiced

Active Directory · DNS · DHCP · Group Policy · Windows Server · Windows 10/11 · Virtualization · Networking (TCP/IP) · Troubleshooting · Documentation
