# IA-Carrossery
Developpement d'un logiciel de gestion carrosserie par IA
ia-carrossery/
│
├── backend/                ← API avec FastAPI
│   ├── main.py             ← Serveur principal
│   ├── routes/             ← Endpoints (upload, chatbot, estimation)
│   ├── models/             ← Chargement des modèles IA
│   └── requirements.txt    ← Dépendances backend
│
├── ai_models/              ← Dossier pour les modèles IA
│   ├── vision/             ← Modèle YOLOv8 pour détection dégâts
│   ├── chatbot/            ← Intégration GPT-4 ou OpenAI
│
├── mobile-app/             ← App mobile React Native
│   ├── App.js              ← App principale
│   └── screens/            ← Upload photo, résultats, chat...
│
├── data/                   ← Tes fichiers images/devis à utiliser localement
│
├── .env.example            ← Variables d’environnement (OpenAI key, etc.)
├── README.md               ← Instructions de setup

✅ Upload de photo
✅ Appel du modèle de vision (structure prête pour YOLOv8)
✅ Appel à OpenAI (chatbot technique)
✅ Backend API en FastAPI
✅ Frontend mobile React Native (Expo) avec écran upload + chat

