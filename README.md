# AI-Powered Fitness Recommendation Platform

# Overview

AI-Powered Fitness Recommendation Platform is a microservices-based fitness application designed to provide personalized workout plans and track user fitness activities. The system integrates artificial intelligence to generate workout recommendations based on user goals, fitness history, and preferences.

The application demonstrates modern backend architecture using microservices, secure authentication, asynchronous communication, and AI integration.

# Key Features

* User registration and authentication

* Workout creation and tracking

* AI-generated workout recommendations

* Microservices-based architecture

* Event-driven communication between services

* API Gateway for centralized routing

* Service discovery for dynamic scaling

* Centralized configuration management

# System Architecture

```text
Client (React)
      │
API Gateway
      │
Service Discovery
      │
-----------------------------
|  User Service             |
|  Workout Service          |
|  AI Recommendation Service|
-----------------------------
      │
Message Broker (RabbitMQ)
      │
Database
```

# Tech Stack
# Backend
* Java
* Spring Boot
* Spring Cloud (Eureka, API Gateway)
* REST APIs
# Frontend
* React.js
# Messaging
* RabbitMQ
* Database
* MySQL

# Microservices Overview
# 1. User Service
* Handles user registration and profile management
# 2. Workout Service
* Manages workout data and user activity tracking
# 3. AI Recommendation Service
* Generates personalized workout plans based on user behavior
# 4. API Gateway
* Routes client requests to appropriate services
# 5. Service Discovery (Eureka)
* Enables dynamic service registration and discovery
