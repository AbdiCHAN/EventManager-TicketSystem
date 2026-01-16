# EventMaster Enterprise - Ticketing & Event Management System

**Enterprise-Grade Event Management & Ticketing System**  
A complete, scalable platform for managing events, ticket sales, attendee tracking, and analytics.  
Built with **HTML/CSS/JS frontend** and **Node.js backend APIs**, deployable on **Vercel**.

Designed for **large enterprises, internal corporate teams, and high-scale event organizers** who need a secure, professional, and fully customizable system.

---

## 💰 Enterprise Pricing & Subscription Options (2026)

### Full Enterprise License (One-Time Purchase)
- **Price:** $250,000 – $500,000 USD per company  
- **Includes:**  
  - Full source code (frontend + backend APIs)  
  - Deployment on Vercel or client-preferred cloud  
  - Custom branding & feature requests  
  - Priority enterprise support & updates  

### Subscription / SaaS Rental Option
- For companies who cannot afford full purchase:  
  - **Monthly Plan:** $5,000 – $7,500/month  
  - **Quarterly Plan:** $12,500 – $20,000/quarter  
  - **Annual Plan:** $45,000 – $70,000/year  

### Optional Add-Ons
- Dedicated on-site or remote support: $10,000/year  
- Additional modules or advanced analytics: custom pricing  

> **Rationale:** With 8 engineers building and maintaining this system, these prices ensure **team profitability** while remaining competitive in the 2026 enterprise market.

---

## 📝 Enterprise Contract / Agreement
Clients must sign a **custom enterprise license or subscription agreement** before access to source code or deployment.

The agreement covers:  
- **Ownership:**  
  - Full license purchase: client receives full commercial usage rights  
  - Subscription: client uses system under time-limited enterprise license  
- **Restrictions:** Redistribution, resale, or sharing is strictly prohibited  
- **Payment Terms:** Full payment or subscription payments as agreed  
- **Support:** Optional enterprise support terms included in contract  

**Example Clause:**  
> "The licensee (client) is granted a non-transferable, enterprise-level license to use EventMaster Enterprise for internal operations only. Redistribution, resale, or sharing of the software is strictly prohibited. Full payment or subscription fees must be honored according to the signed agreement before deployment or system access."

---

## 👥 Collaborators & Enterprise Roles

