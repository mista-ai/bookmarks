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

## Usage

- **User Authentication:** Sign up with email or use social login via Facebook, Twitter, or Google.
- **Profile Management:** Update your profile with custom information and images.
- **Bookmarklet:** Drag the provided bookmarklet to your bookmarks bar to share images directly from other websites.
- **Follow System:** Follow other users to stay updated with their activities.
- **Infinite Scroll:** Enjoy a seamless browsing experience with AJAX-driven infinite scrolling.
- **Activity Streams:** View a stream of activities from users you follow.
- **Redis Integration:** Experience improved performance with Redis caching and a Redis-based image ranking system.

## Optimization and Debugging

- **Django Debug Toolbar:** Utilize the integrated toolbar for debugging during development.
- **Optimized QuerySets:** The application is designed to efficiently handle database queries.
- **Django Signals:** Ensure data integrity with custom signal handlers.

## Technologies Used

- **Django:** A high-level Python web framework.
- **Redis:** Used for caching, real-time statistics, and image ranking.
- **OAuth 2.0:** For secure social authentication.
- **JavaScript:** Enables the bookmarklet functionality and AJAX-driven features.
- **Easy Thumbnails:** For efficient image handling and resizing.
- **HTML/CSS:** For frontend development.
