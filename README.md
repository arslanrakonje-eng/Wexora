# BlockWorld 2020 Revival

BlockWorld 2020 is a full-stack Roblox Revival website and 3D online multiplayer building game inspired by the classic 2020 era.

## Features
- **Modern Express & Socket.io Backend**: Real-time multiplayer synchronization and block building.
- **3D Sandbox Gameplay**: Built with Three.js featuring block mining, placement, and character movement.
- **Supabase Integration**: User authentication, profiles, database tables, and catalog systems.
- **Responsive Web UI**: Home games page, catalog, login/register portals, and custom user sessions.

## Installation & Setup

1. **Clone or Extract Project**:
   Extract `BlockWorld2020-Revival.zip` into your project directory.

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**:
   Copy `.env.example` to `.env` and fill in your Supabase credentials:
   ```env
   PORT=3000
   SUPABASE_URL=https://your-supabase-project.supabase.co
   SUPABASE_ANON_KEY=your-supabase-anon-key
   ```

4. **Run the Database Schema**:
   Execute the SQL script located in `supabase/schema.sql` inside your Supabase SQL Editor.

5. **Run the Development Server**:
   ```bash
   npm start
   ```
   Open your browser and navigate to `http://localhost:3000`.

## Publishing & Deployment
- **Backend & Web Hosting**: Deployable on Render, Railway, Fly.io, or Heroku as a Node.js web service.
- **Database**: Fully compatible with Supabase PostgreSQL.
