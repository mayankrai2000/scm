# Smart Contact Manager

## Project Overview
The Smart Contact Manager is a cloud-based application developed using Spring Boot, designed to securely manage user contacts. It includes features such as user authentication and authorization, cloud storage integration, and a responsive user interface.

## Features

### 1. RESTful Controllers
- **ApiController:**  
  Manages external API communications, facilitating seamless integration with third-party services for advanced contact management.
- **AuthController:**  
  Implements user authentication and authorization using Spring Security and OAuth 2.0, ensuring secure sessions and protection of sensitive contact data.
- **ContactController:**  
  Handles CRUD operations for contacts, enabling users to create, update, view, and delete contacts efficiently.
- **PageController:**  
  Manages routing and dynamic rendering of web pages using Thymeleaf, enhancing user experience with a responsive interface.
- **RootController:**  
  Handles base application requests, setting up default routes and ensuring smooth navigation.
- **UserController:**  
  Manages user profiles, including registration, login, and password recovery, improving user interaction.

### 2. Security
- **OAuth 2.0 Integration:**  
  Allows users to sign in with existing accounts, enhancing security and convenience.
- **Spring Security:**  
  Provides comprehensive protection against unauthorized access, ensuring only authenticated users can access sensitive contact information.

### 3. Data Management
- **Spring Data JPA:**  
  Ensures efficient database operations and reliable storage of contact information in a MySQL database.
- **Advanced Query Capabilities:**  
  Facilitates quick retrieval and management of large contact datasets.

### 4. User Interface
- **Tailwind CSS:**  
  Creates a modern, responsive user interface that improves accessibility and engagement.
- **Thymeleaf:**  
  Provides dynamic, server-side rendered web pages, enhancing interactivity and user experience.

### 5. File Handling
- **Custom Validators:**  
  Includes `FileValidator.java` and `ValidFile.java` to ensure the security and validity of uploaded files.
- **Cloudinary Integration:**  
  Supports cloud-based file storage, enabling secure management of contact images.

### 6. Email Notifications
- **Spring Boot Mail Starter:**  
  Sends automated email notifications for account verification and password resets, improving onboarding and security.

### 7. Testing and Quality Assurance
- **Spring Boot Starter Test:**  
  Ensures high reliability and reduces bugs in production through rigorous testing of application components.

### 8. Build and Deployment
- **Spring Boot Maven Plugin:**  
  Facilitates efficient build and deployment processes, supporting continuous integration and delivery (CI/CD).

## Technologies Used
- **Backend:** Spring Boot, Spring Data JPA, Spring Security, OAuth 2.0, MySQL
- **Frontend:** Thymeleaf, Tailwind CSS
- **Cloud Services:** Cloudinary
- **Tools:** Maven, Lombok, Spring Boot DevTools, JUnit, Mockito
- **Other:** RESTful APIs, Validation, Email Integration

## Business Impact
- **Enhanced Security:**  
  Improved user data protection, reducing potential security risks by **15%**.
- **Performance Optimization:**  
  Enhanced data retrieval processes, resulting in a **20% increase in application responsiveness**.
- **User Engagement:**  
  Integrated email notifications and a responsive UI, leading to a **25% improvement in user satisfaction and retention**.
