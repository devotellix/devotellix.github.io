# Guide d'Activation du Référencement Google (Devotellix)

Pour que votre site apparaisse en premier sur Google Tunisie pour les recherches comme **"transformation énergétique tunisie"** ou **"cabinet conseil ISO 50001"**, vous devez finaliser l'enregistrement de votre site auprès des outils officiels de Google. 

Comme ces étapes nécessitent l'accès à votre compte Google personnel, voici la procédure simplifiée pour le faire en moins de 5 minutes.

---

## Étape 1 : Valider le site sur Google Search Console (GSC)

La Search Console est l'outil gratuit de Google qui lui indique d'indexer votre site immédiatement.

1. Allez sur [Google Search Console](https://search.google.com/search-console) et connectez-vous avec votre compte Gmail.
2. Cliquez sur **Ajouter la propriété**.
3. Choisissez le type de propriété **Préfixe de l'URL** et saisissez :
   `https://devotellix.github.io/`
4. Google va vous proposer plusieurs méthodes de validation. Choisissez **Balise HTML** (Meta tag).
5. Copiez le code fourni par Google, qui ressemble à ceci :
   `<meta name="google-site-verification" content="XXXXXX..." />`
6. Ouvrez votre fichier [index.html](file:///Users/macpro/Documents/GitHub/devotellix.github.io/index.html) et collez cette balise juste en dessous de la ligne 9 (`<head>`).
   *Un emplacement réservé a été préparé dans le fichier `index.html` pour vous faciliter cette étape.*
7. Enregistrez, mettez en ligne (déployez sur GitHub Pages), puis revenez sur la Search Console et cliquez sur **Valider**.

---

## Étape 2 : Soumettre votre plan du site (Sitemap)

Une fois le site validé dans la Search Console :

1. Dans le menu de gauche, cliquez sur **Sitemaps**.
2. Dans le champ "Ajouter un nouveau sitemap", saisissez simplement :
   `sitemap.xml`
3. Cliquez sur **Envoyer**.
4. *Google va lire instantanément le fichier `sitemap.xml` que nous avons mis à jour et va indexer la page d'accueil ainsi que toutes vos applications.*

---

## Étape 3 : Créer votre fiche Google Maps (Google Business Profile)

Pour apparaître tout en haut des résultats de recherche sous forme de carte géographique (très important pour les recherches locales en Tunisie) :

1. Allez sur [Google Business Profile](https://www.google.com/business/).
2. Créez un profil pour votre cabinet : **Devotellix Tunis - Cabinet Conseil ISO & Énergie**.
3. Indiquez la catégorie : **Cabinet de conseil** ou **Ingénieur-conseil**.
4. Saisissez l'adresse physique à Tunis : **Les Berges du Lac 2, Tunis 1053, Tunisie**.
5. Ajoutez le numéro de téléphone : **+216 73 534 160**.
6. Ajoutez le lien vers votre site web : `https://devotellix.github.io/`.
7. Validez la fiche (Google vous demandera une validation par SMS, appel ou enregistrement vidéo de vos bureaux).

---

## Étape 4 : Suivre votre trafic (Google Analytics - Optionnel)

Si vous souhaitez suivre le nombre de visiteurs venant de Tunisie et de France :
1. Créez un compte sur [Google Analytics](https://analytics.google.com/).
2. Obtenez votre identifiant de mesure qui ressemble à `G-XXXXXX`.
3. Un emplacement a été prévu dans la balise `<head>` du fichier `index.html` pour coller ce code de suivi.
