# Utilise l'image officielle Node.js en tant qu'image de base
FROM node:16

# Définit le répertoire de travail
WORKDIR /app

# Copie les fichiers de dépendances
COPY package*.json ./

# Installe les dépendances
RUN npm install

# Copie le reste des fichiers de l'application
COPY . .

# Expose le port de l'application
EXPOSE 3000

# Démarre l'application
CMD ["npm", "start"]
