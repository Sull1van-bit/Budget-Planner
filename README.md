# Budget Planner 💰

A free and open-source budget planning application that helps you manage your finances effectively. Built as an alternative to paid budget management tools, this application allows you to track income, expenses, and budget goals on your local machine with complete data privacy.

## ✨ Features

- 📊 **Expense Tracking** - Monitor your daily expenses and income
- 🎯 **Budget Goals** - Set and track budget limits for different categories
- 📈 **Financial Overview** - Visualize your spending patterns
- 🔒 **Privacy First** - All data stored locally on your machine
- 🆓 **Completely Free** - No subscriptions, no hidden costs

## 🛠️ Tech Stack

- **Frontend:** React + Tailwind CSS
- **Backend:** Express.js
- **Database:** MySQL
- **Package Manager:** npm

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MySQL](https://www.mysql.com/) (v8.0 or higher)
- npm (comes with Node.js)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Sull1van-bit/Budget-Planner
cd budget-planner
```

### 2. Install Dependencies

```bash
npm install
# or
npm i
```

### 3. Database Setup

Create a new MySQL database for the application:

```sql
CREATE DATABASE budget_planner;
```

### 4. Environment Configuration

Create a `.env` file in the root directory and configure the following variables:

```env
# Database Configuration
DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=budget_planner
DB_PORT=3306

# Server Configuration
PORT=5000

# JWT Secret (for authentication)
JWT_SECRET=your_secret_key_here
```

### 5. Run the Application

Start both frontend and backend servers concurrently:

```bash
npm run dev:full
```

The application will be available at:
- **Frontend:** http://localhost:5173 (or your Vite default port)
- **Backend API:** http://localhost:5000

## 📁 Project Structure

```
budget-planner/
├── client/                # React frontend
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Page components
│   │   ├── utils/        # Utility functions
│   │   └── App.tsx       # Main app component
│   └── package.json
├── server/                # Express backend
│   ├── controllers/      # Route controllers
│   ├── models/           # Database models
│   ├── routes/           # API routes
│   └── index.js          # Server entry point
├── .env                   # Environment variables (create this)
├── package.json          # Root package.json
└── README.md
```

## 🔧 Available Scripts

- `npm run dev:full` - Run both frontend and backend concurrently
- `npm run dev:client` - Run only the React frontend
- `npm run dev:server` - Run only the Express backend
- `npm run build` - Build the production version

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Your Name**
- GitHub: [@Sull1van-bit](https://github.com/Sull1van-bit)
- LinkedIn: [Rafael Romelo](www.linkedin.com/in/rafael-romelo-615657289)

## 🙏 Acknowledgments

- Built with ❤️ as a free alternative to paid budget management tools
- Special thanks to the open-source community

## 📬 Contact

Have questions or suggestions? Feel free to reach out:
- Open an issue on GitHub
- Email: rafaelromelogibran400@gmail.com

## 💖 Support This Project

If you find this project helpful and want to support its development, you can buy me a coffee!

### For Indonesian Users

Support via Saweria: [https://saweria.co/Sull1van](https://saweria.co/Sull1van)

### Crypto Donations 🪙
**USDT (BEP20):**
0x6535a5904f7f3d1d98841ef6eebcb15e9d13d2f9

Thank you for your support! 🙏

---

⭐ If you find this project helpful, please consider giving it a star!
