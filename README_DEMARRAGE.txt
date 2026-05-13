═══════════════════════════════════════════════════════════════════════════════
                    APPRENDRE À CODER - GUIDE COMPLET
                          Pour Ketty - Déc 2024
═══════════════════════════════════════════════════════════════════════════════

🌿 BIENVENUE !

Tu as maintenant TROIS documents complets pour apprendre à coder :

1. 📖 Guide complet (guide_codage_floral_corrige.html)
   ➜ Explication détaillée de TOUS les concepts
   ➜ 13 sections : HTML, CSS, JS, DOM, localStorage, API, débogage, etc.
   ➜ Exercices avec solutions
   ➜ Ressources pour continuer

2. 📋 Cheat Sheet (cheat_sheet_webdev.html)
   ➜ Référence rapide à garder en favori
   ➜ Tous les snippets (petits bouts de code) les plus utiles
   ➜ À consulter quand tu oublies une syntaxe

3. 🗺️ Plan 12 semaines (plan_apprentissage_12_semaines.html)
   ➜ Progression structurée semaine par semaine
   ➜ Projets progressifs
   ➜ Du débutant à "app personnelle complète"

═══════════════════════════════════════════════════════════════════════════════

🚀 PAR OÙ COMMENCER ?

Semaine 1 :
─────────
1. Ouvre le guide complet (section "Fondamentaux")
2. Lis les 3 piliers du web (HTML, CSS, JS)
3. Crée ta première page HTML : hello.html
4. Colle ce code :

   <!DOCTYPE html>
   <html lang="fr">
   <head>
       <meta charset="UTF-8">
       <title>Ma première page</title>
   </head>
   <body>
       <h1>Bonjour Flōra ! 🌿</h1>
       <p>Je suis en train d'apprendre à coder !</p>
   </body>
   </html>

5. Ouvre le fichier dans un navigateur
6. Bravo ! Tu as créé ta première page web 🎉

═══════════════════════════════════════════════════════════════════════════════

📚 LES 8 PILIERS DU CODE WEB

Pilier 1 : HTML (Structure)
──────────────────────────
La STRUCTURE de ta page. Les murs d'une maison.

Exemple Flōra :
    <div class="recette">
        <h2>Salade Pois Chiches</h2>
        <p>250 cal</p>
        <button>Ajouter</button>
    </div>

Pilier 2 : CSS (Style)
─────────────────────
L'APPARENCE et les COULEURS. La peinture d'une maison.

Exemple Flōra :
    .recette {
        background: white;
        color: #6b9e87;
        padding: 20px;
        border-radius: 8px;
    }

Pilier 3 : JavaScript (Logique)
───────────────────────────────
Les ACTIONS et l'INTERACTIVITÉ. L'électricité d'une maison.

Exemple Flōra :
    function ajouterAuRepas() {
        console.log("Recette ajoutée !");
    }

Pilier 4 : DOM (Manipulation)
────────────────────────────
MODIFIER la page EN TEMPS RÉEL sans recharger.

Exemple Flōra :
    let element = document.getElementById("recettes");
    element.innerHTML = "<p>Nouvelle recette !</p>";

Pilier 5 : Événements
────────────────────
RÉAGIR aux clics, à la saisie de l'utilisateur, etc.

Exemple Flōra :
    button.addEventListener("click", () => {
        ajouterAuRepas();
    });

Pilier 6 : localStorage
──────────────────────
SAUVEGARDER les données même après fermeture de la page.

Exemple Flōra :
    localStorage.setItem("favoris_1", "true");
    let favori = localStorage.getItem("favoris_1");

Pilier 7 : API & Fetch
─────────────────────
COMMUNIQUER avec d'autres serveurs pour récupérer des données.

Exemple Flōra :
    fetch('/recettes.json')
        .then(response => response.json())
        .then(data => console.log(data));

Pilier 8 : Débogage
──────────────────
TROUVER et CORRIGER les erreurs avec console.log().

Exemple Flōra :
    console.log("Valeur de calories: " + calories);

═══════════════════════════════════════════════════════════════════════════════

💡 10 CONSEILS POUR RÉUSSIR

1. CODE CHAQUE JOUR
   30 minutes/jour > 5h le weekend
   La régularité est la clé.

2. UTILISE CONSOLE.LOG()
   C'est ton meilleur ami. L'ajoute partout.
   F12 → Onglet Console pour voir les messages.

3. ACCEPTE LES ERREURS
   Tous les programmeurs les font. C'est normal !
   C'est comme ça qu'on apprend.

4. NE COPIE PAS TON CODE
   Recopie-le à la main. Ton cerveau apprendra mieux.

5. CRÉE DES PROJETS
   La meilleure façon d'apprendre : faire des apps qui t'intéressent.
   Un tracker de douleur ? Une liste de courses ? Fais-le !

6. LIS DU CODE D'AUTRES
   Sur GitHub, regarde comment les pros font les choses.

7. NOMME TES VARIABLES EXPLICITEMENT
   Pas : let x = 250;
   Oui : let caloriesRecette = 250;

8. COMMENTE TON CODE
   Explique le POURQUOI, pas le QUOI.
   // Filtrer les recettes légères (< 300 cal)
   let legeres = recettes.filter(r => r.calories < 300);

9. TESTE AVEC DE PETITS EXEMPLES
   Avant de modifier ton app complète,
   teste d'abord dans la console.

10. REJOINS UNE COMMUNAUTÉ
    Trouve des gens qui apprennent aussi.
    Discord, Reddit, groupe local.
    Les meilleurs apprentissages viennent des questions.

