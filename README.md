# AirBnB Clone Project

A modern web application that replicates the core functionality of AirBnB, allowing users to browse, view, and book properties.

## Project Goals

- Build a fully functional property rental platform
- Implement responsive design for optimal user experience
- Create an intuitive booking system
- Develop reusable UI components
- Deploy a scalable web application

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT
- **Deployment**: Docker, AWS/Vercel

## UI/UX Design Planning

### Design Goals

- Create an intuitive and visually appealing interface
- Ensure seamless user experience across all devices
- Implement clear navigation and booking flow
- Maintain consistency with modern design standards

### Key Features

| Page | Description | Key Components |
|------|-------------|----------------|
| **Property Listing View** | Main page displaying available properties with search and filter functionality | Search bar, property cards, filters, map integration |
| **Listing Detailed View** | Comprehensive property information with photos, amenities, and booking options | Image gallery, property details, amenities list, booking form, reviews |
| **Simple Checkout View** | Streamlined booking process with payment integration | Booking summary, guest information, payment form, confirmation |

### Importance of User-Friendly Design

A user-friendly design in a booking system is crucial because it directly impacts conversion rates and user satisfaction. Clear navigation reduces booking abandonment, intuitive forms minimize errors, and responsive design ensures accessibility across devices. Good UX design builds trust, which is essential for users making financial transactions.

### Design Properties

#### Color Styles
- **Primary**: #FF385C (Airbnb Red)
- **Secondary**: #00A699 (Teal)
- **Neutral**: #484848 (Dark Gray)
- **Background**: #FFFFFF (White)
- **Text**: #222222 (Near Black)
- **Border**: #DDDDDD (Light Gray)

#### Typography
- **Font Family**: Circular, -apple-system, BlinkMacSystemFont, Roboto, Helvetica Neue, sans-serif
- **Headings**: 
  - H1: 32px, Font Weight: 800
  - H2: 26px, Font Weight: 600
  - H3: 22px, Font Weight: 600
- **Body Text**: 16px, Font Weight: 400
- **Small Text**: 14px, Font Weight: 400

### Importance of Design Properties

Identifying design properties from mockups ensures consistency across the application, maintains brand identity, improves development efficiency by creating a design system, and facilitates collaboration between designers and developers. It also helps in creating reusable components and maintaining design standards throughout the project lifecycle.

## Project Roles and Responsibilities

| Role | Key Responsibilities | Contribution to Success |
|------|---------------------|------------------------|
| **Project Manager** | Timeline management, resource allocation, stakeholder communication, risk mitigation | Ensures project delivery on time and within scope |
| **Frontend Developers** | UI implementation, responsive design, user interactions, performance optimization | Creates the user-facing experience and interface |
| **Backend Developers** | API development, database design, server logic, security implementation | Builds the core functionality and data management |
| **Designers** | UI/UX design, prototyping, user research, design systems | Defines the user experience and visual identity |
| **QA/Testers** | Test planning, bug identification, quality assurance, user acceptance testing | Ensures product quality and reliability |
| **DevOps Engineers** | Deployment automation, infrastructure management, monitoring, scalability | Maintains system reliability and performance |
| **Product Owner** | Requirements definition, feature prioritization, stakeholder alignment | Guides product direction and feature decisions |
| **Scrum Master** | Process facilitation, team coaching, impediment removal, sprint planning | Ensures efficient team collaboration and delivery |

## UI Component Patterns

### Planned Components

| Component | Purpose | Features |
|-----------|---------|----------|
| **Navbar** | Primary navigation and user access | Logo, search bar, navigation links, user menu, responsive mobile menu |
| **Property Card** | Display property preview information | Property image, title, location, price, rating, quick booking option |
| **Footer** | Secondary navigation and company information | Links, social media, legal information, contact details |
| **Search Bar** | Property search functionality | Location input, date pickers, guest selector, search filters |
| **Filter Panel** | Property filtering options | Price range, property type, amenities, location filters |
| **Image Gallery** | Property photo display | Main image, thumbnail navigation, fullscreen view, image carousel |
| **Booking Form** | Reservation functionality | Date selection, guest count, pricing calculation, booking confirmation |
| **Review Card** | User review display | User avatar, rating, review text, date, helpful votes |