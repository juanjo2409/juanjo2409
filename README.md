<h1 align="center">¡Hola! Soy Juan José Maldonado Navarro 👋</h1>
<h3 align="center">Backend .NET & Full Stack Developer</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Disponible_para_Trabajar-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Focus-Backend_.NET_%7C_Clean_Architecture-blue?style=for-the-badge" alt="Focus">
  <img src="https://img.shields.io/badge/Location-Barranquilla%2C_Colombia-orange?style=for-the-badge" alt="Location">
</p>

<p align="center">
  Desarrollador de Software enfocado en construir arquitecturas robustas, API RESTful eficientes y código limpio en el ecosistema <b>.NET / C#</b>. Apasionado por la aplicación de Domain-Driven Design (DDD), principios SOLID y patrones de diseño para entregar software escalable y mantenible.
</p>

---

### 🚀 Sobre Mí

* 🎓 **Formación Académica:** Tecnólogo en Análisis y Desarrollo de Software (ADSO) en el **SENA**.
* ⚡ **Entrenamiento Intensivo:** Coder en formación en **Riwi** (Cohorte 5, Clan C#).
* 💼 **Experiencia Real:** Desarrollador Freelance y creador de plataformas con Clean Architecture y despliegues en producción.
* 🎯 **Especialización:** Backend con **.NET / C#**, **PostgreSQL**, **EF Core** y **React + TypeScript**.

---

### 🛠️ Tecnologías y Herramientas

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

## 💼 Proyectos Destacados

### 🏆 1. FrameRent — Audiovisual Equipment Rental Platform
> **Backend & Clean Architecture (.NET)** | [🔗 Ver Repositorio en GitHub](https://github.com/juanjo2409/FrameRent)

Plataforma full-stack de alquiler de equipos audiovisuales diseñada con estrictos estándares de arquitectura empresarial.

* **Arquitectura y Patrones:** Desarrollado bajo **Clean Architecture**, principios **SOLID**, entidades de dominio ricas con máquinas de estado y objetos de valor (*Value Objects*).
* **Reglas de Negocio Clave:** 
  * Verificación de disponibilidad de stock mediante consultas LINQ de solape de fechas (*date-overlap*).
  * Gestión de flujos de alquiler (`Pending` -> `Approved` -> `Delivered` -> `Returned`) con cálculo automático de tarifas por retraso (*LateFee*).
  * Restricción de solicitudes (máximo 15 días, máximo 3 alquileres activos por cliente).
* **Características Técnicas:** Contenedorizado con **Docker Compose**, autenticación con **ASP.NET Core Identity & JWT**, cliente MVC consumiendo la API mediante `HttpClient` tipado.
* **Stack Tecnológico:** `.NET`, `ASP.NET Core Web API / MVC`, `EF Core`, `PostgreSQL`, `Docker`.

---

### 📚 2. SkillHub — Workshop & Enrollment Management Platform
> **Backend & Clean Architecture (.NET 10)** | [🔗 Ver Repositorio en GitHub](https://github.com/juanjo2409/SkillHub)

Plataforma corporativa de gestión para centros de capacitación enfocada en el control riguroso de reglas de negocio e inscripciones.

* **Arquitectura y Patrones:** Implementa **Clean Architecture**, **Domain-Driven Design (DDD)** y principios **SOLID**.
* **Reglas de Negocio:** Control de aforo, prevención de inscripciones duplicadas, validación de conflictos de horario y políticas de cancelación/re-inscripción con auditoría.
* **Características Avanzadas:** 
  * Importación masiva de datos desde Excel con **EPPlus**.
  * Generación de certificados académicos en PDF mediante **QuestPDF**.
  * Documentación interactiva de la API con **Scalar**.
* **Stack Tecnológico:** `.NET 10`, `ASP.NET Core API / MVC`, `EF Core 10`, `PostgreSQL`, `Tailwind CSS`.

---

### 🧠 3. PsicoBitacoras — Plataforma de Cartillas Psicológicas
> **Full Stack** | [🔗 Visitar Sitio Web en Producción](https://www.daleunclick.online) | [🔗 Ver Repositorio en GitHub](https://github.com/juanjo2409/psicobitacoras)

Aplicación web Full-Stack diseñada con un enfoque profesional y clínico para el acompañamiento y bienestar emocional.

* **Descripción:** Permite a los usuarios acceder a cartillas terapéuticas interactivas, registrar reflexiones personales y gestionar citas psicológicas de manera asistida.
* **Impacto y Estado:** Desplegado y funcionando activamente en producción para usuarios reales.
* **Stack Tecnológico:** Frontend con `React (Vite)` y `Tailwind CSS v4` | Backend con `Node.js` y `Express.js` | Base de datos relacional en `MySQL`.

---

### 📊 Estadísticas y Actividad en GitHub

<div align="center">

  <img src="https://img.shields.io/badge/Commits_Totales-200%2B-blue?style=for-the-badge&logo=github&logoColor=white" alt="Commits" />
  <img src="https://img.shields.io/badge/Repositorios_Activos-10%2B-success?style=for-the-badge&logo=git&logoColor=white" alt="Repos" />
  <img src="https://img.shields.io/badge/Enfoque-.NET_10_%7C_Clean_Architecture-orange?style=for-the-badge&logo=codeforces&logoColor=white" alt="Focus" />

  <br><br>

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=juanjo2409&theme=radical&hide_border=true" alt="GitHub Streak" />

</div>

---

### 📫 ¿Hablamos?

<p align="center">
  <a href="https://www.linkedin.com/in/juan-jose-maldonado-navarro" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:juanjosemn160@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/juanjo2409">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>
