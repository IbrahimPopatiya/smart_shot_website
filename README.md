![SmartShot Website](https://placehold.co/1200x300/0c0a09/fafaf9?text=SmartShot+Website)

# 📸 SmartShot Website

> The official marketing / landing page for **SmartShot** — a smart screenshot capturing tool. This site showcases SmartShot's features, demo, use cases, and how it works to potential users.

---

## ✨ Features

- 🏠 Compelling **hero section** introducing SmartShot
- 🎥 Embedded **demo video** showing the product in action
- ⚙️ Dedicated **Features** section highlighting key capabilities
- 🧭 Step-by-step **How It Works** walkthrough
- 💡 Real-world **use cases** showcase
- 🔗 **Supabase** integration for backend/data needs (e.g., waitlist signups, analytics)
- 📱 Fully responsive, modern UI

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| ⚡ **Vite** | Lightning-fast build tool and dev server |
| ⚛️ **React 18** | UI library |
| 🔷 **TypeScript** | Type-safe JavaScript |
| 🎨 **Tailwind CSS** | Utility-first styling |
| 🗄️ **Supabase** | Backend-as-a-service (database/auth) |
| 🧹 **ESLint** | Linting and code quality |
| 🚀 **gh-pages** | Deployment to GitHub Pages |

---

## 🖼️ Demo / Screenshots

> 📝 *Placeholder images below — replace with real screenshots of the live site.*

![Landing Page](https://placehold.co/800x450?text=Landing+Page)

![Features Section](https://placehold.co/800x450?text=Features+Section)

![How It Works](https://placehold.co/800x450?text=How+It+Works)

---

## 📁 Project Structure

The actual project source lives inside the `smartshot-website/` subfolder:

```
smart_shot_website/
└── smartshot-website/   <- Vite/React/TS project root
    ├── src/
    │   ├── components/
    │   ├── App.tsx
    │   └── main.tsx
    ├── public/
    ├── package.json
    └── ...
```

---

## ⚙️ Configuration

Create a `.env` file inside `smartshot-website/` with your Supabase credentials:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

> ⚠️ Never commit your `.env` file — it's already excluded via `.gitignore`.

---

## 🧹 Linting & Type Checking

```bash
npm run lint        # Run ESLint
npm run typecheck   # Run TypeScript type checking
```

---

## 📄 License

This project is private and maintained for the SmartShot product.

---

## 🛠️ Setup

```bash
cd smartshot-website
npm install
```

---

## 🚀 Run

### Development server

```bash
npm run dev
```

The site will be available at `http://localhost:5173` (default Vite port).

### Production build

```bash
npm run build
```

This outputs the optimized static site to the `dist/` folder. Preview it locally with:

```bash
npm run preview
```

### 🌐 Deploy to GitHub Pages

This project uses `gh-pages` for one-command deployment:

```bash
npm run deploy
```

This will build the project and push the `dist/` folder to the `gh-pages` branch, publishing it to:

```
https://ibrahimpopatiya.github.io/smartshot-website
```
