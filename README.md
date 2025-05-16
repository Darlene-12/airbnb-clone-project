# StayEase: Accommodation Booking Platform

![StayEase Logo](path/to/logo.png)

## 📌 Overview

StayEase is a modern accommodation booking platform inspired by Zostel and Airbnb. The application allows users to discover, browse, and book unique stays around the world with an intuitive and responsive interface.

## 🌟 Features

- **Property Discovery**: Browse accommodations with advanced filtering options
- **Detailed Listings**: View comprehensive property details with image galleries
- **User Authentication**: Secure login and registration system
- **Booking System**: Reserve accommodations with date selection
- **Responsive Design**: Seamless experience across all devices
- **User Reviews & Ratings**: Leave and read authentic reviews
- **Map Integration**: View property locations on interactive maps
- **Payment Processing**: Secure payment system for bookings
- **Host Dashboard**: For property owners to manage their listings
- **Availability Calendar**: Real-time booking availability

## 🛠️ Tech Stack

### Frontend
- **Framework**: React 18+ with Vite
- **Styling**: TailwindCSS
- **State Management**: React Context API / Redux Toolkit
- **Routing**: React Router v6
- **Form Handling**: React Hook Form
- **Data Fetching**: Axios / React Query
- **Maps**: Mapbox/Google Maps API
- **Payment**: Stripe Integration

### Development Tools
- **Version Control**: Git & GitHub
- **Package Manager**: npm / yarn
- **Linting & Formatting**: ESLint & Prettier
- **Design**: Figma

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+)
- npm or yarn

## 🏗️ Project Structure
stayease/
├── public/                     # Static files accessible by the browser
│   ├── images/                 # Static images used across the app
│   └── favicon.ico             # Website favicon
├── src/                        # Application source code
│   ├── assets/                 # Project-wide assets
│   │   ├── images/             # Component-specific images
│   │   └── icons/              # SVG or icon assets
│   ├── components/             # Reusable UI components
│   │   ├── common/             # Shared UI elements (e.g. buttons, cards)
│   │   │   ├── Button.jsx
│   │   │   ├── Input.jsx
│   │   │   ├── Card.jsx
│   │   ├── layout/             # Layout wrappers (Navbar, Footer)
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   ├── property/           # Property display components
│   │   │   ├── PropertyCard.jsx
│   │   │   ├── PropertyGrid.jsx
│   │   │   ├── PropertyDetails.jsx
│   │   ├── booking/            # Booking flow components
│   │   │   ├── BookingForm.jsx
│   │   │   ├── Calendar.jsx
│   │   ├── reviews/            # Reviews system
│   │   │   ├── ReviewCard.jsx
│   │   │   ├── ReviewForm.jsx
│   │   ├── map/                # Map integration
│   │   │   ├── MapView.jsx
│   │   │   ├── Marker.jsx
│   │   └── host/               # Host management dashboard
│   │       ├── ListingForm.jsx
│   │       ├── BookingsTable.jsx
│   ├── context/                # React context providers (state management)
│   │   ├── AuthContext.jsx
│   │   ├── BookingContext.jsx
│   ├── hooks/                  # Custom React hooks
│   │   ├── useAuth.js
│   │   ├── useProperties.js
│   ├── pages/                  # Application routes/pages
│   │   ├── Home.jsx
│   │   ├── PropertyListing.jsx
│   │   ├── PropertyDetail.jsx
│   │   ├── Checkout.jsx
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   ├── UserProfile.jsx
│   │   ├── HostDashboard.jsx
│   ├── services/               # API call functions
│   │   ├── api.js
│   │   ├── auth.js
│   │   ├── properties.js
│   │   ├── bookings.js
│   │   ├── payments.js
│   ├── utils/                  # Utility/helper functions
│   │   ├── formatters.js
│   │   ├── validators.js
│   ├── App.jsx                 # Root app component
│   └── main.jsx                # Entry point (ReactDOM render)
├── .eslintrc.js                # Linter configuration
├── .prettierrc                 # Prettier formatting rules
├── vite.config.js              # Vite dev/build config
├── tailwind.config.js          # TailwindCSS configuration
├── package.json                # Project dependencies and scripts
└── README.md                   # Project documentation (this file)



## 📝 Development Guidelines

### 🔧 Coding Standards

- Use functional components with hooks.
- Implement proper error handling and loading states
- Write sematic HTML for accessibility
- Follow TailwindCSS best practices
- Maintain a modular yet reusable component structure


### 🔁 Git Workflow

1. Create feature branches from `develop`:
   ```bash
   git checkout -b feature/feature-name
2. Make commits with clear descriptive messages
3. Submit all requests to develop
4. Squash commits when merging

## 📄 License

### MIT LICENSE
MIT License

Copyright (c) 2025 Darlene Wendie

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

### Acknowledgments
- Design inspiration from Zostel and Airbnb
- Styling framework TailwindCSS
- Form handling: React Hook Form
- Map intergration: Mapbox

  Made by: Darlene Wendie



