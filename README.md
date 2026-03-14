# Initialiser le projet
npx create-vite@latest immobilier-rdc --template react
cd immobilier-rdc

# Installer les dépendances
npm install
npm install react-icons
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

# Copier tous les fichiers que j'ai fournis
# (Remplacer src/App.jsx, src/index.css, créer src/components/, src/data/)

# Initialiser Git et pousser
git remote add origin https://github.com/jeancykabangu7-blip/immobilier-rdc.git
git branch -M main
git add .
git commit -m "feat: Initial commit - ImmobilierRDC MVP"
git push -u origin main
