# Motager - مُتاجر

![image](https://github.com/user-attachments/assets/9d585f32-7889-4d32-9dc2-95e678099820)

# Motager – E-commerce SaaS for the MENA Region

Motager is an e-commerce building platform designed specifically for the MENA region. It helps non-technical users create professional online stores, with enhanced SEO, rich product descriptions, and full Arabic localization. Built using scalable microservices architecture with Go for high performance and reliability.

---

## Table of Contents

* [Introduction](#introduction)
* [Features](#features)
* [AI-Powered Product Description](#ai-powered-product-description)
* [Tech Stack](#tech-stack)
* [System Architecture](#system-architecture)
* [Future Features and Updates](#future-features-and-updates)
* [Team Members](#team-members)

---

## Introduction

Many users in the MENA region face real challenges when trying to launch an online store:

* Lack of technical experience to build websites or communicate their needs to developers
* Poor product descriptions that negatively affect search engine visibility
* Inadequate support for Arabic language and regional customization
* Platforms that can’t scale properly with user growth
* Difficulty competing online due to inconsistent pricing across different stores

Motager aims to solve these issues with a robust and region-focused solution.

---

## Features

### User Management

* Email registration and login with verification
* Secure authentication with JWT
* Password reset and profile updates

### Store Creation

* Easy-to-use store builder with server-side generation (SSG)
* SEO-friendly structure
* Ready-made themes designed for Arabic layout (RTL support)

### Product Management

* Add and manage products
* Auto-generated product descriptions using AI
* Categorization, filtering, and media upload

---

## AI-Powered Product Description

Motager integrates a machine learning model trained on real Amazon product data. This allows automatic generation of SEO-optimized product descriptions, helping store owners attract more traffic and increase conversion rates.

* Built using Python, FastAPI, and TensorFlow
* Integrated directly into the product creation flow
* Descriptions are generated in real time with high relevance and clarity

---

## Tech Stack

### Backend

* Language: Go (Golang)
* Architecture: Microservices
* Database: PostgreSQL for transactional data, MongoDB for logging
* Communication: REST and gRPC
* Containerization: Docker
* Hosting: DigitalOcean

### Frontend

* Framework: Next.js (React)
* Rendering: Server-Side Generation
* Styling: Tailwind CSS
* Deployment: Nginx reverse proxy

### Mobile (Planned)

* Language: Kotlin
* Design Pattern: MVVM
* Platform: Android

---

## System Architecture

Motager follows a clean, scalable microservices architecture:

* Authentication Service: Handles user registration, login, and tokens
* Logger Service: Records logs and events in MongoDB
* Mailer Service: Sends email using SMTP; tested with MailHog
* Broker Service: Acts as the internal API gateway between services
* Frontend App: Communicates with backend through the broker
* Admin Dashboard: Manages products, users, and settings

All services are containerized using Docker and managed via Docker Compose.

---

## Future Features and Updates

* Support for multi-tenancy (multiple stores under same platform)
* Advanced analytics and dashboards for merchants
* Mobile application release
* Integration with regional payment gateways
* AI-based product recommendation system
* OTP login and Two-Factor Authentication

## Team Members
## 👥 Team members

Meet the amazing team behind this project:

<table>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/63597605?v=4" width="100px"/><br />
      <a href="https://github.com/robaa12">Robaa</a><br/>
      <sub><i>Backend Developer</i></sub>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/130296979?v=4" width="100px"/><br />
      <a href="https://github.com/Gamgom29">Abdelrahman Tamer</a><br/>
      <sub><i>Full Stack Developer</i></sub>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/152120823?v=4" width="100px"/><br />
      <a href="https://github.com/youseftrek">Yousef Tarek</a><br/>
      <sub><i>Frontend Developer</i></sub>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/130584325?v=4" width="100px"/><br />
      <a href="https://github.com/AhmedNabilko">Ahmed Ibrahim</a><br/>
      <sub><i>Backend Developer</i></sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/130024306?v=4" width="100px"/><br />
      <a href="https://github.com/AhmedEl-Malky">Ahmed Elmalky</a><br/>
      <sub><i>Android Developer</i></sub>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/130070306?v=4" width="100px"/><br />
      <a href="https://github.com/khedr0">Omar Khedr</a><br/>
      <sub><i>Android Developer</i></sub>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/142066798?v=4" width="100px"/><br />
      <a href="https://github.com/Abdallah035">Abdallah Mohamed</a><br/>
      <sub><i>AI Engineer</i></sub>
    </td>
    
  </tr>
</table>
