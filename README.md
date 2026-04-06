# 🛡️ Active Directory Manager — CyberSec

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-Security_Gated-DC143C?style=for-the-badge)
![Tests](https://img.shields.io/badge/Tests-19%20Passing-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)

---

## 📋 Overview

Active Directory Manager — CyberSec is a full-stack cybersecurity management application built from scratch, simulating enterprise-grade Active Directory administration through a modern dark-themed security interface. The application demonstrates real-world identity and access management (IAM), security policy enforcement, organizational unit management, and compliance audit logging — the core functions of any enterprise cybersecurity operations environment.

This is not a tutorial project. It is a production-ready application with TypeScript type safety, role-based access control security gates, comprehensive unit testing, and compliance-ready audit export functionality.

---

## 🚀 Live Demo

> **[View Live Application](#)** ← Add your live URL here

---

## 🎯 What I Built

A complete Active Directory management platform with 6 fully functional modules, built with a dark cybersecurity interface. Every module implements real enterprise security concepts — RBAC enforcement, audit logging, policy management, and organizational governance.

---

## 🏗️ Application Architecture

```
active-directory-manager-cybersec/
│
├── Dashboard Module
│   ├── Real-time metrics display
│   ├── Area chart (activity trends)
│   ├── Pie chart (user status distribution)
│   └── Live activity feed
│
├── User Management Module
│   ├── Full CRUD operations
│   ├── Search & filter
│   └── Status control (Active / Locked / Disabled / Expired)
│
├── Group Management Module
│   ├── Nested group structure
│   ├── Membership add/remove
│   └── Permission tags
│
├── Organizational Units Module
│   ├── Recursive tree view
│   └── Inline add/edit/delete
│
├── Security Policies Module
│   ├── Password policy configuration
│   ├── Lockout configuration
│   ├── Access controls
│   └── Live security score
│
└── Audit Logs Module
    ├── Paginated log view
    ├── Filter by category & severity
    └── CSV export (compliance-ready)
```

---

## ✨ Key Features

### 🔐 Role-Based Access Control (RBAC)
Security gates restrict destructive actions to admin users only — enforcing the principle of least privilege at the application level. Non-admin users cannot execute delete, disable, or policy-change operations regardless of UI access.

### 📊 Real-Time Dashboard
Live metrics, area charts tracking activity trends, pie charts visualizing user status distribution, and a real-time activity feed — giving security administrators instant situational awareness across the environment.

### 👥 User Management
Full CRUD (Create, Read, Update, Delete) operations with search and filter capabilities. User status management covers the full enterprise lifecycle: Active, Locked, Disabled, and Expired — mirroring real Active Directory account states.

### 🏢 Organizational Units — Recursive Tree View
Hierarchical OU structure with recursive tree rendering, supporting deeply nested organizational hierarchies. Inline add, edit, and delete operations maintain the tree structure without page reloads.

### 🔒 Security Policies with Live Score
Password complexity requirements, account lockout thresholds, and access control configurations — with a live security score that updates in real time as policies are tightened or loosened. Gives administrators immediate feedback on their security posture.

### 📋 Compliance-Ready Audit Logs
Paginated audit log with filtering by category and severity. CSV export functionality makes this compliance-ready for SOX, NIST, and enterprise governance requirements — the same audit trail functionality required in regulated industries.

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| **Language** | TypeScript (error-free) |
| **Frontend Framework** | React |
| **Styling** | Dark cybersecurity theme, custom CSS |
| **Testing** | Vitest — 19 tests passing |
| **Security** | RBAC gates on all destructive actions |
| **Data Export** | CSV export for audit compliance |
| **AI-Assisted Development** | Manus AI, Claude AI, Claude Code (VS Code) |

---

## ✅ Test Coverage

```
 ✓ Dashboard metrics render correctly
 ✓ User CRUD operations — create user
 ✓ User CRUD operations — update user
 ✓ User CRUD operations — delete user (admin only)
 ✓ User status transitions — active to locked
 ✓ User status transitions — active to disabled
 ✓ User search and filter functionality
 ✓ Group membership add operation
 ✓ Group membership remove operation
 ✓ Nested group structure renders correctly
 ✓ OU tree view recursive rendering
 ✓ OU inline add operation
 ✓ OU inline delete operation
 ✓ Security policy password config saves
 ✓ Security policy lockout config saves
 ✓ Live security score updates on policy change
 ✓ Audit log pagination works correctly
 ✓ Audit log CSV export generates correctly
 ✓ RBAC blocks destructive actions for non-admin users

19 tests passing | 0 failing | TypeScript error-free
```

---

## 🔐 Security Concepts Demonstrated

| Concept | Implementation |
|---|---|
| **Role-Based Access Control** | Admin-gated destructive actions across all modules |
| **Least Privilege Principle** | Non-admin users restricted from delete/disable operations |
| **Account Lifecycle Management** | Active, Locked, Disabled, Expired status states |
| **Password Policy Enforcement** | Configurable complexity, length, and expiration requirements |
| **Account Lockout Policy** | Configurable failed attempt thresholds and lockout duration |
| **Audit Trail** | Paginated, filterable logs with CSV export for compliance |
| **Organizational Governance** | Hierarchical OU structure mirroring enterprise AD design |
| **Security Posture Scoring** | Real-time security score based on active policy configuration |

---

## 💼 Enterprise Relevance

This application directly simulates the tools used by:

**IT Security Analysts** — monitoring user accounts, reviewing audit logs, enforcing lockout policies, and managing access controls are daily SOC tasks. This application demonstrates all of them.

**IAM Engineers** — user lifecycle management, group membership, RBAC enforcement, and OU hierarchy management are the core responsibilities of Identity and Access Management roles paying $85-110K.

**Cloud Security Engineers** — Azure Active Directory mirrors every concept in this application. Understanding AD structure, group policy, and account management directly translates to Azure AD, Entra ID, and enterprise cloud identity platforms.

**GRC Analysts** — the audit log with CSV export, security policy documentation, and lockout configuration directly support SOX, NIST 800-53, and ISO 27001 compliance requirements.

---

## 🎓 Certifications This Supports

| Certification | Relevant Concepts |
|---|---|
| **CompTIA Security+** *(In Progress)* | IAM, RBAC, account policies, audit logging, least privilege |
| **Microsoft AZ-104** *(In Progress)* | Azure AD user/group management, RBAC, OU structure |
| **Microsoft AZ-900** *(In Progress)* | Identity concepts, access management, security fundamentals |

---

## 🗂️ Full Project Portfolio

| # | Project | Platform | Key Skills |
|---|---|---|---|
| 1 | Windows VM Deployment | Azure | NSG, RBAC, RDP |
| 2 | Linux VM Deployment | Azure | SSH, NSG, Linux |
| 3 | Cloud Storage Website | Azure | Blob Storage, SAS |
| 4 | Automate Cloud Deployments | Azure | CLI, ARM, IaC |
| 5 | Automate Azure VM with Terraform | Azure + Terraform | IaC, Terraform |
| 6 | Automate Azure Website with Terraform | Azure + Terraform | IaC, Blob Storage |
| 7 | Basic Azure VM Lab | Azure | AZ-900, AZ-104 |
| 8 | AWS S3 Lab | AWS | Multi-Cloud Storage |
| 9 | **Active Directory Manager — CyberSec** | **Full-Stack App** | **IAM, RBAC, TypeScript, React** |

---

## 👤 Author

**Brandon Coleman**
IT Systems Analyst | Cybersecurity · Azure Cloud · Data Analytics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/Bcoleman356/Bcoloe)

📍 Mansfield, TX
