# ORO Wallet

A full-stack mobile banking platform with an integrated custodial cryptocurrency wallet built using Flutter, Node.js, PostgreSQL, Stripe, and Ethereum.

> Portfolio showcase repository. Source code is private.

---

## Project Overview

ORO Wallet is a mobile application that allows users to securely manage digital assets through a backend-controlled custodial wallet system.

The platform supports:

* User registration and authentication
* Biometric login
* Wallet balance tracking
* Transaction history
* Peer-to-peer token transfers
* Token purchases through Stripe
* Blockchain-backed asset management

The project was developed as a functional MVP demonstrating mobile application architecture, backend API development, payment processing, ledger accounting, and blockchain integration.

---

## Demo Video

https://github.com/andrii-spitsyn/oro-wallet-showcase/blob/main/video/ORO%20Wallet%20Presentation.mp4

*The demonstration was recorded from an earlier MVP build. The current version contains additional improvements and features not shown in the recording.*

---

## Screenshots

### 1. Home Page
Main dashboard displaying wallet balance, quick actions, and recent transactions.

<img width="360" height="725" alt="home_page" src="https://github.com/user-attachments/assets/280452a3-8b34-40a5-b26d-aae6ccc84d87" />

### 2. Account Page
User profile information and wallet address management.

<img width="360" height="725" alt="account_page" src="https://github.com/user-attachments/assets/783f3fe7-dc45-4eb4-ad76-95150b3555f2" />

### 3. Settings Page
Application configuration, biometric authentication, and security settings.

<img width="360" height="725" alt="settings_page" src="https://github.com/user-attachments/assets/8a933482-8132-459a-985f-625903f81677" />

### 4. Send ORO Page
Peer-to-peer transfer workflow with recipient selection and amount validation.

<img width="360" height="725" alt="send_oro_page" src="https://github.com/user-attachments/assets/14aa92bc-de3a-4a3e-8471-72d5102474b5" />

### 5. Buy ORO Page
Token purchase workflow integrated with Stripe payment processing.

<img width="360" height="725" alt="buy_oro_page" src="https://github.com/user-attachments/assets/4305f3b7-5d08-40a5-9a68-6afc624b02f5" />


---

## Technology Stack

### Mobile Application

* Flutter
* Dart
* Hive
* Dependency Injection

### Backend

* Node.js
* PostgreSQL
* REST API Architecture

### Integrations

* Stripe Payments
* Ethereum Sepolia
* Ethers.js

---

## Architecture

The system follows a backend-controlled custodial wallet model.

Users never interact directly with the blockchain.

All blockchain operations are validated and executed through backend services.

User
↓
Flutter Mobile App
↓
Node.js API
↓
Business Services
↓
Ledger & Database
↓
Ethereum Smart Contract

Key architectural decisions:

* Service-based Flutter architecture
* Dependency Injection
* Ledger-backed transaction tracking
* Backend-controlled transaction execution
* Encrypted private key storage
* Separation of presentation and business logic

---

## Key Features

### Secure Authentication

* PIN-based login
* Encrypted private key storage
* Biometric authentication support

### Wallet Operations

* Balance management
* Transaction history
* Quick-send functionality
* Peer-to-peer transfers

### Payments

* Stripe payment processing
* Automated token issuance workflow

### Transaction Tracking

* Ledger-backed transaction history
* Pending and confirmed transaction states
* Balance synchronization

---

## Personal Contribution

This project was designed and implemented as a full-stack application, including:

* Flutter mobile application development
* Application architecture design
* Backend API implementation
* Database schema design
* Blockchain integration
* Payment workflow implementation
* Transaction processing logic

---

## Source Code Availability

The source code is intentionally private because the project is intended for continued development.

This repository serves as a portfolio showcase of the application's architecture, functionality, and implementation approach.
