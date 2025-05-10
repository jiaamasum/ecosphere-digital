# 🌱 EcoSphere Digital Marketplace

A full-stack digital marketplace for eco-friendly products and resources, built with **Next.js 14**, **Stripe Connect**, **Kinde Auth**, **Prisma**, and **Supabase**.

---

## 🚀 Features

- **Modern Blog**: Latest articles and eco-tips
- **FAQ**: Common questions answered
- **Templates**: Downloadable sustainability templates, filterable by category
- **Privacy Policy & Terms**: Standard legal pages
- **Newsletter**: Stay updated with eco news
- **Role-based Dashboards**: For buyers and sellers
- **Secure Auth**: Kinde Auth integration
- **Payments**: Stripe Connect for seamless checkout

---

## 🛠️ Tech Stack

| Frontend   | Backend   | Auth      | Payments      | DB      |
|------------|-----------|-----------|---------------|---------|
| Next.js 14 | Next.js   | Kinde     | Stripe Connect| Prisma  |
| Tailwind   | Supabase  |           |               |         |

---

## 📂 Folder Structure

```plaintext
/app
  /blog
  /faq
  /templates
  /privacy
  /terms
/components
  Footer.tsx
```

---

## 📝 Setup

```bash
git clone https://github.com/jiaamasum/ecosphere-digital.git
cd ecosphere-digital
npm install
# Add your .env.local with Supabase, Stripe, Kinde, and DB keys
npm run dev
```

---

## ⚙️ Environment Variables

Create a `.env.local` file in your project root with the following variables:

```env
# Supabase
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

# Stripe
STRIPE_SECRET_KEY=your_stripe_secret
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret

# Kinde Auth
KINDE_ISSUER_URL=your_kinde_issuer_url
KINDE_CLIENT_ID=your_kinde_client_id
KINDE_CLIENT_SECRET=your_kinde_client_secret

# Prisma/Postgres
DATABASE_URL=your_postgres_url
DIRECT_URL=your_postgres_direct_url
```

Set these same variables in your Vercel project dashboard for production deployments.

---

## 🚀 Deploying to Vercel

1. Push your code to GitHub ([repo link](https://github.com/jiaamasum/ecosphere-digital)).
2. Connect your repo to [Vercel](https://vercel.com/).
3. Set all environment variables in the Vercel dashboard.
4. Deploy!
5. (Optional) Run Prisma migrations manually if needed:
   ```bash
   npx prisma generate
   npx prisma migrate deploy
   ```

---

## 📸 Screenshots

<!-- Add screenshots or GIFs here -->

---

## 🤝 Contributing

Pull requests welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📄 License

[MIT](LICENSE)

---

> **EcoSphere** is a full-stack digital marketplace built with Next.js 14, Stripe Connect, Kinde Auth, Prisma, and Supabase, allowing users to seamlessly buy and sell digital products. It features secure authentication, product listings, cart functionality, Stripe-powered checkout, and role-based dashboards for buyers and sellers.
