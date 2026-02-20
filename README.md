# 🚀 Mon App Node.js avec Docker

Application simple développée avec Node.js et Express, conteneurisée avec Docker.


---

## 📁 Structure du projet

mon-app/
├── package.json
├── index.js
└── Dockerfile

---

## 🛠 Technologies utilisées

- Node.js 18
- Express
- Docker

---

## ▶️ Exécution sans Docker

1. Installer les dépendances :

npm install

2. Lancer l’application :

npm start

3. Ouvrir dans le navigateur :

http://localhost:3000

---

## 🐳 Exécution avec Docker

1. Construire l’image Docker :

docker build -t mon-app-node .

2. Lancer le conteneur :

docker run -p 3000:3000 mon-app-node

3. Ouvrir dans le navigateur :

http://localhost:3000

---

## 📌 Résultat

L’application affiche :

Hello Docker!

---

## 👨‍💻 Auteur

Nacer Amar