═══════════════════════════════════════════════════════════════════════════════

⚠️ ERREURS COURANTES

❌ Erreur 1 : Attendre d'être "prête" avant de coder
   Non ! Commence maintenant, même si tu n'es pas sûre.
   Faire des erreurs = apprendre.

❌ Erreur 2 : Mémoriser la syntaxe au lieu de la comprendre
   Non ! Tu l'oublieras. Comprendre est plus important.
   Google + cheat sheet suffisent.

❌ Erreur 3 : Sauter les exercices
   Non ! Faire les exercices = apprendre vraiment.
   Lire sans coder = regarder la piscine sans nager.

❌ Erreur 4 : Avoir peur de casser quelque chose
   Non ! C'est impossible de "casser" en codant localement.
   C'est là qu'on apprend.

❌ Erreur 5 : Apprendre sans projet concret
   Non ! Code pour résoudre UN PROBLÈME que tu as.
   Une app générique ennuie. Une APP TIE intéresse.

═══════════════════════════════════════════════════════════════════════════════

🎯 TON PREMIER MINI-PROJET : Mini Flōra

Objectif : Créer une app fonctionnelle en 2 semaines.

Étape 1 : HTML (jour 1-2)
─────────────────────────
Crée index.html avec :
- 1 titre "🌿 Mini Flōra"
- 3 recettes (div avec nom + calories)
- 1 div "Mon repas" vide
- 1 bouton "Ajouter au repas" pour chaque recette

Étape 2 : CSS (jour 3-4)
─────────────────────────
Stylise avec :
- Couleurs Flōra (vert #6b9e87, coral #e8a995)
- Cartes pour chaque recette
- Boutons avec survol

Étape 3 : JavaScript (jour 5-10)
───────────────────────────────
Ajoute l'interactivité :
- Clic sur "Ajouter" → La recette apparaît dans "Mon repas"
- Affiche le total de calories
- Bouton "Retirer" pour chaque recette

Étape 4 : Finition (jour 11-14)
───────────────────────────────
- Nettoie ton code
- Ajoute des commentaires
- Teste tout
- Partage sur GitHub Pages

═══════════════════════════════════════════════════════════════════════════════

📖 VOCABULAIRE ESSENTIEL (à retenir)

DOM = Document Object Model
    La représentation de ta page HTML sous forme d'arbre.
    JavaScript peut la modifier.

API = Application Programming Interface
    Un moyen pour 2 apps de communiquer.

localStorage = Stockage du navigateur
    Les données restent même après fermeture.

JSON = JavaScript Object Notation
    Format pour écrire des données structurées.
    {"nom": "Salade", "calories": 250}

Promise = Une promesse
    "Je te promets que je vais faire quelque chose"
    Utilisé avec fetch().

Callback = Une fonction passée à une autre fonction
    forEach((recette) => { ... })
    La fonction fléchée est le callback.

Scope = La "portée" d'une variable
    Une variable créée dans une fonction n'existe que là.

Event = Un événement
    Clic, saisie, chargement, etc.

Method = Une fonction appartenant à un objet
    array.push(), string.toUpperCase()

Class = Une classe CSS (sélecteur)
    .recette { color: red; }

═══════════════════════════════════════════════════════════════════════════════

🔗 RESSOURCES GRATUITES

Documentation :
─────────────
- MDN Web Docs (mdn.org) = LA référence. Bookmark-le !
- W3Schools (w3schools.com) = Tutoriels interactifs
- Eloquent JavaScript (en ligne, gratuit) = Livre excellent

Vidéos :
───────
- freeCodeCamp (YouTube) = Cours complets gratuits
- The Net Ninja (YouTube) = Tutoriels web dev
- Grafikart (YouTube, français) = Web design et dev

Outils :
───────
- CodePen (codepen.io) = Voir/modifier du code
- GitHub (github.com) = Partager ton code
- GitHub Pages = Publier ton app (gratuit !)

Communauté :
───────────
- Discord (cherche "coding for beginners")
- Reddit (r/learnprogramming)
- Groupe local près de toi

═══════════════════════════════════════════════════════════════════════════════

✅ CHECK-LIST : TON PLAN CETTE SEMAINE

Lundi :
  ☐ Ouvre le guide complet
  ☐ Lis "Les Fondamentaux"
  ☐ Crée hello.html

Mardi-Mercredi :
  ☐ Lis section HTML
  ☐ Crée ta page "À propos de Flōra" (HTML + texte)
  ☐ Teste dans le navigateur

Jeudi-Vendredi :
  ☐ Lis section CSS
  ☐ Stylise ta page (couleurs, fonts, padding)
  ☐ Rends-la responsive

Samedi-Dimanche :
  ☐ Relis les sections 1-3 au complet
  ☐ Sauvegarde le guide et la cheat sheet en favori
  ☐ Plan ta semaine 2 (commencer JavaScript)

═══════════════════════════════════════════════════════════════════════════════

💪 MESSAGE FINAL

Tu as TOUS les outils pour réussir. C'est maintenant que ça devient vraiment cool.

En 12 semaines, tu seras capable de créer des apps WEB VRAIES.
Des apps utiles. Des apps que TU vas utiliser tous les jours.

Le voyage commence maintenant. Pas demain. MAINTENANT.

30 minutes. C'est tout ce qu'il faut.

Ouvre le guide.
Crée ton premier fichier HTML.
Bravo. Tu as commencé. 🌿

À bientôt, développeuse !

═══════════════════════════════════════════════════════════════════════════════
