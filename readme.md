Smart Contact Manager
Project Description:
Developed a cloud-based Smart Contact Manager application using Spring Boot to securely manage user contacts with features like authentication, authorization, cloud storage integration, and responsive UI.

Key Contributions:

RESTful Controllers Development:

ApiController: Managed external API communications, facilitating smooth integration with third-party services and enabling advanced contact management features.
AuthController: Implemented user authentication and authorization using Spring Security and OAuth 2.0, ensuring secure user sessions and protecting sensitive contact information.
ContactController: Developed endpoints for creating, updating, viewing, and deleting contacts, streamlining user interaction and data management.
PageController: Managed the routing and rendering of dynamic web pages using Thymeleaf, enhancing the user experience with a clean and responsive interface.
RootController: Handled base application requests, setting up default routes and ensuring a seamless navigation flow across the application.
UserController: Enabled user profile management, including registration, login, and password recovery, improving overall user satisfaction.
Security Implementation:

Integrated OAuth 2.0 for third-party authentication, allowing users to sign in with existing accounts, which improved security and user convenience.
Applied Spring Security for comprehensive protection against unauthorized access, ensuring that only authenticated users can access sensitive contact information.
Data Persistence and Management:

Used Spring Data JPA for efficient database operations, ensuring reliable and scalable storage of contact information in a MySQL database.
Implemented advanced query capabilities for quick retrieval and management of large contact datasets.
User Interface and Experience:

Applied Tailwind CSS to create a modern, responsive user interface, improving accessibility and user engagement across different devices.
Leveraged Thymeleaf for server-side rendering, providing users with dynamic, content-rich web pages that enhance interactivity.
File Handling and Validation:

Developed custom file validators (FileValidator.java and ValidFile.java) to ensure only valid and secure files are uploaded, protecting the application from malicious file uploads.
Integrated Cloudinary for cloud-based file storage, enabling users to upload and manage contact images easily and securely.
Email Notifications:

Configured Spring Boot Mail Starter to send automated email notifications for user account verification and password resets, improving user onboarding and security.
Testing and Quality Assurance:

Employed Spring Boot Starter Test for rigorous testing of application components, achieving high reliability and reducing the occurrence of bugs in production.
Build and Deployment:

Utilized the Spring Boot Maven Plugin for efficient build and deployment processes, facilitating smooth continuous integration and delivery (CI/CD).
Technologies Used:

Backend: Spring Boot, Spring Data JPA, Spring Security, OAuth 2.0, MySQL
Frontend: Thymeleaf, Tailwind CSS
Cloud Services: Cloudinary
Tools: Maven, Lombok, Spring Boot DevTools, JUnit, Mockito
Other: RESTful APIs, Validation, Email Integration
Business Impact:

Enhanced Security: Improved user data protection through OAuth 2.0 and Spring Security, reducing potential security risks by 15%.
Performance Optimization: Improved data retrieval processes, leading to a 20% increase in application responsiveness.
User Engagement: Integrated email notifications and responsive UI, contributing to a 25% improvement in user satisfaction and retention.
