# Zen Finance 🧘🏽‍♂️💰

**Zen Finance** is an umbrella repository for a modern fintech application. It brings together both the backend (`zen-api`) and frontend (`zen-ui`) into a single project structure for easier collaboration and deployment.

---

## 🧩 Submodules

This repository contains the following components as Git submodules:

- [`zen-api`](https://github.com/jason-ezenwa/zen-api) — The backend API for Zen Finance.
- [`zen-ui`](https://github.com/yourusername/zen-ui) — The frontend user interface for Zen Finance.

Each submodule is maintained independently, and you can work with them directly inside this umbrella repository.

---

## 🔧 Features

- Authentication
- Multi-currency Wallets
- Currency Exchange
- Virtual Cards

---

## 📦 Getting Started

### 1. Clone this umbrella repository with submodules:

```bash
git clone --recurse-submodules https://github.com/yourusername/zen-finance.git
```

If you've already cloned without --recurse-submodules, run:
git submodule update --init --recursive

### 2. Navigate into the submodules
cd zen-api      # For backend

cd zen-ui       # For frontend

To update a submodule (that has been changed in its independent repo), cd into it, then run ```git pull origin main```, cd out of it and then commit (and push) the changes to this umbrella repo.
