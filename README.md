# 💳 Abonnement Hebdomadaire avec Stripe + Flask

Ce projet permet de mettre en place un système d’abonnement automatique (90€/semaine) via Stripe, déployable sur Render.

---

## 🔧 Fonctionnalités

- 🔒 Paiement sécurisé avec Stripe Checkout
- 💰 Abonnement hebdomadaire (90€)
- 🚀 Déployable sur Render ou tout autre hébergeur
- 💻 Interface simple et responsive

---

## 📦 Installation

```bash
git clone https://github.com/tonpseudo/abonnement-stripe.git
cd abonnement-stripe
cp .env.example .env
# ➜ ajoute ta STRIPE_SECRET_KEY dans le fichier .env
pip install -r requirements.txt
python app.py
