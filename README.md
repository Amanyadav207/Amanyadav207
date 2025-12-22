<div align="center">
  <h1>Aman Yadav</h1>
  <h3>Building backend systems with strong data consistency, secure authentication, and scalable APIs.</h3>

  <p>
    <a href="https://www.linkedin.com/in/amanyadav207">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
    </a>
    <a href="mailto:amanyadav130904@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
    <a href="https://drive.google.com/file/d/19H_gZDGwQ4q9adZqHycr1x39hKmxLjYF/view">
      <img src="https://img.shields.io/badge/Resume-View_PDF-000000?style=for-the-badge&logo=pdf&logoColor=white" alt="Resume"/>
    </a>
  </p>
</div>

---

## 👨‍💻 About Me

I am a **Software Engineer** focused on **backend engineering, system design, and data reliability**. I aim to go beyond “making things work” by designing systems that emphasize **correctness, maintainability, and performance** under real-world constraints.

My engineering approach emphasizes **careful schema design, secure authentication, idempotent data pipelines, and efficient API contracts**. Whether it’s building a schema-aware ETL pipeline or solving cross-domain authentication issues in production deployments, I enjoy working on problems that require a deep understanding of backend systems.

---

## 🚀 Featured Projects

### 🔹 SheetGuard (Schema-Aware ETL & Data Validation Tool)
*A robust ETL pipeline designed to safely migrate data from Google Sheets into relational databases.*

- **Problem**: Spreadsheet-based data entry often leads to schema violations, duplicates, and partial database failures.
- **Engineering Solution**:
  - Built a **schema-aware, multi-stage validation pipeline** to catch missing fields, type mismatches, and constraint violations before insertion.
  - Designed an **idempotent ingestion process** to allow safe re-runs without duplicating data.
  - Implemented a **dead-letter queue (DLQ)** to isolate invalid records while keeping the main pipeline operational.
  - Added **audit logs and ETL run tracking** for observability and debugging.
- **Tech Stack**: `Python` `PostgreSQL (NeonDB)` `Google Sheets API` `Google App Script` `Pandas`
- **Key Takeaway**: Ensures partial failures never corrupt downstream database state.

---

### 🔹 CraveStream (Short-Video Food Discovery Platform)
*A backend-driven social content platform inspired by TikTok-style vertical video feeds.*

- **Problem**: Food discovery platforms lack engaging short-form content and often struggle with media delivery and secure access control.
- **Engineering Solution**:
  - Built a **vertical short-video feed** optimized for content discovery and user engagement.
  - Implemented **secure authentication** using JWT with HttpOnly cookies to reduce XSS attack surface.
  - Solved **CORS and cross-domain cookie issues** in a distributed deployment (Vercel frontend, Render backend).
  - Designed **role-based access control (RBAC)** to separate user discovery flows from partner content management.
  - Integrated **ImageKit** for optimized video storage, transformations, and low-latency streaming.
- **Tech Stack**: `React.js` `Node.js` `Express` `MongoDB` `JWT` `ImageKit` `TailwindCSS`
- **Key Takeaway**: Demonstrates real-world backend problem-solving around authentication, media pipelines, and deployment constraints.

---

### 🔹 Conflux (Real-Time Collaborative Code Editor)
*A real-time collaborative code editor built for low-latency multi-user editing.*

- **Problem**: Real-time collaboration requires conflict-free state synchronization across multiple clients.
- **Engineering Solution**:
  - Implemented **CRDT-based synchronization (Yjs)** to ensure conflict-free concurrent edits.
  - Built a **WebSocket-based backend** to manage live collaboration sessions.
  - Integrated **Monaco Editor** for a VS Code–like in-browser editing experience.
- **Tech Stack**: `Node.js` `WebSocket` `React` `Yjs` `Monaco Editor`
- **Key Takeaway**: Highlights understanding of real-time systems and distributed state consistency.

---

## 🛠 Tech Stack

| Category | Strong In (Production) | Familiar With |
|------|------------------------|---------------|
| **Languages** | Java, JavaScript (ES6+), SQL, Go | Python, TypeScript |
| **Backend** | Spring Boot, Node.js, Express, REST APIs | Microservices, gRPC |
| **Databases** | PostgreSQL, MySQL, Redis | MongoDB |
| **DevOps & Tools** | Docker, Git/GitHub, Linux, Postman | Kubernetes, CI/CD |

---

## 🎯 What I’m Looking For

I am actively seeking **Backend Engineering Internships** or **FullStack** where I can:
- Work on **production-scale backend systems**
- Solve problems involving **data consistency, APIs, and system reliability**
- Learn from engineers building **high-performance distributed systems**

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Amanyadav207&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Amanyadav207&layout=compact&theme=tokyonight&hide_border=true" height="150"/>
</div>
