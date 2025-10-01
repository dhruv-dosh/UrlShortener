# 🔗 UrlShortener: Real-Time URL Shortening and Analytics Platform

**UrlShortener** is a powerful, modern URL shortening service that allows users to instantly generate short links, securely manage them, and track comprehensive real-time analytics. Built with a robust Spring Boot backend and a responsive React frontend, UrlShortener is designed to be fast, scalable, and user-friendly.

## 📌 Overview

UrlShortener provides a complete solution for link management. Beyond just shortening long URLs, it offers detailed, real-time insights into link usage, including the total number of clicks and individual user interactions. The platform ensures a personalized and secure experience through full user authentication and a modern, fast user interface.

## 🔥 Key Features

  * **✅ Shorten Links:** Instantly generate concise, shareable short URLs for any long link.
  * **📈 Analytics Dashboard:** Access a powerful dashboard to track the performance of every link, showing the total number of clicks.
  * **👤 User Tracking:** Monitor granular link usage, tracking individual clicks associated with authenticated users.
  * **🔒 User Authentication:** Secure login and signup functionality powered by JWT for a personalized and private link management experience.
  * **✨ Modern UI:** A smooth, reactive frontend built with ReactJS for an excellent user experience.
  * **🚀 Fast & Scalable:** A robust and efficient backend powered by Spring Boot ensures high performance and scalability.

## 🛠️ Tech Stack

UrlShortener is a full-stack application leveraging modern, industry-standard technologies:

### Backend (API)

| Technology | Purpose |
| :--- | :--- |
| **Spring Boot** | Core framework for the RESTful API, providing speed and stability. |
| **Spring Security** | Handling authorization, user authentication, and securing endpoints. |
| **JWT Authentication** | Secure, stateless authentication for API communication. |
| **MySQL/PostgreSQL** | Relational database for persistence of short links, long URLs, user data, and click analytics. |

### Frontend (UI)

| Technology | Purpose |
| :--- | :--- |
| **ReactJS** | Library for building the responsive and dynamic Single Page Application (SPA). |
| **React Router** | Managing client-side routing and navigation within the application. |
| **Axios** | Efficient, promise-based HTTP client for communicating with the Spring Boot API. |

## ⚙️ Getting Started

Follow these steps to set up and run UrlShortener locally.

### Prerequisites

  * Java Development Kit (JDK 17 or newer)
  * Node.js and npm (or yarn)
  * A running instance of MySQL or PostgreSQL database.
  * Maven (for Spring Boot build)

### 1\. Database Setup

1.  Create a new database instance named `urlshortener_db` (or similar).
2.  Update the database connection properties in the backend's `application.properties` or `application.yml` file with your credentials:
    ```yaml
    # Example for Spring Boot (application.yml)
    spring:
      datasource:
        url: jdbc:postgresql://localhost:5432/urlshortener_db
        username: your_db_user
        password: your_db_password
    ```

### 2\. Backend Setup

1.  Navigate to the `backend` directory (or equivalent).
2.  Build the project using Maven:
    ```bash
    mvn clean install
    ```
3.  Run the application:
    ```bash
    java -jar target/urlshortener-backend-*.jar
    # OR if using an IDE like IntelliJ, run the main application class.
    ```
    The API should start running on `http://localhost:8080`.

### 3\. Frontend Setup

1.  Navigate to the `frontend` directory (or equivalent).
2.  Install the dependencies:
    ```bash
    npm install
    # OR yarn install
    ```
3.  Start the development server:
    ```bash
    npm start
    # OR yarn start
    ```
    The React application should open in your browser at `http://localhost:3000` (or the configured port).

## 🤝 Contribution

We welcome contributions\! If you have suggestions for new features, bug fixes, or improvements, please:

1.  Fork the repository.
2.  Create a new feature branch (`git checkout -b feature/amazing-feature`).
3.  Commit your changes (`git commit -m 'feat: Add amazing feature'`).
4.  Push to the branch (`git push origin feature/amazing-feature`).
5.  Open a Pull Request.

## 🚀 Future Enhancements

We aim to make the setup and deployment process even simpler through containerization.

### Dockerization

We plan to implement **Docker** and **Docker Compose** to enable users to spin up the entire application stack (Frontend, Backend, and Database) with a single command.

**Goal:**

1.  **Containerize** the Spring Boot API and the React UI.
2.  Provide a `docker-compose.yml` file to link the services, including a database container.

**Future Run Command:**

```bash
docker-compose up -d
```

*This will significantly reduce local configuration and dependency management.*

 *For In Depth Java Notes [Java_Notes](https://github.com/dhruv-dosh/Java_In_Depth_Notes)*
 
 *For Learning Spring Boot [Spring boot](https://github.com/dhruv-dosh/Spring_Java_Framework)*
 
 *For Learning Docker [Docker](https://github.com/dhruv-dosh/Docker_Notes_And_Commands)*
 
 *For Learning Jenkins [Jenkins](https://github.com/dhruv-dosh/Jenkins_Declarative_Pipeline_Setup)*

*Created and maintained by [dhruv-doshi](https://github.com/dhruv-dosh)*
