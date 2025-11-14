🧩 Jenga API – Flutter & Node.js Integration

A streamlined, production-ready implementation of Jenga API using a Node.js backend and a Flutter client application. This repository provides a clean, modular structure for integrating Jenga payment services—including mobile money, card payments, and bank transfers—into modern applications.

🚀 Overview

This project demonstrates a full-stack integration of Safaricom’s Jenga Payment Gateway using:

Flutter (frontend/mobile app)

Node.js + Express (backend API)

Jenga API (payments, account validation, transaction status)

It’s designed as a starter template for developers building fintech and e-commerce apps that require secure, real-time payment processing.

✨ Features
🔐 Backend (Node.js)

Jenga API authentication (API key, secret, merchant code)

Endpoints for:

Mobile money checkout (Mpesa, Airtel Money, Telkom)

Card payments

Bank-to-bank transactions

Transaction status queries

Secure HMAC signature generation

Environment-based configuration (dotenv)

Clean Express router structure

📱 Frontend (Flutter)

Responsive UI for initiating payments

Form validation for amount, phone, and account number

REST API integration with backend

Real-time transaction feedback

Clean state management (Provider or Riverpod)

🏗️ Tech Stack
Backend

Node.js

Express.js

Axios

Dotenv

Crypto

Frontend

Flutter

Dart

HTTP package

Provider / Riverpod (optional)
