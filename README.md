[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/AzG32zf0)
## 1) Navbar horizontale simple (desktop)

**Objectifs :** apprendre à créer une barre de navigation horizontale.  
**Contraintes :** pas de positionnement.  

**Consignes :**
* Crée un élément principal (comme un conteneur) qui contiendra la navigation.  
* Ajoute un élément pour le logo (texte simple).  
* Ajoute ensuite 5 liens de navigation dans une liste.  
* Trouve comment afficher les liens côte à côte au lieu les uns sous les autres.  
* Ajoute un espace entre les liens (par exemple en donnant une marge).  
* Ajoute un effet visuel quand on passe la souris sur un lien (changement de couleur, soulignement, etc.).  
* Vérifie que la navigation reste lisible si le fond est clair ou sombre.  

**Critères :** tous les liens sont bien alignés sur une même ligne, les espacements sont réguliers, et le logo se distingue des liens.  
**Bonus :** ajoute une animation fluide sur le soulignement des liens quand on les survole.

![exo 01- Navbar](assets/exo01.png)
---

## 2) “Hero” bandeau d’accueil

**Objectifs :** apprendre à structurer une section d’accueil avec un titre et un bouton.   

**Consignes :**
* Crée une section d’accueil avec un grand titre, un sous-titre, un paragraphe descriptif et un bouton d’action.  
* Trouve comment centrer le texte horizontalement.  
* Donne une largeur maximale au texte pour ne pas qu’il soit trop large sur grand écran.  
* Le bouton doit ressembler à un vrai bouton : fond, bord arrondi, texte lisible.  
* Prévoyez un effet visuel au survol (ex : changement de couleur ou d’ombre).  
* Ajoute un peu d’espace entre les lignes pour que le texte soit agréable à lire.  

**Critères :** la section est équilibrée, le texte est centré, et le bouton est bien visible.  
**Bonus :** ajoute un dégradé de fond ou une légère texture en arrière-plan.

![exo 02- Hero](assets/exo02.png)
---

## 3) Cards produit (liste 2–3 par ligne)

**Objectifs :** créer plusieurs blocs similaires pour présenter des produits.   

**Consignes :**
* Crée une structure répétée : une image, un titre, un prix et un bouton.  
* Trouve comment afficher plusieurs cartes côte à côte (2 ou 3 selon la taille de l’écran).  
* Ajoute un petit espace entre les cartes.  
* Chaque carte doit avoir un fond et un encadrement léger pour se détacher du fond.  
* Mets un espace intérieur pour éviter que le texte touche les bords.  
* Le bouton doit être visible, avec un effet au survol.  

**Critères :** les cartes sont alignées, espacées et lisibles.  
**Bonus :** ajoute une petite mention spéciale sur une carte (ex : “Promo” ou “Nouveau”) à l’intérieur du contenu, sans utiliser de position absolue.

![exo 03- Produits](assets/exo03.png)
---

## 4) Formulaire d’inscription accessible

**Objectifs :** apprendre à organiser et styliser un formulaire complet.  
**Contraintes :** pas de positionnement. Utiliser les balises sémantiques (`fieldset`, `legend`, `label`, `input`).  

**Consignes :**
* Crée un formulaire avec un titre.  
* Ajoute des champs pour le nom, l’email et le mot de passe.  
* Ajoute une case à cocher pour accepter les conditions et un bouton pour valider.  
* Chaque champ doit être accompagné d’un label au-dessus ou à côté.  
* Laisse un espace vertical entre chaque groupe de champ.  
* Trouve un moyen de rendre le focus (quand on clique sur un champ) bien visible.  
* Le bouton doit se démarquer des autres éléments du formulaire.  

**Critères :** les champs sont alignés, faciles à lire et accessibles.  
**Bonus :** ajoute un texte d’aide en petit sous chaque champ (par exemple pour expliquer le format du mot de passe).

![exo 04- Formulaire](assets/exo04.png)
---

## 5) Tableau de prix (pricing table)

**Objectifs :** apprendre à styliser un tableau pour présenter plusieurs offres.  
**Contraintes :** utiliser la balise `<table>` sans positionnement ni flexbox.  

**Consignes :**
* Crée un tableau avec une ligne d’en-têtes et plusieurs lignes de contenu.  
* Les colonnes représentent des offres (ex : Basique, Pro, Premium).  
* Donne un style différent à la ligne d’en-têtes pour qu’elle ressorte.  
* Alterne la couleur des lignes pour faciliter la lecture.  
* Ajoute un effet au survol d’une ligne ou d’une colonne.  
* Les bordures du tableau doivent être fines et régulières.  

**Critères :** le tableau est bien aligné, agréable à lire et structuré.  
**Bonus :** fais ressortir une colonne “recommandée” avec une couleur ou un style particulier.

![exo 05- Tableau](assets/exo05.png)
---

