# 🎶 Spotify Clone Music Player

A modern, fully responsive Spotify clone music player built with React, Supabase, Stripe, and Tailwind CSS.


🌟 Features

User Authentication: Secure signup and login with Supabase.
Product Management: Users can view available products and pricing plans.
Subscription Payments: Stripe integration for subscription and payment handling.
Responsive Design: Tailwind CSS for a seamless UI on all devices.
Dynamic Music Playback: Play, pause, and navigate tracks with a smooth user experience.
Customizable Playlists: Create and manage playlists based on user preference.


📁 Modules

User Details
Handles user authentication, profile management, and user-specific data.

Product
Displays available music products and playlists, organized for easy browsing.

Price
Manages pricing tiers and options, including dynamic updates to accommodate new pricing models.

Subscription
Integrates Stripe to manage premium subscriptions, payment processing, and subscription renewals.


🚀 Tech Stack

Frontend: React, Tailwind CSS
Backend: Supabase (PostgreSQL & Auth)
Payment Integration: Stripe


🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spotify-clone.git
   cd spotify-clone
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   Set up `.env` with your Supabase and Stripe keys:
   ```plaintext
   REACT_APP_SUPABASE_URL=your_supabase_url
   REACT_APP_SUPABASE_ANON_KEY=your_supabase_anon_key
   REACT_APP_STRIPE_KEY=your_stripe_key

4. Run the application:
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.
