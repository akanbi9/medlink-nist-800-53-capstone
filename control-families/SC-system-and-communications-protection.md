# SC — System and Communications Protection

## Purpose

The System and Communications Protection (SC) family focuses on protecting MedLink Services Ltd.'s network, communications, and data in transit.

The assessment focuses on:

* Network boundaries
* Remote access
* Network segmentation
* VPN
* Encryption in transit
* Firewall rules
* Secure network communications

---

# 1. Network Security Diagram

The following diagram represents the high-level network architecture of MedLink Services Ltd.

```text
                         INTERNET
                             |
                             v
                         FIREWALL
                             |
                             v
                           ROUTER
                             |
                             v
                           SWITCH
                  ___________|____________
                 |           |            |
                 v           v            v
          STAFF NETWORK   SERVERS    GUEST WI-FI
                 |           |            |
                 |           |       Isolated Network
                 |           |
                 |      Customer Database
                 |
          Employee Computers


        REMOTE WORKERS
              |
              v
             VPN
              |
              v
           FIREWALL
              |
              v
       INTERNAL NETWORK


       SECURITY MONITORING
              |
              v
     Logs / Alerts / Detection
```

## Network Components

| Component           | Purpose                                                                 |
| ------------------- | ----------------------------------------------------------------------- |
| Internet            | External network connection                                             |
| Firewall            | Controls traffic entering and leaving the network                       |
| Router              | Directs network traffic                                                 |
| Switch              | Connects internal network devices                                       |
| Staff Network       | Provides access for authorized employees                                |
| Servers             | Hosts internal services and applications                                |
| Guest Wi-Fi         | Provides internet access to visitors without access to internal systems |
| VPN                 | Provides secure remote access for authorized workers                    |
| Customer Database   | Stores customer information                                             |
| Security Monitoring | Collects and reviews security events                                    |

---

# 2. Network Boundaries

Network boundaries define where MedLink's internal network begins and where external networks or services are separated from it.

## Main Network Boundaries

### Internet Boundary

The firewall separates MedLink's internal network from the public Internet.

```text
Internet
   |
   v
Firewall
   |
   v
Internal Network
```

The firewall should control and inspect traffic crossing this boundary.

### Guest Network Boundary

Guest Wi-Fi should be separated from the internal employee network.

```text
Guest Wi-Fi
     |
     X
Internal Network
```

Guests should not be able to directly access:

* Employee computers
* Internal servers
* Customer databases
* Administrative systems

### Remote Access Boundary

Remote workers should connect through an approved secure remote-access mechanism such as a VPN.

```text
Remote Worker
      |
     VPN
      |
  Firewall
      |
Internal Network
```

---

# 3. Remote Access Requirements

Remote access should only be provided to authorized users and should be controlled according to business requirements.

## Requirements

* [ ] Remote users must be authorized.
* [ ] VPN or another approved secure access method must be used.
* [ ] MFA should be enabled for remote access.
* [ ] Remote users should receive only the access required for their job.
* [ ] Remote connections should use encrypted communications.
* [ ] Remote access activity should be logged.
* [ ] Remote access accounts should be reviewed periodically.
* [ ] Former employees and contractors should have remote access removed.
* [ ] Administrative remote access should be restricted.
* [ ] Suspicious remote-access activity should be investigated.

## Remote Access Process

```text
Remote Worker
      |
      v
   Internet
      |
      v
     VPN
      |
      v
   Firewall
      |
      v
Authorized Internal Resources
```

---

# 4. Network Segmentation Recommendations

Network segmentation separates systems and users into different network areas to reduce unnecessary access.

## Recommended Segments

| Network Segment       | Purpose                         | Access                        |
| --------------------- | ------------------------------- | ----------------------------- |
| Staff Network         | Employee computers              | Authorized internal resources |
| Server Network        | Internal servers                | Restricted                    |
| Guest Network         | Visitors                        | Internet only                 |
| Management Network    | Network/security administration | Authorized administrators     |
| Remote Access Network | VPN users                       | Limited authorized resources  |

## Guest Wi-Fi

Guest Wi-Fi should be isolated from the internal network.

```text
Guest Wi-Fi
     |
     v
Internet

     X

Internal Network
     |
     +---- Staff
     +---- Servers
     +---- Customer Database
```

## Server Segmentation

Servers containing important business or customer information should not be directly accessible by every employee device.

