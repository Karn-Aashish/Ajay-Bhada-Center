# Ajay Bhada Center

A modern web application built with **React**, **Vite**, **Tailwind CSS**, and **Supabase** as the backend-as-a-service (BaaS).  
This project is designed to serve as a complete frontend interface for the **Ajay Bhada Center**, integrating with Supabase for authentication, data management, and real-time updates.

---

## 🧩 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend Framework | React 18 (with Vite) |
| Backend / Database | Supabase |
| Styling | Tailwind CSS, Tailwind Animate |
| UI Components | Radix UI, Lucide Icons |
| State Management | React Query, React Hook Form |
| Validation | Zod |
| Charts | Recharts |
| Deployment | Vercel / Netlify |

---

## ⚙️ Project Structure

```
AjayBhadaCenter/
├── src/              # React source code
├── public/           # Static assets
├── package.json      # Project dependencies and scripts
├── vite.config.js    # Vite configuration
├── .env.example      # Example environment configuration
└── README.md
```

---

## 🔐 Environment Variables

Copy `.env.example` to `.env` and fill in your Supabase credentials.

```
VITE_SUPABASE_URL=your-project-url
VITE_SUPABASE_PROJECT_ID=your-project-id
VITE_SUPABASE_PUBLISHABLE_KEY=your-public-anon-key
```

> **Note:** These are public keys used for frontend access only. Do **not** include any service role keys in this file.

---

## 🧠 Scripts

You can run the following commands in your terminal:

| Command | Description |
|----------|-------------|
| `npm install` | Install all dependencies |
| `npm run dev` | Start the development server |
| `npm run build` | Build the project for production |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint for code quality checks |

---

## 🚀 Local Development

1. Clone this repository  
   ```bash
   git clone https://github.com/Karn-Aashish/AjayBhadaCenter.git
   cd AjayBhadaCenter
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Create your `.env` file  
   ```bash
   cp .env.example .env
   ```

4. Start the development server  
   ```bash
   npm run dev
   ```

Your app will be available at **http://localhost:8080** by default.

---

## 🧱 Deployment

### **Deploying to Vercel**

1. Push your project to GitHub.  
2. Go to [Vercel Dashboard](https://vercel.com).  
3. Import your GitHub repository.  
4. Add environment variables under **Settings → Environment Variables**:  
   - `VITE_SUPABASE_URL`
   - `VITE_SUPABASE_PROJECT_ID`
   - `VITE_SUPABASE_PUBLISHABLE_KEY`
5. Click **Deploy**.

Vercel will automatically build and host your React + Vite app securely.

---

## 🧹 Security and Best Practices

- Do **not** commit your `.env` file. It contains sensitive data.  
- Only public Supabase keys should be used in frontend code.  
- Always use `process.env` (or `import.meta.env` for Vite) to access environment variables.  
- Keep your dependencies updated using `npm audit` or `npm update`.

---

## 🤝 Contribution

If you wish to contribute:

1. Fork this repository  
2. Create a new branch (`feature/new-feature`)  
3. Commit your changes  
4. Push and submit a Pull Request  

---

## 🧾 License

This project is distributed under the **MIT License**.

---

**Developed by Aashish Karn 🐰**  
