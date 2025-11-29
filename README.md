# 📚 EduDash – Academic Management Platform

EduDash is a full-stack academic management platform built with **Spring Boot**, **Angular**, and **PostgreSQL**.  
It provides secure authentication using **JWT**, role-based access control, and management of:

- 👩‍🏫 Enseignants (Teachers)
- 🎓 Présidents de Jury
- 🏢 Service des Examens
- 🧭 Directrice des Études (Admin)
- 📚 Fields, Levels, Semesters, and Subjects

---

## 🚀 Tech Stack

### Backend
- Spring Boot 3
- Spring Security + JWT
- Spring Data JPA (Hibernate)
- PostgreSQL
- Lombok
- JJWT 0.12.6

### Frontend
- Angular
- Tailwind CSS
- TypeScript

---

## 🔐 Authentication & Authorization

EduDash uses **JWT Token Authentication** with the following roles:

| Role | Description |
|------|-------------|
| `ENSEIGNANT` | Teacher |
| `PRESIDENT_JURY` | Jury President |
| `SERVICE_EXAMENS` | Exam Department |
| `DIRECTEUR_ETUDES` | System Admin |

A default admin account is created on startup:

