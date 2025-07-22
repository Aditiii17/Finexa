
---

# 💰 Full Stack AI Finance Platform 🔥

An intelligent, secure, and scalable finance platform powered by AI — built with:

**Next.js | Supabase | Tailwind CSS | Prisma | Inngest | ArcJet | Shadcn UI**

---

## 🚀 Live Demo

🌐 [Visit Live App](https://finexa-aditi-bakshis-projects.vercel.app/)

---

## 🧠 Features

* ✅ **User Authentication** with Supabase
* 📊 **AI-Powered Insights** on financial data
* 📅 **Recurring Task Scheduling** with Inngest
* 🔒 **Real-time Security & Anomaly Detection** with ArcJet
* 🎨 **Modern & Responsive UI** using Tailwind CSS + Shadcn UI
* ⚙️ **ORM & DB Management** with Prisma + Supabase Postgres
* 🧩 Fully modular architecture with scalable API routes

---

## 🛠️ Tech Stack

| Tech          | Description                        |
| ------------- | ---------------------------------- |
| **Next.js**   | App framework with SSR/ISR support |
| **Supabase**  | Backend-as-a-service (Auth + DB)   |
| **Tailwind**  | Utility-first CSS framework        |
| **Prisma**    | Type-safe ORM for PostgreSQL       |
| **Inngest**   | Background jobs & event workflows  |
| **ArcJet**    | AI-powered request protection      |
| **Shadcn UI** | Accessible UI components           |

---

## 📦 Project Structure

```
/app              → Next.js app directory
/components      → Reusable UI components (Shadcn)
/lib             → Utility & service files
/pages/api       → API routes for handling actions
/prisma          → Prisma schema and migrations
/styles          → Global Tailwind styles
```

---

## 🧑‍💻 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/ai-finance-platform.git
cd ai-finance-platform
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment

```bash
cp .env.example .env
# Fill in Supabase, Prisma, ArcJet, and Inngest credentials
```

### 4. Setup database

```bash
npx prisma generate
npx prisma db push
```

### 5. Run locally

```bash
npm run dev
```

---

## 🧩 Key Integrations

### 🔐 Supabase Auth

* Sign up, Sign in, and Magic Link
* Role-based user access

### 📉 AI Finance Tools

* NLP for expense categorization
* Predictive analytics (ML models optional)

### 🔁 Inngest Scheduler

* Monthly/weekly budget notifications
* Event-driven processing

### 🛡️ ArcJet Protection

* Rate-limiting and anomaly detection
* Built-in bot defense for endpoints

---

## 🖼️ UI Components (Shadcn + Tailwind)

* Dashboard Layout
* Charts & Tables
* Input Forms & Modals
* Toasts & Alerts

---

## 🗃️ Database Schema (Prisma)

```prisma
model User {
  id        String  @id @default(uuid())
  email     String  @unique
  expenses  Expense[]
  createdAt DateTime @default(now())
}

model Expense {
  id        String  @id @default(uuid())
  title     String
  amount    Float
  category  String
  userId    String
  user      User     @relation(fields: [userId], references: [id])
  createdAt DateTime @default(now())
}
```

---

## 🧪 Testing

* Coming soon: Playwright or Cypress for E2E tests
* Unit testing with `vitest` or `jest` supported

---

## 📈 Roadmap

* [x] Basic AI integration (classification)
* [ ] Full financial forecasting with LLMs
* [ ] Role-based dashboards (user/admin)
* [ ] Stripe integration for billing

---

## 🧑‍🎓 Screenshots

![WhatsApp Image 2025-07-22 at 12 28 25_51f08b03](https://github.com/user-attachments/assets/de0c2b90-9c0d-418a-aad4-fd2214128161)
![WhatsApp Image 2025-07-22 at 12 28 12_7dc8e958](https://github.com/user-attachments/assets/bc89f39c-d623-4d01-8924-9539b99164ba)
![WhatsApp Image 2025-07-22 at 12 27 59_c66c796d](https://github.com/user-attachments/assets/582babbe-2cd8-4a0e-8f7e-3f87afe97852)
![WhatsApp Image 2025-07-22 at 12 31 32_33abaee5](https://github.com/user-attachments/assets/2f6d77e9-ca30-4461-b95e-1f3ac53b8d39)
![WhatsApp Image 2025-07-22 at 12 30 30_6df7b65f](https://github.com/user-attachments/assets/134ab282-b0c0-4e3a-b1e2-2d5ef87f18de)
![WhatsApp Image 2025-07-22 at 12 29 00_becf05a8](https://github.com/user-attachments/assets/8a356741-d0f9-4932-b95d-89c7ecaa2f3e)


---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a PR or submit issues in the [Issues Tab](https://github.com/your-repo/issues).

---

## 📄 License

[MIT](./LICENSE)

---

## ✨ Acknowledgments

* [Shadcn UI](https://ui.shadcn.dev/)
* [Supabase](https://supabase.io/)
* [Inngest](https://www.inngest.com/)
* [ArcJet](https://arcjet.com/)
* [Prisma](https://www.prisma.io/)
* [Tailwind CSS](https://tailwindcss.com/)
* [Vercel](https://vercel.com/) (for deployment)

---

Let me know if you want this README exported to Markdown or PDF format.

