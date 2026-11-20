# PREL — Programme de Renforcement de la Lecture à l’Élémentaire

Plateforme web de présentation, d'information et de pré-inscription / candidature pour le **Programme de Renforcement de la Lecture à l’Élémentaire (PREL)**, déployé dans les communes de **Ndiayène Pendao, Fanaye et Guédé Village** (Département de Podor, Région de Saint-Louis, Sénégal).

---

## 1. Structure du dossier

Placez `index.html` et vos fichiers images dans un **même dossier** :

```text
prel-site/
├── index.html
├── README.md
├── PREL.png
├── images (1).jpeg
├── images (2).jpeg
├── images (8).jpeg
└── Saintlouis_ile_pecheur.jpg
```

> **Note :** Si une image n'est pas encore présente dans le dossier lors d'un test, une illustration de secours (SVG) s'affiche automatiquement afin d'éviter les images cassées.

---

## 2. Fonctionnalités de la plateforme

- **Barre de progression de lecture** : fine ligne dégradée (vert sarcelle `#117A7F` vers orange `#E07A16`) en haut de l'écran.
- **En-tête fixe & menu à 3 barres** : logo du PREL en haut à gauche et bouton menu à 3 barres animé en haut à droite ouvrant un tiroir latéral avec accès aux sections, raccourcis vers les formulaires et contact WhatsApp.
- **Présentation du programme & chiffres clés** : compteurs animés (*15* élèves max par groupe, *2x* séances par semaine hors cours, *4 sem.* par cycle, *3 000 F* de contribution mensuelle / élève).
- **Organisation pédagogique & suivi** : présentation du **Cycle 1 (CI & CP)**, du **Cycle 2 (CE1 à CM2)** et des étapes de suivi par cycles de 4 semaines.
- **Galerie photo interactive (Lightbox)** : agrandissement des photos du terrain avec navigation *Précédent / Suivant* (et flèches clavier `←` / `→`).
- **Formulaires interactifs avec aperçu et copie** :
  1. **Pré-inscription d'un élève**
  2. **Candidature Animateur / Animatrice pédagogique**
  3. **Demande d'implantation pour un Directeur d'école**
  Chaque formulaire valide les champs obligatoires, affiche un aperçu du message généré avec bouton **Copier le message**, et ouvre **WhatsApp** (`76 144 38 54`) ou la messagerie **E-mail** (`coordination.prel@gmail.com`).

---

## 3. Tester le site en local

1. Vérifiez que `index.html` et les 5 images se trouvent dans le même dossier.
2. Double-cliquez sur **`index.html`** pour l'ouvrir dans un navigateur web (Chrome, Edge, Firefox, Safari).
3. Testez l'ouverture du menu à 3 barres, le défilement, la galerie photo et l'un des formulaires.

---

## 4. Mettre le site en ligne

### Option rapide : Netlify Drop
1. Créez un compte gratuit sur [Netlify](https://app.netlify.com/).
2. Dans l'onglet **Sites**, glissez-déposez votre dossier contenant `index.html` et les images dans la zone prévue.
3. Ouvrez le lien `https://...netlify.app` généré pour vérifier l'affichage sur ordinateur et téléphone.

### Option : GitHub Pages
1. Créez un dépôt (*repository*) sur [GitHub](https://github.com/) et téléversez `index.html`, `README.md` et vos images à la racine.
2. Dans **Settings > Pages**, activez la publication depuis la branche principale (`main` / `master`), dossier `/ (root)`.

---

## 5. Coordination Générale

- **Responsable :** Moussa Alassane SOW (Coordonnateur Général)
- **WhatsApp :** `76 144 38 54` (`+221 76 144 38 54`)
- **Téléphone direct :** `78 538 89 21` (`+221 78 538 89 21`)
- **E-mail :** `coordination.prel@gmail.com`
