Application # Backroads App

[Application de travail déployée](https://backroads-react-project-app.netlify.app/)

- backroads-html-projet html/css/javascript de travail (contient des actifs)
- final (code source complet) - application react fonctionnelle
  - accédez au dossier
  - exécutez 'npm install'
  - une fois les dépendances installées, exécutez'npm start'

#### Créer une Nouvelle Application React

- installer

```sh
npx create-react-app@latest backroads-app
```

- run dev server

```sh
npm start
```

### Dossier # SRC (passe-partout)

- index.js

```js
import React from "react";
import ReactDOM from "react-dom/client";

//styles (généralement globaux)
import "./index.css";

// convention pour nommer l'application et la configurer dans un fichier séparé
import App from "./App";
// rapport d'importation des signes vitaux web
import reportWebVitals from "./reportWebVitals";

// StrictMode

// StrictMode est un outil pour mettre en évidence les problèmes potentiels dans une application.Active des vérifications et des avertissements supplémentaires pour ses descendants.Fonctionne uniquement en développement, n'a pas d'impact sur la version de production. RENDU DEUX FOIS !!! Possible de supprimer.

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);

// Si vous souhaitez commencer à mesurer les performances de votre application, transmettez une fonction
// pour enregistrer les résultats (par exemple: reportWebVitals (console.log))
// ou envoyez-le à un point de terminaison Analytics. En savoir plus: https://bit.ly/CRA-vitals
reportWebVitals();
```

`
