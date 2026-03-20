# ArticlesCMS

I developed a custom Content Management System (CMS) from the ground up, specifically designed for managing website articles through standard CRUD operations. The entire backend is powered by PHP 8, with a strong emphasis on security throughout the application.

The system is built on a PostgreSQL database, chosen for its robustness and advanced security features. Security is a primary focus, implemented through comprehensive server-side validations in PHP to prevent SQL injection and XSS attacks. All sensitive data, including user passwords, is protected using strong hashing algorithms like Argon2, and data transmission is secured with HTTPS encryption.

On the frontend (UI interfaces), I used semantic HTML5 for structured content, combined with a custom CSS framework built on CSS Grid and media queries for a fully responsive design. Pure JavaScript is used for client-side interactions, including form validation to enhance user experience and reduce server load, but all critical security checks are enforced server-side. The architecture follows a clean separation of concerns, with PHP handling all business logic, data processing, and security measures, while the frontend focuses on presentation and user interaction. This custom CMS provides a secure, high-performance solution for article management with full control over the codebase.
