FROM node:latest # Take the last version of node as image

WORKDIR /usr/src/app	 # definir le repertoire de travail

COPY package*.json ./  # copier le fichier package.jon

RUN npm install # installer les dependances

COPY . ./ # copie des fichiers sources

EXPOSE	5555 # port de sortie 5555

CMD ["npm", "start"] # commande npm start
