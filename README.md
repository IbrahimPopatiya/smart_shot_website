# 📸 SmartShot Website

The official marketing / landing page for **SmartShot** — a smart screenshot capturing tool. This site showcases SmartShot's features, demo, use cases, and how it works to potential users.

## ✨ What It Does

This is a sleek, modern marketing website that:

- 🏠 Introduces SmartShot with a compelling hero section
- 🎥 Embeds a demo video showing the product in action
- ⚙️ Highlights key **features** of the SmartShot tool
- 🧭 Explains **how it works** step-by-step
- 💡 Showcases real-world **use cases**
- 🔗 Connects to **Supabase** for backend/data needs (e.g., waitlist signups, analytics)

## 🛠️ Tech Stack

- ⚡ **Vite** — lightning-fast build tool and dev server
- ⚛️ **React 18** — UI library
- 🔷 **TypeScript** — type-safe JavaScript
- 🎨 **Tailwind CSS** — utility-first styling
- 🗄️ **Supabase** — backend-as-a-service (database/auth)
- 🧹 **ESLint** — linting and code quality
- 🚀 **gh-pages** — deployment to GitHub Pages

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

## 🚀 Getting Started

### 1. Install dependencies

```bash
cd smartshot-website
npm install
```

### 2. Configure environment variables

Create a `.env` file inside `smartshot-website/` with your Supabase credentials:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

> ⚠️ Never commit your `.env` file — it's already excluded via `.gitignore`.

### 3. Run the development server

```bash
npm run dev
```

The site will be available at `http://localhost:5173` (default Vite port).

## 🏗️ Build

To create a production build:

```bash
npm run build
```

This outputs the optimized static site to the `dist/` folder.

To preview the production build locally:

```bash
npm run preview
```

## 🌐 Deploy to GitHub Pages

This project uses `gh-pages` for one-command deployment:

```bash
npm run deploy
```

This will build the project and push the `dist/` folder to the `gh-pages` branch, publishing it to:

```
https://ibrahimpopatiya.github.io/smartshot-website
```

## 🧹 Linting & Type Checking

```bash
npm run lint       # Run ESLint
npm run typecheck   # Run TypeScript type checking
```

## 📄 License

This project is private and maintained for the SmartShot product.
