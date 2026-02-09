
# HeritageHub – Digital Platform for Culture & Heritage

HeritageHub is a full-stack web platform that connects travelers, local guides, vloggers, and vendors to promote culture and heritage digitally.  
The platform enables local vendors to sell crafts, guides to assist travelers, and vloggers to share content—all within a single ecosystem.

---

## 🚀 Features

- Multi-role system: Travelers, Guides, Vloggers, and Local Vendors  
- E-commerce system for selling local crafts  
- Real-time chat using WebSocket  
- Role-based authentication and authorization  
- High-performance content delivery using Redis caching  
- SEO-optimized frontend with server-side rendering  
- Scalable backend architecture  

---

## 🛠️ Tech Stack

### Frontend
- Next.js  
- TypeScript  
- Tailwind CSS  

### Backend
- Node.js  
- Express.js  
- Prisma ORM  
- MySQL  
- Redis  
- WebSocket  

### DevOps & Tooling
- Turborepo (Monorepo)  
- GitHub Actions  
- ESLint  
- Prettier  

---

## 📂 Monorepo Structure

apps/
web/        → Next.js frontend

packages/
ui/         → Shared UI components
config/     → Shared TypeScript & ESLint configurations


## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kushkumar569/heritagehub-digital-platform.git
cd heritagehub-digital-platform
````

### 2. Install dependencies

```bash
npm install
```

### 3. Setup environment variables

Create a `.env` file inside `apps/web` and add:

```
JWT_SECRET

EMAIL_USER
EMAIL_PASS
BASE_URL
PORT
GOOGLE_API_KEY
```

### 4. Run the project

```bash
npm run dev
```

---

## 🧠 Key Implementations

* Prisma ORM for database schema management and migrations
* Redis caching for faster response times and improved scalability
* WebSocket-based real-time communication
* Server-side rendering with Next.js for SEO optimization
* Clean and scalable monorepo architecture using Turborepo

---

## 📌 Future Enhancements

* Payment gateway integration
* Map-based discovery for guides and heritage locations
* Review and rating system
* Progressive Web App (PWA) support

---

## 👤 Author

**Kush Kumar**

* GitHub: [https://github.com/kushkumar569](https://github.com/kushkumar569)
* LinkedIn: [https://www.linkedin.com/in/kush-kumar-876525257/](https://www.linkedin.com/in/kush-kumar-876525257/)

