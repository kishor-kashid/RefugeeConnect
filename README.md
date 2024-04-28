# RefugeeConnect


## Project Description

RefugeeConnect is a comprehensive platform aimed at bridging the gap between refugees and essential services, fostering community support, and empowering refugees to integrate successfully into their new environments. This platform provides a range of services accessible via web applications, catering to the needs of refugees, service providers, donors, and the wider community.

## Tech Stack

### Backend
- Node.js
- Express.js
- Mongoose.js
- MongoDB
- PWA (Progressive Web App)
- Redux for state management
- Internationalization support

### Frontend
- React.js
- MapBox for mapping services
- Google API integration
- DialogBox via Google Cloud
- Kommunicate AI for intelligent communication

### Other
- JWT (JSON Web Tokens) for authentication and authorization
- Stripe API for payment processing

## Roles and Permissions

RefugeeConnect caters to three primary roles with distinct access levels:

- Admin
  - Full access to all CRUD operations.
  - Ability to add resources, camps, and stories.
  - Manage users and their roles.
  
- Refugee
  - View resources and camps.
  - Add personal stories.
  
- User
  - Add resources.
  - Make donations.

## Getting Started

To get started with RefugeeConnect:

1. Clone the repository.
2. Install all necessary packages:
   - For the backend, run `npm install` in the `backend` directory.
   - For the frontend, run `npm install` in the `frontend` directory.
3. Start the backend server:
   - Navigate to the backend directory and run `node server.js`.
4. Start the frontend application:
   - In a new terminal, navigate to the frontend directory and run `npm run dev`.