## 6) Bloc image + texte (mise en page “media object”)

**Objectifs :** apprendre à afficher une image à côté d’un texte.  
**Contraintes :** pas de flexbox ni de positionnement, utiliser le flot naturel.  

**Consignes :**
* Crée un bloc contenant une image et un texte.  
* L’image doit apparaître à gauche et le texte à droite sur grand écran.  
* Ajoute un titre, un paragraphe et un bouton sous le texte.  
* Laisse de l’espace entre l’image et le texte.  
* Sur mobile, le texte doit passer sous l’image (penser à une règle conditionnelle).  

**Critères :** l’image et le texte sont bien alignés, le tout reste lisible sur mobile.  
**Bonus :** ajoute une petite icône avant certains paragraphes (par exemple avec `::before`).

![exo 06- Image](assets/exo06.png)
---

## 7) Footer multi-colonnes

**Objectifs :** apprendre à structurer un pied de page.    

**Consignes :**
* Crée un footer avec un fond différent du reste du site.  
* Ajoute 3 ou 4 sections : “À propos”, “Liens utiles”, “Contact”, “Réseaux”.  
* Chaque section a un titre et plusieurs liens ou textes.  
* Trouve comment afficher les sections les unes à côté des autres.  
* Ajoute un peu d’espace intérieur et autour des colonnes.  
* Rends le texte du footer lisible sur fond sombre.  

**Critères :** colonnes alignées, espacement régulier, contenu lisible.  
**Bonus :** ajoute une ligne décorative ou un effet de dégradé en haut du footer.

![exo 07- Footer](assets/exo07.png)
---

## 8) Fil d’Ariane (breadcrumbs) + Pagination

**Objectifs :** créer deux composants de navigation.  
**Contraintes :** uniquement en ligne, aucun positionnement.  

**Consignes :**
* Crée un petit fil d’Ariane : “Accueil > Boutique > Produit”.  
* Chaque élément doit être cliquable sauf le dernier.  
* Ajoute un séparateur entre les liens (ex : “>”).  
* Juste en dessous, crée une pagination avec des numéros de pages.  
* Les liens doivent être visibles, et la page actuelle doit avoir un style différent.  
* Ajoute un effet visuel quand on passe la souris sur les liens.  

**Critères :** navigation claire, lisible et alignée.  
**Bonus :** ajoute un état pour la page active avec une couleur ou un soulignement différent.

![exo 08- Ariane](assets/exo08.png)
---

## 9) FAQ accordéon CSS-only

**Objectifs :** créer un accordéon interactif sans JavaScript.  
**Contraintes :** aucun positionnement, uniquement des balises natives ou des interactions CSS.  

**Consignes :**
* Crée une liste de 5 ou 6 questions.  
* Chaque question doit pouvoir se dérouler pour afficher sa réponse.  
* Utilise une balise ou un système qui permet d’ouvrir/fermer sans JavaScript.  
* Donne un style clair à la question (gras, icône à gauche par exemple).  
* La réponse doit apparaître en dessous quand la question est ouverte.  
* Ajoute un effet de transition pour rendre l’ouverture fluide.  

**Critères :** fonctionnement fluide, lecture claire, accessibilité clavier respectée.  
**Bonus :** fais tourner ou changer l’icône selon l’état ouvert/fermé.

![exo 09- FAQ](assets/exo09.png)
---

## 10) Navbar responsive avec toggle CSS

**Objectifs :** apprendre à rendre une navigation adaptable au mobile sans position absolue.  
**Contraintes :** aucun positionnement; utiliser une technique CSS simple (checkbox ou details).  

**Consignes :**
* Reprends le principe de la première navbar.  
* Ajoute un bouton ou une case à cocher qui affiche/masque le menu.  
* Sur grand écran, les liens doivent être visibles en ligne.  
* Sur petit écran, le menu doit se replier et s’ouvrir au clic.  
* Ajoute un effet de transition quand le menu s’ouvre.  
* Le tout doit rester navigable au clavier.  

**Critères :** navigation fluide sur tous les écrans, aucun débordement, tout est lisible.  
**Bonus :** crée une icône de menu “hamburger” en pur CSS (trois barres qui deviennent une croix à l’ouverture).

![exo 10- Navbar Toggle](assets/exo10.png)
![exo 10- Navbar Toggle](assets/exo10_2.png)

## Charte Graphique

 ### Couleurs
  * --bg: #ecf7f5;
  *  --muted: #e8f1ef;
  * --text: #0f1b1a;
  * --text-soft: #425a58;
  * --primary: #0f766e;
  * --primary-700: #0c5f59;
  * --primary-100: #e0f2f1;
  * --accent: #22c5ac;
  * --warning: #f59e0b;
  * --radius: 16px;
  * --shadow: 0 6px 18px rgba(15, 118, 110, 0.1);

### Polices
  * font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto,"Helvetica Neue", Arial, sans-serif;