| Name | GitHub Username | Role |
|------|----------------|------|
| Phoebe | [ChrisphoebeOchieng](https://github.com/ChrisphoebeOchieng) | Software Engineer |
| Bryan | [bryan-kipla](https://github.com/bryan-kipla) | Software Engineer |
| Calton | [CaltonMomaya](https://github.com/CaltonMomaya) | Software Engineer & Assistant Project Manager |
| Abdirahman | [AbdiCHAN](https://github.com/AbdiCHAN) | Project Manager & Software Engineer |
| Abdullahi Arab | [abdullahiabdikadir35](https://github.com/abdullahiabdikadir35) | Organizer & Communication Coordinator / Software Engineer |
| Abdullahi | [abzulo](https://github.com/abzulo) | Software Engineer |
| Aucxley | [aucxley-eng](https://github.com/aucxley-eng) | Software Engineer |
| Abdulhadi | [abdulhadishueb](https://github.com/abdulhadishueb) | Software Engineer |

---

## ⚡ Enterprise Features

### User Features
- Browse events by category, date, and location  
- Secure ticket booking and payment  
- Digital tickets with QR codes  
- User profiles with event history  

### Organizer Features
- Create, edit, and manage events  
- Multiple ticket tiers (VIP, General, Early Bird)  
- Real-time ticket sales tracking via backend API  
- Export attendee lists and reports  
- Customizable event pages  

### Admin Features
- Manage users, events, and payments via backend API  
- Analytics dashboard with charts  
- Refunds, cancellations, and dispute management  

---

## 🛠️ Enterprise Tech Stack & API
- **Frontend:** HTML, CSS, JavaScript (static + dynamic pages in `public/`)  
- **Backend / API:** Node.js + Express.js RESTful API (serverless functions in `api/`)  
- **Database:** MongoDB / PostgreSQL  
- **Authentication:** JWT / OAuth 2.0  
- **Payments:** Stripe / PayPal integration  
- **Hosting / Deployment:** Vercel  

**API Endpoints include:**  
- `/api/events` – CRUD for events  
- `/api/events/[id]` – GET/PUT/DELETE a single event  
- `/api/users` – Register, login, manage users  
- `/api/users/[id]` – User profile operations  
- `/api/tickets` – Create/manage tickets  
- `/api/tickets/[id]` – Single ticket management  
- `/api/payments` – Stripe/PayPal payment processing  
- `/api/payments/webhook` – Webhooks for payment events  
- `/api/admin/*` – Analytics, reports, admin management  

**Frontend Example:**

```javascript
// Fetch all events from API
fetch('/api/events')
  .then(res => res.json())
  .then(data => console.log(data));

// Create a ticket
fetch('/api/tickets', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify({ eventId: '123', userId: '456', ticketType: 'VIP' })
})
.then(res => res.json())
.then(data => console.log(data));
🚀 Getting Started
Clone the repository:
git clone https://github.com/yourusername/EventMaster-TicketingSystem.git

Frontend

All static HTML/CSS/JS files are in public/

Open public/index.html locally or deploy to Vercel for live hosting

Backend / API

API files are in api/

Vercel automatically hosts them as serverless endpoints

Example endpoints:

GET /api/events
POST /api/tickets
POST /api/payments

📈 Enterprise Roadmap

Event analytics dashboard

Multi-language support

Mobile app integration

Advanced ticketing tiers

Payment refunds & invoicing

💳 Enterprise Sales & Payment Plan

Sales Approach:

Internal clients (company subsidiaries, departments)

Local businesses, large organizations, and event venues

Direct enterprise contracts

Payment Methods:

Bank transfer

PayPal / Stripe (international clients)

Full upfront payment for purchase or subscription payments

Delivery:

After full payment & signed contract, client receives:

Full source code (frontend + API backend)

Deployment on Vercel

Documentation & support

⭐ Contributing (Enterprise Development)

Star the repository instead of forking initially

Clone directly for local development

Once the project is finalized as a team, then fork for feature development

📄 Enterprise License

Custom Enterprise License (commercial use only)

Only paying clients receive source code and commercial rights

Internal testing & development allowed

📞 Enterprise Contact

CEO / Contact: Abdirahman Cabdi
Email: speedextra008@gmail.com

GitHub: https://github.com/AbdiCHAN

📁 Project Folder Structure (Vercel-Ready API + Public)
EventMaster-TicketingSystem/
│
├─ public/                    # Static frontend files
│   ├─ index.html
│   ├─ about.html
│   ├─ events.html
│   ├─ dashboard.html
│   ├─ contact.html
│   ├─ styles/
│   │   ├─ main.css
│   │   ├─ dashboard.css
│   │   ├─ events.css
│   │   └─ contact.css
│   ├─ js/
│   │   ├─ main.js
│   │   ├─ events.js
│   │   ├─ dashboard.js
│   │   └─ contact.js
│   └─ assets/
│       ├─ images/
│       └─ icons/
│
├─ api/                        # Serverless backend API endpoints
│   ├─ events/
│   │   ├─ index.js
│   │   └─ [id].js
│   ├─ users/
│   │   ├─ index.js
│   │   └─ [id].js
│   ├─ tickets/
│   │   ├─ index.js
│   │   └─ [id].js
│   ├─ payments/
│   │   ├─ index.js
│   │   └─ webhook.js
│   ├─ admin/
│   │   ├─ analytics.js
│   │   └─ manage.js
│   ├─ db.js
│   └─ auth.js
│
├─ .gitignore
├─ README.md
└─ ENTERPRISE_LICENSE.md
