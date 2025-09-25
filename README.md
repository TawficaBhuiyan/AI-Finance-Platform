<h1 align="center">📊 AI Finance Platform</h1>
<p align="center">
  <b>A smart personal finance web application with AI-powered receipt scanning</b>  
</p>

---

## ✨ Features  

| Feature | Description |
|---------|-------------|
| 🔐 **Authentication** | Secure user sign-up/login with Clerk |
| 💰 **Account Management** | Create and manage Cash, Bank, or Card accounts |
| 🧾 **Transactions** | Log income/expenses with category, account, amount, and date |
| 📷 **Receipt Scanning** | Upload receipts and auto-extract fields with Google Gemini |
| 📊 **Budget Tracking** | Define budgets per category and track usage |
| 📈 **Analytics Dashboard** | View income, expenses, and insights |
| 🔄 **Recurring Transactions** | Automate repeated income/expenses |
| 📧 **Email Notifications** | Alerts and updates via Resend |
| 🛡 **Bot Protection** | Secure APIs with Arcjet |

---

## 🏗️ Tech Stack  

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Clerk-5B0BB5?style=for-the-badge&logo=clerk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Resend-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  <img src="https://img.shields.io/badge/Arcjet-000000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Inngest-00BFA6?style=for-the-badge"/>
</p>

---

## 📂 Project Structure  

```bash
ai-finance-platform/
│── app/                # Next.js app router pages & components
│   ├── (main)/         # Main authenticated routes
│   ├── api/            # API endpoints (transactions, accounts, etc.)
│   ├── components/     # UI components (forms, charts, scanner, etc.)
│   └── lib/            # Utilities (schemas, helpers)
│── prisma/             # Prisma schema and migrations
│── public/             # Static assets
│── .env                # Environment variables
│── package.json        # Project dependencies
│── README.md           # Project documentation
```

---

## ⚙️ Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/ai-finance-platform.git
cd ai-finance-platform
```

### 2️⃣ Install Dependencies  
```bash
npm install
```

### 3️⃣ Configure Environment Variables  
Create a `.env` file:  
```env
DATABASE_URL=postgresql://postgres:password@localhost:5432/finance_db
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
CLERK_SECRET_KEY=your_secret_key
GEMINI_API_KEY=your_gemini_key
RESEND_API_KEY=your_resend_key
ARCJET_KEY=your_arcjet_key
```

### 4️⃣ Setup Database  
```bash
npx prisma migrate dev
```

### 5️⃣ Run Development Server  
```bash
npm run dev
```
App will be live at 👉 **http://localhost:3000**

---

## 📊 Usage  

1. **Sign up** with Clerk authentication  
2. **Create accounts** (Cash, Bank, Card) with balances  
3. **Log transactions** – income/expense with categories  
4. **Upload receipts** – AI extracts fields automatically  
5. **Define budgets** and track spending  
6. **View dashboard** with insights and reports  
7. **Get notifications** by email  

---

## 🔮 Future Work  

- 📱 Mobile application (Android/iOS)  
- 🌍 Multi-currency support  
- 🏦 Banking API integration  
- 🤖 Predictive AI insights & saving goals  
- 👨‍👩‍👧 Shared budgets for families  

---

## 📝 License  

This project is licensed under the **MIT License**.  

<p align="center">✨ Built with ❤️ using Next.js, Prisma, PostgreSQL, and AI ✨</p>
