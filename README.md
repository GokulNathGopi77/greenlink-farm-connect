🌱 Greenlink Farm Connect
Greenlink Farm Connect is a modern web application designed to connect farmers, buyers, and service providers in the agriculture sector.
It enables farmers to list products, buyers to place orders, and admins to manage the platform efficiently.

📌 Project Info
GitHub Repo: https://github.com/GokulNathGopi77/greenlink-farm-connect

🛠️ Technologies Used
Frontend:

React + TypeScript

Vite

shadcn-ui

Tailwind CSS

Backend:

Supabase

PostgreSQL (managed by Supabase)

Supabase Auth (Email/Password)

Supabase Edge Functions (Serverless)

Supabase real-time capabilities (optional)

💻 Installation & Setup
Follow these steps to run the project locally:

1️⃣ Clone the repository
git clone https://github.com/GokulNathGopi77/greenlink-farm-connect.git

2️⃣ Move into the project folder
cd greenlink-farm-connect

3️⃣ Install dependencies
npm install

4️⃣ Start the development server
npm run dev

The app will be available at http://localhost:5173.

📂 Backend Architecture
Profiles Function:

Get user profiles

Update profile information

Delete profiles (admin only)

Products Function:

Get all products or single product by ID

Add, update, and delete products (farmer role)

Orders Function:

Create new orders

Update order and payment status

Fetch user orders with items

Analytics Function:

Dashboard metrics (products, orders, users, revenue)

Sales analytics with date filters

Product performance tracking

🔐 Security & Authentication
JWT Verification for all API calls

CORS Support for web access

Role-based access (Farmer, Buyer, Admin)

🚀 Deployment
This project can be deployed on:

Vercel

Netlify

Supabase Hosting (Edge Functions & DB)


✅ This project was fully developed and maintained by me for my final year project.

