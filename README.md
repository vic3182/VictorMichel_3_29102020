# Produce maintainable CSS stylesheets with SASS

CSS is the palette we use to paint the web, making pages beautiful, identifiable, and responsive. In this class we’ll learn to write clean, maintainable, and modular CSS code through the implementation of designed naming and file structures, such as BEM, and the use of SASS, a CSS precompiler.

# Commandes SASS

1. Installer node.js 

2.Initialiser le npm 

Dans le terminal et CD C:\Users\Victor\Desktop\Projet-3 puis npm init 

3. Installer Node sass

Dans le terminal : npm install node-sass

4. Ecrire la commande node-sass

Ouvrir package.json dans visual code puis ajouter commande scss dans scripts : 
"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  "scss": "node-sass -watch scss -o css"
}

5. Exécuter le script 

npm run scss 
