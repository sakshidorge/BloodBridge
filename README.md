# 🩸 Blood Bridge

> **Bridge the Gap, Save a Life** — India's trusted community blood donor network.

A fully functional, single-page blood donation website built for India. Connects blood donors with patients in need across 28+ cities.

---

## 🚀 Deploy to Vercel

### Option 1: One-click (Vercel Dashboard)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import your GitHub repo
4. Click **Deploy** — done!

### Option 2: Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

---

## ✨ Features

| Feature | Details |
|---|---|
| 🩸 Live Blood Availability | 8 blood groups with real-time unit counts + critical alerts |
| 📊 Charts | Bar chart (units available) + Donut chart (donor distribution) |
| 🚨 Blood Requests | Active request cards with urgency levels |
| 🗺️ Donor Map | Google Maps embed showing donors across India |
| 📝 Donor Registration | Full form with pledge message |
| 🆘 Blood Request Form | Emergency request form with instant admin notification |
| 💬 WhatsApp | Floating button + dedicated WhatsApp CTA section |
| 🔔 Admin Notifications | **Real-time** — any new request/donor instantly notifies the admin dashboard |
| 👥 Admin Dashboard | Donor table, request table, charts, donor detail modals with history |
| 💬 Donor History | Timeline of past donations per donor in admin modal |
| 💡 Quotes | Inspirational quotes from WHO, APJ Abdul Kalam, NBTC |
| ℹ️ About | Full about section with stats, facts, government registration info |

---

## 🏗️ Project Structure

```
blood-bridge/
├── index.html      ← Complete website (single file)
├── vercel.json     ← Vercel deployment config
└── README.md       ← This file
```

---

## 🔧 Tech Stack

- **Pure HTML5 + CSS3 + Vanilla JS** — No frameworks, no build step
- **Chart.js** (CDN) — Blood availability graphs
- **Google Maps Embed** — Donor location map
- **Google Fonts** — Playfair Display + DM Sans

---

## 📱 Sections

1. **Hero** — Animated landing with live blood group stats
2. **Blood Availability** — 8-group grid + 2 charts
3. **How It Works** — 3-step process
4. **Quotes** — Inspirational blood donation quotes
5. **Active Requests** — Real blood requests with urgency badges
6. **Pledge Wall** — Donor pledge cards
7. **Find Donor (Map)** — Google Maps + donor sidebar
8. **Register / Request Forms** — Donor registration + blood request
9. **About** — Foundation story, stats, certifications
10. **WhatsApp Section** — Direct WhatsApp contact
11. **Admin Dashboard** — Full admin panel (password: click "Admin Dashboard" button)

---

## 🔔 Admin Notification System

When a user submits a **blood request** or **registers as a donor**, the Admin Dashboard is instantly notified:
- Red notification badge appears on the "🔔 Notifications" tab
- Notification count updates in the Overview stats
- Full details (patient name, blood group, hospital, urgency) shown in a dismissible notification card

---

## 🇮🇳 Indian Data Included

- **15 dummy donors** across: Mumbai, Delhi, Bangalore, Hyderabad, Chennai, Pune, Ahmedabad, Kolkata, Lucknow, Kochi, Jaipur, Mangalore, Bhopal, Chandigarh, Guwahati
- **8 active blood requests** across major Indian hospitals (AIIMS, Kokilaben, Apollo, CMC Vellore, etc.)
- **Donation history** for key donors
- All states and blood groups covered

---

## ⚙️ Customisation

To connect to a real backend, replace the `donors[]` and `requests[]` arrays in the `<script>` section with API calls.

WhatsApp number is set to `+91 98765 43210` — replace in two places:
```html
href="https://wa.me/919876543210?text=..."
```

---

## 📄 License

Free to use for non-commercial, social good projects. Please credit Blood Bridge Foundation.
