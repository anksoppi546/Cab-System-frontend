# Cab System Frontend
This is a Next.js application for the frontend of a cab system.

## Deployed Links
- Frontend : https://cab-system-frontend-ankit.vercel.app/
- Backend : https://cab-system-backend-3jxx.onrender.com

## Booking Ride Page
Users can book a ride from here by selecting vehicles of own choice. After a successful booking, booking details are sent on their provided email-id.
![Screenshot 2024-08-12 230149](https://github.com/user-attachments/assets/c24a62b4-e64a-4fab-98ac-863033af3845)

## Cab Management Page
Pricing and Availability of cabs are managed here.
![Screenshot 2024-08-12 230227](https://github.com/user-attachments/assets/3257ac77-5699-4fba-aae9-2c343a012f72)

Users can see all booking details also.

# Features
## ✅ Car Availability
- After a booking is done that cab will not be available to other until its journey is over.
- Go to Cab Management to make any cab Available.

## ✅ Responsiveness
- Web app is mostly responsive to almost all screen sizes. (Under Development)
- Create issue on repo if found (Since testing on all screen size is not possible for me).
- Beautiful UI implemented for better user experiences.

## ✅ Booking Confirmation Email
- When a booking is confirmed, server sends an email.

## ✅ Shortest Time estimation
- A graph is designed and Dijkstra Algorithm is used to estimate the shortest path

## ✅ 5 Cab Type (Cab Management - Change Price Per Minute)
- 5 cab type are implemented, also there price per minute can be changed by the admin

## Prerequisites
Make sure you have the following installed before proceeding:
- [Node.js](https://nodejs.org/)

## Installation

1. Install dependencies

   ```bash
   npm install
   ```

## Usage

To start the development server, run:

```bash
npm run dev
```

The application will be available at `http://localhost:3000` by default.

## Project Structure

```
cab-system-frontend/
  ├── app/                 # React components
  │   ├── pages/           # Next.js pages
  ├── components/          # Reusable React components
  ├── context/             # React context providers and consumers
  ├── public/              # Static files
  ├── utils/               # Utility functions and helpers
  ├── .env.local           # Local environment variables (not committed to git)
  ├── .eslintrc.json       # ESLint configuration
  ├── .gitignore           # Specifies intentionally untracked files
  ├── jsconfig.json        # JavaScript configuration for Visual Studio Code
  ├── .next-env.d.ts       # TypeScript declarations for Next.js environment
  ├── next.config.js       # Next.js configuration
  ├── package.json         # Project metadata and dependencies
  ├── README.md            # Project README file
  ├── tailwind.config.js   # Tailwind CSS configuration
  └── yarn.lock            # Yarn lock file
```
