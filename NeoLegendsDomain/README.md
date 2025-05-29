# NeoLegends Domain – Setup Guide

## 1. Frontend
- Built with React + Tailwind
- Pages: Homepage, Listings, Login/Register, Dashboard, Admin Panel

## 2. Backend
- Firebase Auth + Firestore
- Stripe Test Integration (Escrow simulation)

## 3. Setup

### Firebase
- Create Firebase project
- Enable Email/Password Auth
- Create Firestore DB
- Use `firebase.json` and rules from /backend

### Stripe
- Use Stripe test keys
- Set up webhooks if needed

### Local Setup
```bash
cd frontend
npm install
cp ../.env.example .env
npm start
```

### Deployment
- Recommended: Vercel for frontend
- Firebase Hosting or Functions for backend
