# ThreadSafe – Secure E2EE Messaging Architecture

Portfolio repository documenting my system architecture and infrastructure design contributions to the ThreadSafe secure messaging platform.

---

## Overview

ThreadSafe is a secure end to end encrypted messaging platform supporting:

- One to one encrypted messaging
- Group chat communication
- Role-based permissions
- Secure key exchange
- Read receipts
- Message persistence controls
- Secure authentication workflows

The platform was designed around modern distributed systems and cryptographic principles.

---

## My Role

I contributed primarily as:

- System Architect
- Infrastructure Designer
- API/Dataflow Planner

---

## Contributions

My responsibilities included:

- Designing the three-server microservices architecture
- Creating system dataflow and infrastructure diagrams
- Defining frontend/backend API interaction structure
- Planning scalable message routing workflows
- Designing secure key-management architecture
- Supporting encryption pipeline planning using:
  - ECC
  - AES-256
  - Double Ratchet concepts

---

## System Workflow

1. User authenticates securely
2. Frontend communicates with backend services
3. Messages are encrypted client-side
4. Secure routing service manages message delivery
5. Key-management service handles encryption keys
6. Backend stores encrypted metadata and message states
7. Recipients decrypt messages securely

---

## Technologies & Concepts

- Python
- Flask
- React
- Docker
- REST APIs
- Microservices
- End-to-End Encryption
- AES-256
- ECC
- Distributed Systems
- Secure Communication Protocols

---

## Original Project Repository

https://github.com/joshtnguyen/ThreadSafe

---

## Note

This repository serves as a portfolio documentation project focused on my architectural and system design contributions. It does not claim ownership of the original collaborative codebase.
