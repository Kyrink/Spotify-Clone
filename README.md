# Spotify Clone

## Intro
This Spotify clone aims to replicate the core features of the popular music streaming service using  Next.js 13.4, React, Tailwind CSS, Supabase, PostgreSQL, and Stripe, focusing on providing users with an engaging and dynamic experience of exploring, playing, and managing their favorite music. The project incorporates a dynamic user interface, secure authentication, database management, and premium subscriptions.

## Tech Stack
- **Frontend:** `Next.js 13.4`, `React`, `Tailwind CSS`
- **Backend:** `Supabase`, `PostgreSQL`
- **Payment Processing:** `Stripe`
- **Authentication:** `Supabase Authentication`, `GitHub OAuth`
- **Storage:** `Supabase Storage` for files and images

## Features
- **Dynamic UI:** Using Next.js and React, with Tailwind CSS for styling and animations.
- **Responsive Design:** Full responsiveness across all devices with Tailwind.
- **Authentication:** Secure user registration and login with Supabase, including GitHub OAuth.
- **Database Management:** Utilize Supabase and PostgreSQL for database schemas and operations.
- **Payment Processing:** Stripe integration for handling premium subscriptions, including recurring payments and subscription management.
- **Music Streaming:** Features for song upload, playback, favorites system, and playlists.
- **Advanced Components:** Including an advanced player component for music playback.
- **Form Validation:** Client-side form validation using react-hook-form.
- **Error Handling:** Server error handling with react-toast.
- **Direct Database Access:** Fetch data in server React components directly from the database without an API.

## Process
The project kicks off with setting up Next.js for the frontend and Tailwind CSS for custom styling. The backend leverages Supabase for authentication, database management, and storage, with PostgreSQL as the underlying database. The integration of Stripe adds premium subscription functionalities. This tutorial covers everything from initial setup to deploying a fully functional music streaming service.

## Learnings
- Developing with Next.js and React for a dynamic SPA.
- Styling with Tailwind CSS for rapid UI development.
- Backend management with Supabase and PostgreSQL.
- Secure authentication methods and payment processing with Stripe.
- Direct database access in Next.js without traditional API calls.

## Improvement
Future enhancements could include expanding the music catalog, implementing a recommendation algorithm, and integrating social features for shared playlists and music discovery.

## Running the Project
1. Clone the repo and install dependencies with `npm install`.
2. Configure environment variables for Supabase and Stripe.
3. Run the development server with `npm run dev` and navigate to `http://localhost:3000`.

## Video or Image

