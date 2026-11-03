<h1 align="center">Hello, I'm Juan José Maldonado Navarro 👋</h1>
<h3 align="center">Backend .NET & Full Stack Developer</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Open_to_Work-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Focus-Backend_.NET_%7C_Clean_Architecture-blue?style=for-the-badge" alt="Focus">
  <a href="https://cert.efset.org/en/BWqZZk" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/EF_SET_Certified-B2_Upper_Intermediate-purple?style=for-the-badge&logo=english" alt="EF SET B2 Certificate">
  </a>
  <img src="https://img.shields.io/badge/Location-Barranquilla%2C_Colombia-orange?style=for-the-badge" alt="Location">
</p>

<p align="center">
  Software Developer focused on building robust architectures, efficient RESTful APIs, and clean code in the <b>.NET / C#</b> ecosystem. Passionate about applying Domain-Driven Design (DDD), SOLID principles, and design patterns to deliver scalable and maintainable software. Certified <b>B2 Upper Intermediate</b> in English (EF SET) with professional reading proficiency (C2).
</p>

---

### 🚀 About Me

* 🎓 **Academic Background:** Technologist in Software Analysis and Development (ADSO) at **SENA**.
* ⚡ **Intensive Tech Training:** Coder in training at **Riwi** (Cohort 5, C# Clan).
* 📜 **English Proficiency:** Certified **B2 Upper Intermediate** by [EF SET Certificate](https://cert.efset.org/en/BWqZZk) (Score: 57/100).
  * 📖 **Reading:** C2 Proficient (75/100) — *Advanced technical documentation comprehension.*
  * 🎧 **Listening:** B2 Upper Intermediate (55/100)
  * ✍️ **Writing:** B2 Upper Intermediate (51/100)
  * 🗣️ **Speaking:** B1 Intermediate (46/100) — *Actively practicing daily at Riwi and through self-study.*
* 💼 **Real Experience:** Freelance Developer and creator of platforms featuring Clean Architecture and production deployments.
* 🎯 **Specialization:** Backend with **.NET / C#**, **PostgreSQL**, **EF Core**, and **React + TypeScript**.

---

### 🛠️ Tech Stack & Tools

<div align="center">

  <!-- Core & Backend -->
  <img src="https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/ASP.NET_Core_API-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core Web API" />
  <img src="https://img.shields.io/badge/Node.js-%2343853D.svg?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="Express.js" />

  <br>

  <!-- Frontend -->
  <img src="https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/React-%2320232A.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />

  <br>

  <!-- Databases & ORM -->
  <img src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/EF_Core-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white" alt="EF Core" />
  <img src="https://img.shields.io/badge/MySQL-%23000f0f.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/SQL_Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />

  <br>

  <!-- DevOps & Tools -->
  <img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Linux_Ubuntu-%23E95420.svg?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu" />
  <img src="https://img.shields.io/badge/Postman-%23FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code" />

</div>

---

## 💼 Featured Projects

### 🏆 1. FrameRent — Audiovisual Equipment Rental Platform
> **Backend & Clean Architecture (.NET)** | <a href="https://github.com/juanjo2409/FrameRent" target="_blank" rel="noopener noreferrer">🔗 View Repository on GitHub</a>

Full-stack audiovisual equipment rental platform built under strict enterprise software architecture standards.

* **Architecture & Patterns:** Developed using **Clean Architecture**, **SOLID** principles, rich domain entities with state machines, and **Value Objects**.
* **Key Business Rules:** 
  * Stock availability verification via LINQ date-overlap queries.
  * Rental lifecycle management (`Pending` -> `Approved` -> `Delivered` -> `Returned`) with automated late fee calculation (`LateFee`).
  * Request constraints (maximum 15 days, max 3 active rentals per customer).
* **Technical Highlights:** Containerized with **Docker Compose**, authenticated via **ASP.NET Core Identity & JWT**, and featuring an MVC client consuming the API through a typed `HttpClient`.
* **Tech Stack:** `.NET`, `ASP.NET Core Web API / MVC`, `EF Core`, `PostgreSQL`, `Docker`.

---

### 📚 2. SkillHub — Workshop & Enrollment Management Platform
> **Backend & Clean Architecture (.NET 10)** | <a href="https://github.com/juanjo2409/SkillHub" target="_blank" rel="noopener noreferrer">🔗 View Repository on GitHub</a>

Enterprise training center management platform focused on rigorous business rule enforcement and enrollment control.

* **Architecture & Patterns:** Implements **Clean Architecture**, **Domain-Driven Design (DDD)**, and **SOLID** principles.
* **Business Rules:** Capacity control, prevention of duplicate enrollments, automatic schedule conflict validation, and audit-logged cancellation/re-enrollment policies.
* **Advanced Features:** 
  * Bulk data import from Excel using **EPPlus**.
  * Automated generation of academic PDF certificates via **QuestPDF**.
  * Interactive API documentation with **Scalar**.
* **Tech Stack:** `.NET 10`, `ASP.NET Core API / MVC`, `EF Core 10`, `PostgreSQL`, `Tailwind CSS`.

---

### 🧠 3. PsicoBitacoras — Psychological Workbooks Platform
> **Full Stack** | <a href="https://www.daleunclick.online" target="_blank" rel="noopener noreferrer">🔗 Visit Live Website</a> | <a href="https://github.com/juanjo2409/psicobitacoras" target="_blank" rel="noopener noreferrer">🔗 View Repository on GitHub</a>

Full-stack web application designed with a professional and clinical approach for emotional well-being and support.

* **Description:** Enables users to access interactive therapeutic workbooks, record personal reflections, and schedule psychological appointments seamlessly.
* **Impact & Status:** Deployed and actively running in production for real users.
* **Tech Stack:** Frontend with `React (Vite)` and `Tailwind CSS v4` | Backend with `Node.js` and `Express.js` | Relational database in `MySQL`.

---

### 📊 GitHub Statistics & Activity

<div align="center">

  <img src="https://img.shields.io/badge/Total_Commits-200%2B-blue?style=for-the-badge&logo=github&logoColor=white" alt="Commits" />
  <img src="https://img.shields.io/badge/Active_Repos-10%2B-success?style=for-the-badge&logo=git&logoColor=white" alt="Repos" />
  <img src="https://img.shields.io/badge/Focus-.NET_10_%7C_Clean_Architecture-orange?style=for-the-badge&logo=codeforces&logoColor=white" alt="Focus" />

  <br><br>

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=juanjo2409&theme=radical&hide_border=true" alt="GitHub Streak" />

</div>

---

### 📫 Let's Connect?

<p align="center">
  <a href="https://www.linkedin.com/in/juan-jose-maldonado-navarro" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:juanjosemn160@gmail.com" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/juanjo2409" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>
