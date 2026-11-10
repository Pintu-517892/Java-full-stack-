<!-- Pintu Sharma | Java Developer Portfolio -->

<div align="center">

# 👋 Hi, I'm Pintu Sharma

### Java Developer · Java Full Stack Developer · Software Development Engineer

**Java | Spring Boot | Angular | REST APIs | Microservices**

*I enjoy building reliable backend services and practical full-stack applications.*

[![GitHub](https://img.shields.io/badge/GitHub-Pintu--517892-181717?style=flat-square&logo=github)](https://github.com/Pintu-517892)

</div>

---

## 👨‍💻 About Me

I'm a **Java Developer** aspiring to grow as a **Java Full Stack Developer**, focused on backend engineering and end-to-end application development. I work with Java and the Spring ecosystem, and build my frontend skills with Angular and TypeScript.

I'm interested in designing clean REST APIs, building secure services, working with relational and NoSQL databases, and understanding how applications are developed, tested, and deployed. I value readable code, practical problem-solving, and continuous learning.

- 🔹 Backend development with Java and Spring Boot
- 🔹 Full-stack application development with Angular
- 🔹 REST API design, authentication, and authorization
- 🔹 Microservices, messaging, and database integration
- 🔹 Cloud, Linux, containers, and CI/CD practices

## 🎯 Roles I'm Open To

| Role | Focus |
|---|---|
| **Java Developer** | Core Java, Spring Boot, REST APIs |
| **Java Full Stack Developer** | Java backend, Angular frontend, database integration |
| **Software Development Engineer (SDE)** | Problem-solving, application development, and software design |

---

## 🧰 Technical Skills

| Category | Technologies |
|---|---|
| **Programming Languages** | Java 8, Java 11, Java 17, SQL, JavaScript, TypeScript |
| **Core Java** | OOP, Collections Framework, Generics, Exception Handling, Multithreading, Lambda Expressions, Stream API |
| **Backend Development** | Spring Framework, Spring Boot, Spring MVC, Spring Data JPA, Hibernate |
| **API & Security** | REST APIs, Spring Security, JWT Authentication, Authentication & Authorization |
| **Microservices & Messaging** | Microservices Architecture, Spring Cloud, API Gateway, Service Discovery, OpenFeign, Apache Kafka |
| **Frontend Development** | Angular, HTML5, CSS3, Bootstrap, TypeScript |
| **Databases & Caching** | MySQL, PostgreSQL, MongoDB, Redis |
| **Cloud & DevOps** | AWS, Linux, Shell Scripting, Docker, Kubernetes, Jenkins, CI/CD |
| **Testing & API Tools** | JUnit, Mockito, Postman, Swagger / OpenAPI |
| **Development Tools** | Git, GitHub, Maven, VS Code, IntelliJ IDEA |

## ⚙️ Technology Stack

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=java,js,ts" alt="Java, JavaScript and TypeScript" />

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=spring,hibernate" alt="Spring and Hibernate" />

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=angular,html,css,bootstrap" alt="Angular, HTML, CSS and Bootstrap" />

**Databases & Messaging**
<br/>
<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis,kafka" alt="MySQL, PostgreSQL, MongoDB, Redis and Kafka" />

**Cloud & DevOps**
<br/>
<img src="https://skillicons.dev/icons?i=aws,linux,bash,docker,kubernetes,jenkins" alt="AWS, Linux, Bash, Docker, Kubernetes and Jenkins" />

**Tools**
<br/>
<img src="https://skillicons.dev/icons?i=git,github,maven,postman,vscode,idea" alt="Git, GitHub, Maven, Postman, VS Code and IntelliJ IDEA" />

</div>

---

## 🚀 Featured Projects

> **Portfolio note:** These project descriptions define the intended scope. Repository links will be added when the implementations are published. They are not presented as completed projects.

### 🔐 1. Authentication & Authorization Service

A secure authentication service built around Spring Security and token-based access control. It is designed to protect application resources and manage user identities and roles.

**Key features**
- User registration and login.
- Spring Security configuration for endpoint protection.
- JWT access-token generation and validation.
- Refresh-token workflow and token expiration handling.
- Role-Based Access Control (RBAC).
- Secure password hashing before storage.
- REST endpoints for authentication and user management.
- PostgreSQL persistence for users, roles, and related data.

**Technology stack**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**High-level request flow**

```text
Client → Login API → Authentication Manager
       → User Details + Password Verification
       → JWT Issued → Client
       → Protected API → JWT Validation → Authorization → Response
```

### 🛒 2. E-Commerce Backend with Microservices

A modular commerce backend designed to separate product, order, inventory, and payment responsibilities into focused services.

**Key features**
- Product catalogue and product-management APIs.
- Order creation and order-status management.
- Inventory availability and stock-update workflows.
- Payment integration boundary.
- REST-based communication between services.
- Event-driven messaging with Apache Kafka.
- PostgreSQL persistence for service data.
- Independent service responsibilities and API contracts.

**Technology stack**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**High-level service flow**

```text
Angular / API Client
        |
   API Gateway
        |
  +-----+---------+-------------+
  |               |             |
Product Service  Order Service  Inventory Service
  |               |             |
PostgreSQL      Kafka Events   PostgreSQL
        |
  Payment Integration
```

### ✈️ 3. Airline Reservation Management System

A full-stack airline reservation application for flight discovery, passenger management, and booking workflows.

**Key features**
- Search flights by source, destination, and travel date.
- View flight schedules and availability.
- Manage passenger details.
- Create, view, and cancel reservations.
- Validate booking requests and handle booking states.
- Expose backend functionality through REST APIs.
- Build an Angular interface for search and reservation workflows.
- Store flight, passenger, and booking data in PostgreSQL.

**Technology stack**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**High-level booking flow**

```text
Angular UI → Flight Search API → Flight Service
           → Availability Check → Booking API
           → Reservation Service → PostgreSQL
           → Booking Confirmation
```

---

## 🧠 Engineering Interests

- Designing scalable and maintainable backend systems.
- Building secure authentication and authorization systems.
- Exploring microservices architecture and service communication.
- Understanding distributed systems and event-driven architecture.
- Improving database design, indexing, and query performance.
- Exploring cloud-native application development.
- Automating build, test, and deployment workflows with CI/CD.
- Writing clean, reusable, and testable code.
- Learning system design and software architecture.

## 📊 GitHub Statistics

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Pintu-517892&show_icons=true&hide_border=true&theme=tokyonight" alt="GitHub profile statistics" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pintu-517892&layout=compact&hide_border=true&theme=tokyonight" alt="Most used languages in public repositories" />
  <br/>
  <img src="https://streak-stats.demolab.com?user=Pintu-517892&hide_border=true&theme=tokyonight" alt="GitHub contribution streak" />
</div>

## 📈 GitHub Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Pintu-517892&theme=tokyo-night&hide_border=true" alt="GitHub contribution activity graph" />
</div>

---

## 🤝 Connect With Me

- **GitHub:** [github.com/Pintu-517892](https://github.com/Pintu-517892)

<div align="center">

*Thanks for visiting my profile. Always learning, building, and improving.*

</div>
