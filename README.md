# Town Centre Pharmacy Website

A full-stack website for Town Centre Pharmacy, featuring a product catalog, online consultation booking, health tips, and an admin dashboard.

## Features

- Home page with featured products and services
- About Us page with pharmacy information
- Products page with filtering and search
- Online consultation booking
- Health tips and blog
- Contact form
- User authentication (login/register)
- Admin dashboard for managing products, orders, appointments, and more

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

## Installation

1. Clone the repository:
   \`\`\`
   git clone https://github.com/your-username/town-centre-pharmacy.git
   cd town-centre-pharmacy
   \`\`\`

2. Install dependencies:
   \`\`\`
   npm install
   cd backend
   npm install
   \`\`\`

3. Create a `.env` file in the backend directory with the following variables:
   \`\`\`
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   JWT_EXPIRE=30d
   JWT_COOKIE_EXPIRE=30
   
   SMTP_HOST=your_smtp_host
   SMTP_PORT=your_smtp_port
   SMTP_EMAIL=your_smtp_email
   SMTP_PASSWORD=your_smtp_password
   FROM_NAME=Town Centre Pharmacy
   FROM_EMAIL=noreply@towncentrepharmacy.com
   
   MAX_FILE_UPLOAD=1000000
   FILE_UPLOAD_PATH=./uploads
   \`\`\`

4. Seed the database:
   \`\`\`
   cd backend
   npm run seed
   \`\`\`

## Running the Application

1. Start the backend server:
   \`\`\`
   cd backend
   npm run dev
   \`\`\`

2. Open the frontend in your browser:
   \`\`\`
   http://localhost:5000
   \`\`\`

## Admin Access

- Email: admin@towncentrepharmacy.com
- Password: 123456

## User Access

- Email: john@example.com
- Password: 123456

## License

This project is licensed under the MIT License.
