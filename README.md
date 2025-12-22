<div align="center">
  <h1>Aman Yadav</h1>
  <h3>Building scalable backend systems, robust APIs, and high-performance applications.</h3>

  <p>
    <a href="https://www.linkedin.com/in/amanyadav207">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
    </a>
    <a href="mailto:amanyadav130904@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/Resume-View_PDF-000000?style=for-the-badge&logo=pdf&logoColor=white" alt="Resume"/>
    </a>
  </p>
</div>

---

### 👨‍💻 About Me

I am a **Software Engineer** with a strong focus on **backend engineering, distributed systems, and data scalability**. I move beyond "making it work" to building systems that are **reliable, maintainable, and performant** under load. 

My engineering approach centers on **schema design, concurrency control, and API efficiency**. Whether it's architecting an idempotent ETL pipeline or handling race conditions in a booking system, I enjoy solving complex problems that require a deep understanding of database internals and system design.

---

### 🚀 Featured Projects

#### � [SheetGuard (Data Validation & ETL Tool)](#)
*A robust ETL tool designed to solve real-world data migration friction between Google Sheets and Relational Databases.*

- **The Problem**: Manual data entry into databases is error-prone, leading to schema violations and data corruption.
- **Engineering Solution**: 
    - Implemented a **multi-stage validation pipeline** to check for primary key conflicts, missing required fields, and data type mismatches before insertion.
    - Designed an **idempotent ETL process** where invalid rows are isolated into a separate "error bucket" log, ensuring the main pipeline never fails partially.
    - Optimized bulk inserts to handle large datasets efficiently.
- **Tech Stack**: `Node.js` `TypeScript` `PostgreSQL` `Google Sheets API`

#### � [CraveStream (Real-Time Ticket Booking System)](#)
*High-concurrency booking engine handling real-time seat reservations with strict consistency guarantees.*

- **The Problem**: High-traffic booking events often suffer from "double-booking" where two users reserve the same seat simultaneously.
- **Engineering Solution**: 
    - Implemented **pessimistic locking** (SELECT ... FOR UPDATE) and atomic transactions to ensure data integrity during concurrent access.
    - Architected the system to handle race conditions gracefully, providing immediate feedback to users.
    - Designed a scalable database schema to track venue, event, and seat states in real-time.
- **Tech Stack**: `Go (Golang)` `PostgreSQL` `Redis` `WebSockets`

#### 🔹 [AI Chatbot / GenAI Service](#)
*Backend-first conversational AI service integrating LLMs with custom functional logic.*

- **The Problem**: integrating raw LLM outputs into applications requires structured prompt engineering and state management.
- **Engineering Solution**: 
    - Developed a **context-aware backend service** that manages conversation history and session state.
    - Abstracted OpenAI API calls into a reusable service layer with error handling and retry logic.
    - Focused on **API design best practices** to deliver streaming responses to the client.
- **Tech Stack**: `Java` `Spring Boot` `OpenAI API` `Docker`

---

### 🛠 Tech Stack

| Category | **Strong In** (Production Ready) | **Familiar With** (Exposure) |
| :--- | :--- | :--- |
| **Languages** | Java, JavaScript (ES6+), SQL | Go (Golang), Python, TypeScript |
| **Backend** | Spring Boot, Node.js, Express, REST APIs | NestJS, Microservices, gRPC |
| **Databases** | PostgreSQL, MySQL, Redis | MongoDB, Cassandra |
| **DevOps & Tools** | Docker, Git/GitHub, Linux, Postman | Kubernetes, AWS (Basic), CI/CD |

---

### 🎯 What I’m Looking For

I am actively seeking **Backend Engineering Internships** or **Full-Stack roles** (Spring/Summer 2025) where I can:
- Contribute to **high-scale production systems**.
- Work with **distributed architectures** and **cloud infrastructure**.
- Tackle challenging problems in **data engineering** or **real-time systems**.

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Amanyadav207&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150" alt="stats graph" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Amanyadav207&layout=compact&theme=tokyonight&hide_border=true" height="150" alt="languages graph" />
</div>

<br>

<div align="center">
  <img src="https://github.com/Amanyadav207/Amanyadav207/blob/main/github-contribution-grid-snake.svg" width="100%" alt="snake animation" />
</div>
