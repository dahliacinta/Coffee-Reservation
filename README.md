# ☕ Coffee Catering Reservation System

## Group Information
- **Group Name:** Ruby  
- **Section:** 5  
- **Course:** INFO 3305 – Web Application Development  
- **Project Completion Date:** 11/1/2026  

### Group Members
- Hani Khairani Binti Mohd Razif (2319158)  
- Dahlia Cinta Binti Abdul Razak (2317562)  
- Dania Safiyya Binti Farid (2310056)  
- Hanis Binti Azhar (2312128)  

---

## Project Overview
The growth of small catering businesses has increased the need for an efficient reservation system. Many businesses still rely on manual bookings through phone calls or walk-ins, which often leads to lost reservations, pricing miscalculations, and double bookings.

The **Coffee Catering Reservation System** was developed for **Lands & People Cafe** to digitalize the reservation process. This web-based system allows customers to select predefined coffee catering packages based on their budget and event requirements while enabling staff to manage bookings efficiently.

---

## Project Objectives
- Digitalize the reservation process
- Provide a seamless online booking experience
- Assist staff in managing reservations efficiently
- Allow users to view, update, and cancel bookings

---

## Target Users
- **Customers:** Individuals booking coffee catering services  
- **Owners:** Cafe owners managing reservations digitally  

---

## Features and Functionalities
- Home page showcasing services offered
- Coffee catering package display with pricing
- Online reservation form
- Date picker calendar
- Booking status page
- Edit and cancel booking options
- Reservation update form
- Cancellation confirmation popup
- Responsive navigation bar
- Footer with contact details and social media links

---

## Technology Stack
- **Backend:** Laravel 10.x  
- **Frontend:** Blade Templates + Bootstrap 5  
- **Database:** MySQL 8.0  
- **Authentication:** Laravel Breeze  
- **Image Storage:** Laravel File Storage  
- **Development Environment:** XAMPP  

---

## Database Design

### Core Tables
- `users` – Customer login information  
- `booking` – Booking details  
- `membership`  
- `teams`  
- `team_invitations`  

### Entity Relationship Diagram (ERD)
[View ERD Diagram](https://drive.google.com/file/d/1M581HbGbgGo_6I07NI9Z8xIYBwOJd6Ia/view)

### Key Relationships
- One package can have many reservation details (One-to-Many)
- Reservation details can have many updates (One-to-Many)
- Reservation details may have a cancelled reservation (One-to-One, optional)

---

## Laravel Implementation

### Routes
- Public booking submission route
- Authenticated routes for viewing, editing, updating, and deleting bookings
- Dashboard and package routes

### Controllers
- **BookingController** – Handles booking CRUD operations

### Models
- User
- Booking
- Membership
- Team
- TeamInvitation

---

## User Interface
- Responsive design using Bootstrap 5
- Gray and peach color theme
- Intuitive navigation and layout
- Interactive booking components

---

## Authentication & Security
- User registration with email validation
- Secure login with session handling
- Password hashing using Laravel Breeze

---

## Installation & Setup

### Prerequisites
- PHP >= 8.1  
- Composer  
- Node.js & NPM  
- MySQL 8.0  
- XAMPP  

### Installation Steps
1. Clone or download this repository  
2. Open the project folder  
3. Configure the `.env` file  
4. Run database migrations  
5. Start the development server  

---

## Testing & Quality Assurance
- User registration and login testing
- Booking creation, update, and cancellation
- Responsive testing across devices

### Browser Compatibility
- Google Chrome  
- Mozilla Firefox  
- Safari  
- Microsoft Edge  

---

## Challenges & Solutions

### Challenge 1: Mobile Responsiveness
- **Solution:** Implemented Bootstrap responsive utilities

### Challenge 2: Complex Reservation Management
- **Solution:** Used Eloquent relationships and structured database design

---

## Future Enhancements
- Online payment integration (Stripe / PayPal)
- Live booking notifications
- Custom package builder
- Mobile application
- Analytics dashboard
- Inventory alerts

---

## Learning Outcomes

### Technical Skills
- Laravel MVC architecture
- Database design and ORM
- Authentication and authorization
- Responsive UI development
- Git & GitHub collaboration

### Soft Skills
- Team collaboration
- Project management
- Problem solving
- Technical documentation

---

## Conclusion
The Coffee Catering Reservation System demonstrates a complete Laravel-based web application that improves reservation management efficiency and enhances customer experience. The project showcases strong technical and teamwork skills applicable to real-world web development.

---

## Screenshots
### Home Page
![Home Page](screenshots/screenshot-HomePage.jpeg)

### Packages Page
![Packages Page](screenshots/screenshot-Packages.png)

### Reservation Form
![Reservation Form](screenshots/screenshot-BookingForm.jpeg)

### My Bookings Page
![My Bookings](screenshots/screenshot-Mybookings.png)


---

## References
- Figma Prototype – Coffee Catering Reservation System  
- Easy Eat. (2025). https://easyeat.ai/r/landsnpeople/2
