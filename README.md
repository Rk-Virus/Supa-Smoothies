# 🥤 Supa-Smoothies

A sleek and simple smoothie tracker built with **React** and **Supabase** for real-time CRUD operations.

🌐 [Live Demo](https://rk-virus.github.io/Supa-Smoothies/)

---

## ✨ Features

- 🔐 Supabase-backed database (PostgreSQL)
- ➕ Add your favorite smoothies
- 🗑️ Delete a smoothie in one click

---

## 🚀 Getting Started

To run this project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/rk-virus/Supa-Smoothies.git
cd Supa-Smoothies
```

### 2. Install Dependencies

Make sure you have **Node.js** installed.

```bash
npm install
```

### 3. Set Up Supabase

- Go to [supabase.io](https://supabase.io/)
- Create a new project and table (e.g., `smoothies`)
- Copy the Supabase URL and anon/public API key
- Create a `.env` file in the root directory and add:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_KEY=your_anon_key
```

> If you're using `vite`, the `VITE_` prefix is necessary.

### 4. Start the App

```bash
npm run dev
```

> The app will run at `http://localhost:5173` by default (Vite server).

---

## 🛠️ Build for Production

To build the app for deployment:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```


---

## 🧾 License

MIT — feel free to fork, modify, and contribute!

---

## 🙌 Credits

Made with 💖 using [React](https://reactjs.org/) and [Supabase](https://supabase.io/)
