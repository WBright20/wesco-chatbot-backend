# 🤖 WESCO Chatbot Backend 2

Backend Node.js pour connecter un chatbot GPT à Facebook Messenger.

## 📦 Installation

```bash
git clone <repo_url>
cd wesco-chatbot-backend2
npm install
cp .env.example .env
```

Ajoute tes clés API dans le fichier `.env`.

## 🚀 Lancement en local

```bash
node index.js
```

## 🌍 Déploiement

Tu peux utiliser [Render](https://render.com) ou [Railway](https://railway.app). N'oublie pas de définir les variables d'environnement.

## 📬 Webhook Messenger

Configure l'URL de ton serveur et le `VERIFY_TOKEN` dans Meta for Developers > Messenger > Webhooks.
