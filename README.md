# 📇 Smart Contact Manager 

A full-featured Spring Boot web application that allows users to manage their personal or professional contacts securely and efficiently — now with image hosting on Cloudinary and modern OAuth2 login support.

---

## 🚀 Features

- 🔐 **Secure Authentication** with Spring Security + OAuth2 login
- ☁️ **Cloud Storage** for contact profile images using Cloudinary
- 📬 **Email Integration** via Spring Boot Mail
- 📚 **Relational Database Support** with Spring Data JPA and MySQL
- 📄 **Form Validation** with Spring Validation
- 📐 **Templating** using Thymeleaf
- 🛠️ **Developer Tools** like Spring DevTools for hot reload
- 💌 **User Notifications** via Email
- ✨ **Modern UI** (TailwindCSS can be optionally included)
- 🧪 **Unit & Security Testing** included

---

## 🧰 Tech Stack

| Layer            | Technology                        |
|------------------|-----------------------------------|
| Backend          | Spring Boot 3.4.4                 |
| Database         | MySQL + Spring Data JPA           |
| Frontend         | Thymeleaf + (TailwindCSS optional)|
| Image Hosting    | Cloudinary                        |
| Authentication   | Spring Security + OAuth2          |
| Email Service    | Spring Boot Mail                  |
| Build Tool       | Maven                             |
| Java Version     | Java 21 (Amazon Corretto)         |

---

## 📦 Project Structure
src/
├─ main/
│ ├─ java/com/scm/
│ ├─ resources/
│ │ ├─ templates/ # Thymeleaf templates
│ │ ├─ static/ # Static assets (CSS, JS, etc.)
│ │ ├─ application.properties 
| | └─  application-prod.properites 
└─ test/

### 📋 Prerequisites

- Java 21+
- Maven
- MySQL
- Cloudinary account (for image hosting)

### 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/bilalkhan-software-dev/Smart-contact-Manager.git
   cd Smart-contact-Manager

   Create a database (e.g. scm)

Add your DB credentials in application.properties:

http://localhost:8081/


