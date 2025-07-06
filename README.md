# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# 🚀 Belajar React

Repository untuk belajar dasar-dasar React dari nol!

## 🔧 Cara Mulai
1. Clone repository ini:
   ```bash
   git clone https://github.com/rendayy/belajar-react.git

# 2. Install dependencies
npm install

# 3. Jalankan development server
npm run dev  # Untuk project Vite

📂 Struktur Project
belajar-react/
├── node_modules/     # Dependencies
├── public/           # Assets static (logo, favicon)
├── src/
│   ├── assets/       # Gambar/font
│   ├── components/   # Komponen reusable
│   ├── App.jsx       # Komponen utama
│   └── main.jsx      # Entry point
├── .gitignore        # File yang diabaikan Git
├── package.json      # Dependencies & scripts
└── vite.config.js    # Konfigurasi Vite

🔧 Script Penting
Perintah	Kegunaan
npm run dev	Jalankan development server
npm run build	Build untuk production
npm run preview	Preview build production lokal
npm test	Jalankan test