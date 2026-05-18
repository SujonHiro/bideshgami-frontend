# Bideshgami Frontend

A modern React-based web application for the Bideshgami platform — built with Vite, Tailwind CSS v4, and a rich component ecosystem.

---

## 🚀 Tech Stack

| Category | Technology |
|---|---|
| Framework | React 19 |
| Build Tool | Vite 7 |
| Styling | Tailwind CSS v4 |
| State Management | Redux Toolkit + React Redux |
| Routing | React Router v7 |
| Form Handling | React Hook Form + Redux |
| HTTP Client | Axios |
| UI Components | Radix UI + shadcn/ui |
| Notifications | Sonner |
| Icons | Lucide React |
| Auth | JWT Decode + js-cookie |

---

## 📦 Prerequisites

- **Node.js** v18+
- **npm** v9+

---

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-org/bideshgami-frontend.git
cd bideshgami-frontend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env` file in the root directory:

```env
VITE_API_BASE_URL=https://your-backend-url.vercel.app/api/v1
```

### 4. Start the development server

```bash
npm run dev
```

The app will be available at `http://localhost:5173`

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint |

---

## 📁 Project Structure

```
bideshgami-frontend/
├── public/                 # Static assets
├── src/
│   ├── assets/             # Images, fonts, etc.
│   ├── components/         # Reusable UI components
│   ├── pages/              # Page-level components
│   ├── redux/           # Redux slices & API logic
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utility functions
│   ├── routes/             # React Router configuration
│   └── main.jsx            # App entry point
├── .env                    # Environment variables (not committed)
├── vite.config.js
└── package.json
```

---

## 🧩 Key Dependencies

### UI & Components
- **Radix UI** — Accessible, unstyled component primitives (accordion, dialog, dropdown, tabs, etc.)
- **shadcn/ui** — Pre-built component patterns on top of Radix UI
- **Lucide React** — Icon library
- **Embla Carousel** — Lightweight carousel/slider
- **Vaul** — Drawer component
- **cmdk** — Command palette (⌘K)
- **next-themes** — Dark/light mode support

### Forms & Validation
- **React Hook Form** — Performant form state management
- **Zod** — Schema validation
- **@hookform/resolvers** — Bridge between RHF and Zod

### Date Handling
- **date-fns** — Date utility library
- **react-day-picker** — Calendar/date picker component

### State & Data
- **Redux Toolkit** — Simplified Redux state management
- **Axios** — HTTP requests

---

## 🌐 Deployment

This project is deployed on **Vercel**.

To deploy manually:

```bash
npm run build
# Then upload the `dist/` folder to your hosting provider
```

For Vercel, connect the GitHub repository and set the environment variables in the Vercel dashboard under **Settings → Environment Variables**.

---

## 🔧 Development Notes

- Tailwind CSS v4 is used via the `@tailwindcss/vite` plugin — no `tailwind.config.js` required.
- `tw-animate-css` provides additional animation utilities.
- `baseline-browser-mapping` is included as a dev dependency for browser compatibility checks. Keep it updated:

```bash
npm i baseline-browser-mapping@latest -D
```

---

## 📄 License

Private — All rights reserved.
