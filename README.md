

# URL Shortener — Spring Boot + HTML/CSS




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

## :beginner: About

**URL Shortener — Spring Boot + HTML/CSS** is a full-stack web application that allows users to quickly register, login, and securely shorten long URLs. Users can manage their links, see a dashboard of all their shortened URLs, and delete links they no longer want. Built using robust and modern technologies: **Spring Boot** for the backend and **HTML/CSS/JavaScript** for the frontend.

The platform features JWT authentication for security, and all redirections are handled efficiently and safely. Its modular design encourages ease of maintenance and extensibility.

## :zap: Usage

The application can be used to:
- Register and manage user accounts.
- Quickly shorten any valid URL after authentication.
- View, manage, and delete your own URLs from a personalized dashboard.
- Seamlessly redirect through short URLs.

### :electric_plug: Installation

#### Backend

1. **Clone the repository:**
   ```bash
   git clone 
   cd backend
   ```

2. **Configure Database:**
   - Edit `src/main/resources/application.properties` with your DB settings (username/password, url, etc.).

3. **Build and Run the Backend Server:**
   ```bash
   ./mvnw spring-boot:run
   ```

#### Frontend

1. Move to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Open `index.html` directly in your browser, or deploy with a local web server (like `live-server` or Python's `http.server`).

### :package: Commands

- **Run backend:**  
  `./mvnw spring-boot:run`
- **Run frontend:**  
  Open `index.html` or serve `/frontend` directory.

## :wrench: Development

### :notebook: Pre-Requisites

- JDK 17+
- Maven 3.8+
- A relational database (MySQL, PostgreSQL, etc.)
- (Optional) Node.js if frontend dependencies are used
- A web browser

### :nut_and_bolt: Development Environment

1. **Clone the project:** Download the repository from GitHub.
2. **Backend:** Install dependencies using Maven. Update database configuration as needed.
3. **Frontend:** No dependencies for basic usage; for extensions, configure as necessary.

### :file_folder: File Structure

```plaintext
.
├── backend
│   ├── src
│   │   ├── controller
│   │   ├── service
│   │   ├── model
│   │   └── repository
│   └── ...
├── frontend
│   ├── public
│   └── src
│       ├── components
│       └── styles
├── README.md
└── ...
```

| No | File/Dir            | Details                  |
|----|---------------------|-------------------------|
| 1  | index.html          | Frontend UI entry point |
| 2  | AuthController.java | Backend authentication  |
| 3  | UrlService.java     | URL logic               |

### :hammer: Build

To build backend:
```bash
cd backend
./mvnw clean install
```

### :rocket: Deployment

- **Backend:** Deploy Spring Boot JAR/WAR to cloud/VPS/server of your choice.
- **Frontend:** Deploy static files to any web hosting or cloud service (Netlify, Vercel, etc.).

## :cherry_blossom: Community

Join us and help evolve this open-source project!

### :fire: Contribution

Your contributions are welcome:

1. **Report a bug:** Open an issue [here](#)
2. **Request a feature:** Suggest a new idea [here](#)
3. **Create a pull request:** Fork, branch (`feat-feature-name`), make changes, and PR to `stage`.

> New to open-source? Check [this guide](https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source).

### :cactus: Branches

- `stage` — Development branch  
- `master` — Production branch  
Feature branches should start from `stage` and be merged via PRs.

### :exclamation: Guideline

- Follow coding best practices.
- Keep commit messages descriptive.
- Ensure your code is linted and tested.

## :question: FAQ

**Q:** Does the app expire short URLs?  
**A:** Not by default, but this can be configured.

**Q:** Can I use a different database?  
**A:** Yes, supported by Spring Boot JPA.

## :page_facing_up: Resources

- [Spring Boot Docs](https://docs.spring.io/spring-boot/docs/current/reference/html/)
- [JWT.io](https://jwt.io/)
- [MDN Web Docs](https://developer.mozilla.org/)

## :camera: Gallery

![Workflow Diagram] ./ProjectWorkFlow.png workflow with authentication, dashboard, and redirection logic*

## :star2: Credit/Acknowledgment

**Team Name:** Vibe Coders

| Name     | Student ID  |
|----------|-------------|
| Gowtham  | 12300278    |
| Mojesh   | 12300281    |
| Anjali   | 12220437    |
| Gopika   | 12212552    |
| Swapnil  | 12206426    |

## :lock: License

Licensed under the [MIT License](./LICENSE).  
© 2025 Vibe Coders

*Last updated: July 15, 2025*

