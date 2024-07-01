# Haarlem Festival Website

## Introduction
Welcome to the Haarlem Festival website project. This platform serves as an all-in-one solution for managing and attending the Haarlem Festival, offering features for visitors, customers, and administrators. The website is designed to provide comprehensive information about events, manage reservations and ticketing, and offer a seamless experience for both festival-goers and organizers.

## Table of Contents
- [Haarlem Festival Website](#haarlem-festival-website)
  - [Introduction](#introduction)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [User Roles and Functionalities](#user-roles-and-functionalities)
    - [Visitors](#visitors)
    - [Customers](#customers)
    - [Administrators](#administrators)
    - [Employees](#employees)
  - [General Information](#general-information)
  - [Events](#events)
    - [YUMMY Events](#yummy-events)
    - [Music Events](#music-events)
    - [Historic Events](#historic-events)
  - [Personal Program](#personal-program)
  - [Orders and Payments](#orders-and-payments)
  - [Important Information](#important-information)
  - [CMS Design](#cms-design)
  - [Conclusion](#conclusion)
    - [Benefits for the Teacher and Client](#benefits-for-the-teacher-and-client)

## Features
- User authentication and management
- Dynamic content management for event and restaurant information
- Reservation and ticket management
- Personal program creation and sharing
- Order processing with payment integration
- Administrative tools for managing users, events, and orders
- Ticket scanning functionality for employees

## User Roles and Functionalities

### Visitors
- **Login:** Access the website with username or email and password.
- **Register:** Create an account with CAPTCHA verification to prevent bots.
- **View Homepage:** Access general information and overview of available events.

### Customers
- **Password Reset:** Reset password through a link sent to the registered email.
- **Manage Account:** Edit email, name, password, and optional profile picture. Confirmation email is sent upon changes.
- **Logout:** Securely log out from the account.
- **View Event Information:** Access detailed information about events, including name, location, description, and cuisines for YUMMY events.
- **Add Reservation/Ticket to Personal Program:** Add events to personal schedule with options for reservations and ticket purchases.
- **Manage Personal Program:** Edit or delete items in personal program list or agenda view.
- **Share Personal Program:** Share or download the personal program as a read-only link or file.
- **Order Payment:** Make payments using iDEAL and other payment methods.
- **Receive Tickets and Invoice:** Receive tickets and invoices via email after successful payment.

### Administrators
- **Manage Users:** Full CRUD operations on user accounts, with search, filter, and sorting options.
- **Edit Homepage:** Update homepage content using a WYSIWYG editor.
- **Manage Custom Information Pages:** Add and edit custom pages using a WYSIWYG editor.
- **Manage Events, Venues, and Artists:** Full CRUD operations for event management, including detailed information and session management.
- **View and Export Orders:** Access order information and export data to .csv or Excel.
- **Manage Reservations:** Manage restaurant reservations with options to deactivate but not delete entries.

### Employees
- **Scan Tickets:** Use a mobile device to scan tickets and update their status. If the ticket was previously scanned, a warning will appear.

## General Information
- **Image Uploading:** All HTML/WYSIWYG editors include options to upload and manage images.
- **Dynamic Content:** All pages, such as artist and restaurant information, are rendered dynamically using database content.
- **Social Media Links:** Integrate event pages with social media for sharing.
- **Availability Checking:** Ensure ticket availability is checked before confirming orders.

## Events

### YUMMY Events
- **View Event and Restaurant Information:** Access general information and detailed restaurant data.
- **Add Reservation:** Add restaurant reservations to personal program, with options to specify allergies.
- **Manage Restaurants and Sessions:** Administrators can manage restaurant details and session schedules.

### Music Events
- **View Event Information:** Access general and individual event information, including artists, venues, and ticket prices.
- **Add Tickets and Passes:** Add tickets, all-access passes, or day passes to personal program.

### Historic Events
- **View Event Information:** Access detailed information about historic events.
- **Add Tickets to Personal Program:** Add tickets to personal program for easy management.

## Personal Program
- **Manage Program:** Edit or delete items in personal program.
- **Share Program:** Share or download the program as a read-only file.

## Orders and Payments
- **Order Payment:** Process payments using various methods in a sandbox environment.
- **Receive Tickets and Invoices:** Receive tickets and invoices via email after payment.
- **Pay Later Option:** Option to pay later if initial payment does not succeed, within 24 hours.

## Important Information
- **Security:** Basic techniques to prevent SQL injection, code injection, cross-site scripting (XSS), and registration by bots (CAPTCHA).
- **Invoice Information:** Detailed invoices including necessary client and transaction details.
- **Ticket Information:** Secure QR code-based tickets to prevent fraud.
- **Payment Status Change:** The payment API communicates if payment has succeeded or not. Only confirmed successful transactions should lead to sent invoices and tickets.
- **Availability Checking:** The maximum number of available tickets should be checked before allowing order confirmation/payment. Only 90% of the availability can be used for single tickets, as per the design project requirements.
- **CMS Design:** The design of the CMS (content management system) is up to you. We prefer a Bootstrap-based admin panel design. Ensure good usability.

## CMS Design
The CMS (Content Management System) design is flexible and can be tailored to specific needs. We recommend a Bootstrap-based admin panel design to ensure good usability and responsiveness.

## Conclusion
The Haarlem Festival website is designed to streamline the process of event management and ticketing for the Haarlem Festival. It offers a robust set of features for users, customers, administrators, and employees, ensuring a seamless and enjoyable experience for all stakeholders. This project aims to deliver a dynamic, secure, and user-friendly platform for managing one of Haarlem's most exciting cultural events.

---

### Benefits for the Teacher and Client
- **Comprehensive User Management:** Ensure secure and efficient management of user accounts.
- **Dynamic Content Management:** Easily update and manage event and restaurant information using WYSIWYG editors.
- **Detailed Event Information:** Provide festival-goers with all necessary details about events, artists, and venues.
- **Streamlined Ticketing Process:** Simplify the process of purchasing and managing tickets and reservations.
- **Personal Program Management:** Allow users to customize their festival experience by creating and sharing personal programs.
- **Robust Security Measures:** Implement security techniques to protect against common web vulnerabilities.
- **Efficient Order Processing:** Ensure smooth payment processing and order management with real-time availability checking.
- **Mobile Ticket Scanning:** Facilitate easy ticket verification for employees using mobile devices.

This README file provides an overview of the project, its features, and benefits, ensuring that both the teacher and client have a clear understanding of the project's scope and functionalities.
