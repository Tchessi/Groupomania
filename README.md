# Groupomania

Projet 7 de la formation openClassroom , Création d'un réseau social pour l'entreprise Groupomania

## Utilisation du projet

## Commencer par cloner le projet

git clone git@github.com:Tchessi/Groupomania.git

## Front-end

```
cd fron-tend
npm install
npm run serve
Le frontend est accessible à l'adresse http://localhost:8080

```

## Back-end

```
cd back-end
npm install
npm i nodemon
nodemon server ou node server
Pour des tests spécifiques (avec postman par exemple), le backend répond à l'adresse: http://localhost:3000

```
## Base de données

```
cd back-end
mpn i mysql -g 

# Vérifier que le nom d'utilisateur et le mot de passe dans le fichier de configuration config.json correspondent à vos informations d'identification MySQL locales

npx sequelize-cli db:create
npx sequelize-cli db:migrate

# Pour installer sequilize CLI
 
npm install --save-dev sequelize-cli



```

## Technologies utilisées

```
# Pour le serveur : Node.js et framework Express
# Pour la base de données : MySQL et Sequelize ORM
# Pour le frontend : Vue.js (Vue Router, Vuex), Sass, Bootsrap et BootsrapVue

```

## Mesures de sécurité et de mise en place

```
# Hashage du mot de passe utilisateur avec bcrypt
# Authentification de l'utilisateur par token avec jsonwebtoken

```
## API documentation Postman
https://documenter.getpostman.com/view/17540434/UVsLRRvc