Access should be restricted based on:

* User role
* Business requirement
* Application requirement
* Security policy

## Customer Database

The customer database should have restricted network access.

Only authorized applications, administrators, or services should be able to communicate with it.

---

# 5. VPN Requirements

A VPN should be used to protect remote connections between authorized remote workers and MedLink's network.

## VPN Security Requirements

* [ ] VPN access requires authentication.
* [ ] MFA is enabled where supported.
* [ ] VPN connections use strong encryption.
* [ ] VPN users are authorized.
* [ ] Access is based on user role.
* [ ] VPN activity is logged.
* [ ] Inactive or terminated accounts are disabled.
* [ ] Administrative VPN access is restricted.
* [ ] VPN configuration is reviewed periodically.

---

# 6. Encryption in Transit

Sensitive information should be protected while travelling across networks.

Examples include:

* Employee credentials
* Customer information
* Authentication information
* Business information
* Remote-access traffic

## Encryption Requirements

* [ ] Sensitive web traffic uses HTTPS/TLS.
* [ ] Remote access uses encrypted VPN connections.
* [ ] Sensitive data is not transmitted using insecure protocols.
* [ ] Secure protocols are used instead of unencrypted alternatives.
* [ ] Certificates are properly managed.
* [ ] Encryption configurations are reviewed periodically.

### Example

```text
INSECURE

Computer ---------> Server
       Unencrypted Data


SECURE

Computer =====TLS/VPN=====> Server
          Encrypted Data
```

---

# 7. Firewall Rule-Review Checklist

Firewall rules should be reviewed periodically to ensure that only required network traffic is permitted.

## Firewall Checklist

* [ ] Firewall rules have documented business purposes.
* [ ] Rules have an identified owner.
* [ ] Unnecessary rules are removed.
* [ ] Any/Any rules are avoided unless specifically justified.
* [ ] Inbound traffic is restricted.
* [ ] Outbound traffic is controlled where required.
* [ ] Administrative access is restricted.
* [ ] Remote-access rules are reviewed.
* [ ] Guest network traffic is isolated.
* [ ] Rules are reviewed periodically.
* [ ] Firewall changes are approved.
* [ ] Firewall activity is logged.
* [ ] Denied traffic is monitored for suspicious activity.

## Firewall Rule Review Table

| Rule ID | Source      | Destination        | Port/Protocol     | Purpose        | Owner | Status   |
| ------- | ----------- | ------------------ | ----------------- | -------------- | ----- | -------- |
| FW-001  | Internet    | Public Website     | HTTPS/443         | Website access | IT    | Approved |
| FW-002  | VPN Users   | Internal Resources | Required Services | Remote access  | IT    | Approved |
| FW-003  | Guest Wi-Fi | Internet           | Required Traffic  | Guest access   | IT    | Approved |
| FW-004  | Guest Wi-Fi | Internal Network   | Any               | Not required   | IT    | Blocked  |

---

# 8. Security Monitoring

Network security events should be monitored to identify suspicious activity.

Security monitoring may include:

* Firewall logs
* VPN logs
* Authentication logs
* Network alerts
* IDS/IPS alerts
* Server logs
* Security incidents

```text
Network Devices
      |
      v
     Logs
      |
      v
Security Monitoring
      |
      v
Alerts / Investigation
```

---

# 9. Practical Evidence

| Artifact                        | Purpose                                            |
| ------------------------------- | -------------------------------------------------- |
| Network Security Diagram        | Shows network architecture and boundaries          |
| Remote Access Requirements      | Defines how remote connections should be secured   |
| Segmentation Recommendations    | Shows how networks should be separated             |
| Encryption-in-Transit Checklist | Verifies protection of data during transmission    |
| Firewall Rule-Review Checklist  | Ensures firewall rules are controlled and reviewed |
| Firewall Rule Review Table      | Provides evidence of firewall configuration review |

## Assessment Status

**Status:** Partially Implemented — Simulated

**Reason:** The MedLink scenario includes network equipment, remote/hybrid workers, cloud services, guest Wi-Fi, and security monitoring. However, the scenario does not provide complete evidence of documented network segmentation, remote-access requirements, encryption-in-transit reviews, or formal firewall rule reviews.

## Recommended Improvement

MedLink should document its network boundaries, implement appropriate network segmentation, require secure remote access, protect sensitive communications using encryption, and perform periodic firewall rule reviews.
