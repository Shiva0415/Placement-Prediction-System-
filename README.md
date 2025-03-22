# Placement Prediction System (Spring Boot + MySQL)  

## Tech Stack  
- Java (Spring Boot)  
- MySQL (Database)  
- Spring Security (Authentication)  
- Hibernate (ORM)  
- REST APIs  

## Overview  
A Placement Prediction System that helps students estimate their chances of getting placed based on academic performance, skills, and other factors.

## Features  
✅ Student Registration & Authentication (JWT-based)  
✅ Data Collection (Academic records, skills, internships)  
✅ Prediction Model Integration (ML model API call)  
✅ Placement Probability Calculation  
✅ Admin Dashboard for Data Management  
✅ RESTful APIs for easy integration  

## Setup Instructions  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/placement-prediction.git
   ```
2. **Navigate to the project directory**  
   ```bash
   cd placement-prediction
   ```
3. **Configure Database (MySQL)**  
   - Create a database named `placement_db` in MySQL.
   - Update `application.properties` with your MySQL credentials.

4. **Build & Run the Application**  
   ```bash
   mvn spring-boot:run
   ```

5. **Access API Endpoints**  
   - Swagger UI: `http://localhost:8080/swagger-ui.html`
   - Login API: `POST /auth/login`
   - Prediction API: `POST /predict`

##
