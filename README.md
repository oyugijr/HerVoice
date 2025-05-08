# HerVoice Backend API

[![Node.js CI](https://github.com/yourusername/hervoice-backend/actions/workflows/node.js.yml/badge.svg)](https://github.com/yourusername/hervoice-backend/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A robust Node.js/Express backend for the HerVoice platform - empowering women through storytelling, resources, and community engagement.

## 📌 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Environment Variables](#-environment-variables)
- [API Documentation](#-api-documentation)
- [Database Schema](#-database-schema)
- [Testing](#-testing)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

## 🚀 Features
- **User Authentication**: JWT-based registration/login with role-based access
- **Story Management**: Create/update/delete stories with rich text content
- **Content Moderation**: Flagging system with admin dashboard
- **Forum System**: Threads, comments, and replies with nested discussions
- **Notifications**: Real-time updates for user interactions
- **Security**: Rate limiting, input validation, and SQL injection protection
- **Automated Testing**: 90%+ test coverage with Jest/Supertest

## 💻 Tech Stack
- **Runtime**: Node.js 18+
- **Framework**: Express.js
- **Database**: MySQL 8.0 (with Sequelize ORM)
- **Auth**: JWT, Passport.js
- **Validation**: Joi
- **Logging**: Winston
- **Docs**: Swagger/OpenAPI 3.0
- **Testing**: Jest, Supertest

## 🛠 Getting Started

### Prerequisites
- Node.js v18+
- MySQL 8.0+
- npm v9+
- Redis (for rate limiting - optional)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hervoice-backend.git
   cd hervoice-backend
   ```
   
