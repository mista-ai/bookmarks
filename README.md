# Social Website for Bookmarklets

This project is a Django-based platform that supports comprehensive user authentication and various social features. The application is designed to provide an enhanced user experience with robust functionalities like OAuth 2.0 login, dynamic image handling, and efficient backend processes. Below is an overview of the key features and setup instructions.

## Features

- **Comprehensive User Authentication:**
  - Custom user profiles with detailed information.
  - Support for email and social login via OAuth 2.0 (Facebook, Twitter, Google).
  - Automated profile creation upon registration.

- **User Experience Enhancements:**
  - **Easy Thumbnails:** Dynamic image resizing for user-uploaded content.
  - **Application Configuration:** Efficient management of signal handlers.

- **Development and Security:**
  - HTTPS setup for a secure development environment.

- **Advanced Relationships and Interactions:**
  - Many-to-many relationships for user interactions such as following and activity streams.
  - JavaScript bookmarklet for easy image sharing.

- **AJAX-Driven Content:**
  - Infinite scroll for a seamless user experience.
  - Follow system for users to subscribe to content updates.

- **Data Management and Optimization:**
  - Optimized QuerySets to enhance database performance.
  - Django signals for maintaining data integrity.

- **Debugging and Performance:**
  - Integrated Django Debug Toolbar for efficient debugging.
  - Redis for caching, item views, and implementing a Redis-based image ranking system.
