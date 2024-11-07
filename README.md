# Biv-Quack

<div style="display:flex; flex-direction: row; justify-content: center; align-items: center; width: 100vw">
  <a target="_blank" href="https://github.com/VincentDub2/Biv-Quack">
  <img alt="github link" src="https://img.shields.io/badge/Biv'Quack-global-orange?logo=github&style=for-the-badge">
</a>
<a target="_blank" href="">
  <img alt="github link" src="https://img.shields.io/badge/Biv'Quack-docs-blue?logo=github&style=for-the-badge">
</a>
<a target="_blank" href="https://github.com/VincentDub2/ReactNativeIWA">
  <img alt="github link" src="https://img.shields.io/badge/Biv'Quack-frontend-blue?logo=github&style=for-the-badge">
</a>
<a target="_blank" href="https://github.com/VincentDub2/iwa-spring-kafka">
  <img alt="github link" src="https://img.shields.io/badge/Biv'Quack-microservices-blue?logo=github&style=for-the-badge">
</a>
</div>

---

## Context

This project is a school project for the 5th year of engineering school at [Polytech Montpellier](https://www.polytech.umontpellier.fr/). The purpose of the project was to introduce the concept of microservices and to implement a project with this principle. This project was made by a team of two people. It was made in 2 months out of the classroom.

## Project Summary: Bivouac Spot Booking Application

This application allows hikers, bikepackers, motorcyclists, and other adventurers to find and book bivouac spots. It includes the following features:

### Host Management:

CRUD operations for hosts (first name, last name, phone, email, address).
Admin notifications for validating host account deletion requests.

### Spot Management:

CRUD operations for bivouac spots (location, characteristics, equipment, services).
Search for spots based on specific criteria.
User alerts on spot availability based on chosen criteria.

### Traveler Management:

CRUD for traveler profiles, enabling users to create, modify, or delete their profiles.
User alerts on spot availability based on traveler profile.

### Booking Management:

Validation and management of booking requests.
CRUD for ratings and reviews on hosts and travelers after a stay.

## Tech Stack

### Frontend:

- Developed in React Native using Expo.
- Global state management with Redux.
- I18n Friendly (English & French).
- Testing on a preferred platform (iOS & Web).

### Backend:

- Microservices architecture with services for user management, notifications, rate,locations, messaging & booking  in Spring Boot or Spring Webflux.
- API Gateway for backend accessibility (Spring Cloud Gateway).
- PostgreSQL or MongoDB databases for each microservice.
- Kafka message broker for some of the inter-microservice communication.
- Zookeeper for Kafka cluster management.
- Config Server for configuration management.
- Kotlin on one of the microservices.

### Security:

- JWT for authentication and authorization.
- Spring security for securing the microservices.

### Testing and Build:


### Version Control and Deployment:

- Git flow.
- Containerization with Docker-compose.

### CI/CD:

- Implementation of CI/CD using GitHub Actions.

---

@ Vincent Dubuc & Matéo Iori & Kylian Thezenas & Alexandre Lagorce- IG5 Polytech Montpellier - 2024
