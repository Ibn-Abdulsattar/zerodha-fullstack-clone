<div align="center">

<img src="https://img.shields.io/badge/MERN-Stack-20232A?style=for-the-badge&logo=mongodb&logoColor=4EA94B" />
<img src="https://img.shields.io/badge/Status-Live%20Project-brightgreen?style=for-the-badge" />
<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" />

<br/><br/>

```
███████╗███████╗██████╗  ██████╗ ██████╗ ██╗  ██╗ █████╗
╚══███╔╝██╔════╝██╔══██╗██╔═══██╗██╔══██╗██║  ██║██╔══██╗
  ███╔╝ █████╗  ██████╔╝██║   ██║██║  ██║███████║███████║
 ███╔╝  ██╔══╝  ██╔══██╗██║   ██║██║  ██║██╔══██║██╔══██║
███████╗███████╗██║  ██║╚██████╔╝██████╔╝██║  ██║██║  ██║
╚══════╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝
```

### **Full-Stack Stock Trading Platform Clone**
*A production-grade MERN application replicating India's largest discount brokerage*

<br/>

[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=flat-square&logo=nodedotjs)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?style=flat-square&logo=mongodb)](https://mongodb.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

##  Overview

**Zerodha Fullstack Clone** is a comprehensive, end-to-end simulation of [Zerodha](https://zerodha.com) — India's largest and most trusted stockbroking platform. This project showcases a complete MERN stack implementation with three tightly integrated sub-applications: a public-facing marketing frontend, an interactive trading dashboard, and a RESTful backend API.

Built as a portfolio-grade project, it demonstrates real-world full-stack architecture, component-driven UI development, database modeling, and REST API design — all in a single monorepo.

---

##  Features

###  Marketing Frontend
- Responsive landing page replicating Zerodha's homepage
- Product showcase pages (Kite, Console, Coin, Varsity)
- Pricing & brokerage calculator section
- About, support, and open account pages
- Smooth navigation with React Router

###  Trading Dashboard
- Portfolio overview with holdings and positions
- Watchlist with real-time-style stock tracking
- Buy / Sell order modal with form handling
- Funds summary and order history
- Interactive charts for data visualization
- Sidebar navigation mimicking Kite's UI

###  Backend API
- RESTful API with Node.js & Express
- MongoDB database with Mongoose ODM
- API endpoints for holdings, positions, and orders
- Modular route and model architecture
- Environment-based configuration with `.env`

---

##  Project Structure

```
zerodha-fullstack-clone/
│
├──  backend/                  # Node.js + Express REST API
│   ├── model/                   # Mongoose data models
│   ├── controllers/                   # Functionality
│   ├── routes/                   # All Apis
│   ├── schema/                  # Database schemas
│   ├── index.js                 # Server entry point
│   └── package.json
│
├──  dashboard/                # React trading dashboard (Kite-style)
│   ├── src/
│   │   └── components/          # Dashboard UI components
│   ├── public/
│   └── package.json
│
├──   frontend/                 # React marketing/landing site
│   ├── src/
│   │   └── landing_page/        # Page components
│   ├── public/
│   │   └── media/               # Images and brand assets
│   └── package.json
│
└── README.md
```

---

##  Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React.js, React Router, CSS3, Bootstrap |
| **Dashboard** | React.js, Axios, Chart.js, Material UI |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Dev Tools** | dotenv, nodemon, npm |

---

##  Getting Started

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or above)
- [MongoDB](https://www.mongodb.com/) (local or Atlas URI)
- npm

---

### 1️ Clone the Repository

```bash
git clone https://github.com/Ibn-Abdulsattar/Zerodha.git
cd Zerodha
```

---

### 2️ Start the Backend

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:

```env
DATABASE_URL=mongodb://localhost:27017/zerodha
PORT=3002
```

```bash
npm start
```

> API will be running at `http://localhost:3002`

---

### 3️ Start the Dashboard

```bash
cd ../dashboard
npm install
npm start
```

> Dashboard will be running at `http://localhost:3000`

---

### 4️ Start the Frontend

```bash
cd ../frontend
npm install
npm start
```

> Frontend will be running at `http://localhost:3001`

---

##  Screenshots

| Page | Preview |
|---|---|
|  Landing Page | *Home, hero section, product showcase* |
|  Dashboard | *Watchlist, holdings, order placement* |
|  Portfolio | *Positions, funds, P&L summary* |



---

##  API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/allHoldings` | Fetch all stock holdings |
| `GET` | `/allPositions` | Fetch current positions |
| `POST` | `/newOrder` | Place a new buy/sell order |

---

##  What I Learned

- Structuring a **monorepo** with multiple React apps and a shared backend
- Designing and connecting **MongoDB schemas** for financial data
- Building **RESTful APIs** with Express and consuming them via Axios
- Replicating a **real-world production UI** with attention to UX detail
- Managing **state and routing** across a multi-page React application

---

##  Contributing

Contributions are welcome! Here's how to get started:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature description"

# 4. Push to the branch
git push origin feature/your-feature-name

# 5. Open a Pull Request
```

Please follow conventional commit messages and keep PRs focused and well-described.

---

##  License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

##  Disclaimer

This project is built **purely for educational and portfolio purposes**. It is not affiliated with, endorsed by, or connected to [Zerodha](https://zerodha.com) in any way. All brand names, logos, and trademarks belong to their respective owners.

---

<div align="center">

Made  by **[Ibn-Abdulsattar](https://github.com/Ibn-Abdulsattar)**

⭐ *If you found this project helpful, consider giving it a star!*

</div>
