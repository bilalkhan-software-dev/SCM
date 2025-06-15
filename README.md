



# 📇 Smart Contact Manager

A full-featured **Spring Boot web application** that allows users to manage their personal or professional contacts securely and efficiently — now with **image hosting on Cloudinary** and **OAuth2 login support**.



## 🚀 Features

* 🔐 **Secure Authentication** with Spring Security + OAuth2 login
* ☁️ **Cloud Storage** for contact profile images using Cloudinary
* 📬 **Email Integration** via Spring Boot Mail
* 📬 **Forgot password and user verification by email** via Spring Boot Mail
* 📚 **Relational Database Support** with Spring Data JPA and MySQL
* 📄 **Form Validation** using Spring Validation
* 📐 **Server-Side Templating** using Thymeleaf
* 🛠️ **Live Reload** support using Spring DevTools
* 💌 **Search contact with pagination
* ✨ **Modern UI** (TailwindCSS optional)
* 🧪 **Unit & Security Testing** included



## 🧰 Tech Stack

| Layer          | Technology                         |
| -------------- | ---------------------------------- |
| Backend        | Spring Boot 3.4.4                  |
| Database       | MySQL + Spring Data JPA            |
| Frontend       | Thymeleaf + (TailwindCSS optional) |
| Image Hosting  | Cloudinary                         |
| Authentication | Spring Security + OAuth2           |
| Email Service  | Spring Boot Mail                   |
| Build Tool     | Maven                              |
| Java Version   | Java 21 (Amazon Corretto)          |



## 📦 Project Structure

src/
├── main/
│   ├── java/com/scm/               # Java source code
│   └── resources/
│       ├── templates/              # Thymeleaf templates
│       ├── static/                 # Static assets (CSS, JS)
│       ├── application.properties  # Default configuration
│       └── application-prod.properties  # Production config
└── test/                           # Unit and integration tests




## 📋 Prerequisites

* ✅ Java 21+
* ✅ Maven
* ✅ MySQL
* ✅ Cloudinary account



## 🔧 Setup Instructions

1. Clone the repository

   ```bash
   git clone https://github.com/bilalkhan-software-dev/Smart-contact-Manager.git
   cd Smart-contact-Manager
   ```

2. Create a MySQL Database

   * Create a database (e.g., `scm`)
   * Update your `application.properties` file with DB credentials:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/scm
   spring.datasource.username=your_mysql_username
   spring.datasource.password=your_mysql_password
   ```

3. Configure Cloudinary Credentials

   ```properties
   cloudinary.cloud-name=your_cloud_name
   cloudinary.api-key=your_api_key
   cloudinary.api-secret=your_api_secret
   ```
   Same as for Google OAuth and Mail with different id and secret 

4. Run the Application

   ```bash
   mvn spring-boot:run
   ```

5. Visit the Application

   
   http://localhost:8081/
   



## 📄 License

This project is open-source and available under the [Apache License](LICENSE).


## 🙌 Acknowledgements

* [Spring Boot](https://spring.io/projects/spring-boot)
* [Cloudinary](https://cloudinary.com/)
* [Thymeleaf](https://www.thymeleaf.org/)
* [TailwindCSS](https://tailwindcss.com/)


