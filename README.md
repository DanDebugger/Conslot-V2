# Conslot V2

A full-stack decentralized application built with:

* **Frontend:** React + Vite + TypeScript
* **Backend:** Rust
* **Smart Contracts:** Sui + Move

---

## 📁 Project Structure

```
Conslot-V2/
├── conslot-frontend/
├── backend/
├── smart-contract/
```

---

## ⚙️ Prerequisites

Make sure you have installed:

* Node.js (>= 18)
* npm or yarn
* Rust (`cargo`)
* Sui CLI

---

## 🚀 Getting Started

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/conslot-v2.git
cd Conslot-V2
```

---

## 🌐 Frontend Setup (React + Vite + TypeScript)

```bash
cd conslot-frontend
npm install
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---

## 🦀 Backend Setup (Rust)

```bash
cd backend
cargo build
cargo run
```

---

## ⛓️ Smart Contract Setup (Sui + Move)

### Install Sui CLI (if not installed)

```bash
cargo install --locked --git https://github.com/MystenLabs/sui.git --branch devnet sui
```

### Build Contracts

```bash
cd smart-contract
sui move build
```

### Run Tests

```bash
sui move test
```

---

## 📦 Useful Commands

### Frontend

```bash
cd conslot-frontend
npm run dev       # Start dev server
npm run build     # Production build
```

### Backend

```bash
cd backend
cargo run         # Run backend server
cargo build       # Build project
```

### Smart Contracts

```bash
cd smart-contract
sui move build
sui move test
```

---

## 🧠 Notes

* Keep `.env` files for secrets (do not commit them).
* Ensure your backend and frontend ports match for API calls.
* Configure wallet integration for Sui in the frontend.

---

## 📄 License

MIT License
