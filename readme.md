Sure! Here's the simplified version of your **`README.md`** in proper Markdown format:

```markdown
<p align="center">
  <img src="./client/public/main_logo.png" alt="CineXpress Logo" width="300"/>
</p>

# 🎬 CineXpress – Movie Ticket Booking (MERN)

A modern movie ticket booking app built with the **MERN** stack, featuring role-based access, secure payments, real-time seat booking, and rich movie data.

---

## 🚀 Features

### 👤 Users
- Browse movies (posters, trailers, cast)
- Choose showtimes & select seats (interactive seat map)
- Secure checkout with **Stripe**
- Receive e-ticket confirmations via **email**

### 🔧 Admin
- Fetch & manage movies via **TMDB API**
- Schedule shows with date, time, and pricing
- Monitor bookings and users through the admin panel

---

## 🛠 Tech Stack

| Purpose         | Technology / Service           |
|-----------------|-------------------------------|
| Frontend        | React, Tailwind CSS            |
| Backend         | Node.js, Express               |
| Database        | MongoDB Atlas                  |
| Authentication  | Clerk                          |
| Payments        | Stripe                         |
| Email Service   | Brevo (Sendinblue)             |
| Background Jobs | Inngest                        |
| Movie Data      | TMDB API                       |

---

## 📂 Project Structure

```

client/          → React frontend (pages, components, assets)
server/          → Node backend (API, controllers, models)
.env             → Environment variables

````

---

## ▶️ Live Demo

🔗 [CineXpress on Vercel](https://cinexpress-three.vercel.app/)

---

## ⚙️ Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/rishabhhhhhhhhhhh/Movie-Ticket-Booking-System.git
   cd Movie-Ticket-Booking-System
````

2. **Install dependencies**

   ```bash
   npm install
   cd client && npm install
   ```

3. **Configure environment variables**

   Copy `.env.example` to `.env` in both `server/` and `client/`, then update with your API keys:

   **Server `.env`**

   ```env
   MONGODB_URI=
   CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   INNGEST_EVENT_KEY=
   INNGEST_SIGNING_KEY=
   TMDB_API_KEY=
   STRIPE_PUBLISHABLE_KEY=
   STRIPE_SECRET_KEY=
   STRIPE_WEBHOOK_KEY=
   SENDER_EMAIL=
   SMTP_USER=
   SMTP_PASS=
   ```

   **Client `.env`**

   ```env
   VITE_CURRENCY='$'
   VITE_CLERK_PUBLISHABLE_KEY=
   VITE_BASE_URL=
   VITE_TMDB_IMAGE_BASE_URL=https://image.tmdb.org/t/p/original
   ```

4. **Run the app**

   ```bash
   # Start backend
   npm run dev

   # In a separate terminal, start frontend
   cd client && npm start
   ```

---

## 🔐 Admin Panel

Visit `/admin` route to:

* Manage movies (fetched via TMDB)
* Schedule shows (time, pricing)
* View and manage bookings

---

Enjoy the show! 🍿
Built with ❤️ using MERN Stack.

```

Let me know if you want to include badges, contribution guidelines, or deployment instructions.
```
