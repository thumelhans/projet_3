# Projet 3: Ohmyfood

## Pour faire fonctionner SASS

---

1. Etape 1: (si pas déjà fait)

- Installez Node.JS

---

2. Etape 2: (si pas déjà fait)

- Initialisez NodeJS : npm init
- Installer Sass : npm install -g sass
- Vérification de la version sass: sass --version

---

3. Etape 3:

- Configuer le package.json
- Dans script: "sass": "sass --watch [source: scss]:[destination: css]"

---

4. Etape 4:

- Lancer le script sass: npm run sass

## Pour faire fonctionner Autoprefixer

---

1. Etape 1: (si pas déjà fait)

- Installez Node.JS

---

2. Etape 2: (si pas déjà fait)

- Initialisez NodeJS : npm init
- Installer Sass : npm install autoprefixer postcss postcss-cli -g (attention selon votre version de Node.JS vous devrez sans doute mettre --local:global à la place de -g)
- Vérification de la version autoprefixer: autoprefixer --version

---

3. Etape 3:

- Configuer le package.json
- Dans script: "prefix": "postcss [source: scss] --use autoprefixer -d [destination: css]"
- [optionel]: configurer le nombre de version précédente pris en charge ajouter à la fin du package.json
  - "browserslist": "last [xxxx] versions"

---

4. Etape 4:

- Lancer le script autoprefixer: npm run prefix
