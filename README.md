# 🔗 URL Shortener — Spring Boot + HTML/CSS

A secure and user-friendly URL shortener built using **Spring Boot**, **JWT authentication**, and a clean **HTML/CSS** frontend. It allows users to register, generate shortened URLs, view/manage them through a dashboard, and track redirections.

![Project Logo](https://via.placeholder.com/150x80.png?text=Your+Logo+Here)

---

## :ledger: Index

- [About](#beginner-about)
- [Usage](#zap-usage)
  - [Installation](#electric_plug-installation)
  - [Commands](#package-commands)
- [Development](#wrench-development)
  - [Pre-Requisites](#notebook-pre-requisites)
  - [Development Environment](#nut_and_bolt-development-environment)
  - [File Structure](#file_folder-file-structure)
  - [Build](#hammer-build)
  - [Deployment](#rocket-deployment)
- [Community](#cherry_blossom-community)
  - [Contribution](#fire-contribution)
  - [Branches](#cactus-branches)
  - [Guideline](#exclamation-guideline)
- [FAQ](#question-faq)
- [Resources](#page_facing_up-resources)
- [Gallery](#camera-gallery)
- [Credit/Acknowledgment](#star2-creditacknowledgment)
- [License](#lock-license)

---

## :beginner: About

This project is a simple and secure URL shortener service built using **Spring Boot**. It includes:
- JWT-based authentication
- Short URL generation and redirection
- Dashboard for managing personal URLs
- Clean, responsive UI with HTML/CSS

The backend ensures authorization and secure data handling, while the frontend offers a minimal and intuitive interface.

---

## :zap: Usage

### :electric_plug: Installation

Ensure you have the following installed:

- Java 17+
- Maven 3.6+
- Git

Steps to run locally:

```bash
# Clone the repository
git clone https://github.com/your-org/urlshortener.git
cd urlshortener

# Build and run the application
./mvnw clean install
./mvnw spring-boot:run
