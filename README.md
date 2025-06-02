# 💰 MERN Finance Dashboard App with ML Predictions

A full-stack Finance Dashboard application built with the **MERN stack**, enhanced with **Machine Learning predictions**. Users can visualize financial data, track insights, and view predictions based on historical patterns using interactive charts.

## 🔧 Tech Stack

### Frontend
- **Vite** – Fast frontend build tool
- **React** – UI library
- **Redux Toolkit** – State management
- **Material UI (MUI)** – UI components
- **Recharts** – Charting and data visualization

### Backend
- **Node.js** – JavaScript runtime
- **Express.js** – Backend web framework
- **MongoDB** – NoSQL database

### Machine Learning
- Integrated in the backend for predictive analytics (e.g., future trends, classification, regression models).

---

## 📂 Project Structure

```
/client           --> Frontend (Vite + React)
/server           --> Backend (Node + Express + ML + MongoDB)
  └── index.js    --> Entry point for server
  └── app.tsx     --> (Optional mislabeling) Should likely be app.ts (TS backend config)
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/mern-finance-dashboard.git
cd mern-finance-dashboard
```

---

## 📦 Install Dependencies

### Backend
```bash
cd server
npm install
```

### Frontend
```bash
cd client
npm install
```

---

## 🧪 Run the Application

### Backend (Node/Express + ML API)
Make sure MongoDB is running locally or update the connection string in your `.env`.

#### If using `index.js` (JavaScript entry):
```bash
node index.js
```

#### If using `app.tsx` (This is unusual for backend, likely you meant `app.ts`)
> You may need TypeScript installed globally if you're using TypeScript:
```bash
npm install -g typescript ts-node
```

Then run:
```bash
ts-node app.ts
```

> ⚠️ Note: `.tsx` is generally used for React components, not backend apps. Please verify this is a backend file, and rename to `app.ts` if appropriate.

---

### Frontend (Vite + React)
```bash
cd client
npm run dev
```

---

## 🌐 Environment Variables

Create a `.env` file in the `server/` directory and add your environment variables:

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/finance-dashboard
```

---

## 📊 Features

- 📈 Financial dashboard with real-time charting
- 🔮 ML predictions for trends or forecasts
- 🔍 Detailed analytics using Recharts
- 🎨 Clean, responsive UI using Material UI
- 🔧 State managed with Redux Toolkit

---

## 🤖 ML Integration

Machine learning models are implemented in the backend and exposed via RESTful APIs to the frontend for visualization and prediction outputs.

---

## 🛠️ Scripts

### Backend

```bash
# Start server (JS)
node index.js

# Start server (TS)
ts-node app.ts
```

### Frontend

```bash
npm run dev
```

---

## 📬 Contact

Feel free to reach out for issues, PRs, or feedback!

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
