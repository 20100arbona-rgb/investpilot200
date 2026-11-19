INVESTPILOT 200 — version 1

Application web progressive (PWA) adaptée aux téléphones Android et iPhone.

INSTALLATION
1. Décompresser le ZIP.
2. Publier le contenu du dossier sur un hébergement statique HTTPS (GitHub Pages, Netlify, Cloudflare Pages...).
3. Ouvrir l'adresse HTTPS sur le téléphone.
4. Android : menu du navigateur > Installer l'application.
   iPhone : Safari > Partager > Sur l'écran d'accueil.

TEST SUR ORDINATEUR
Dans le dossier : python -m http.server 8000
Puis ouvrir http://localhost:8000

COURS
Dans Réglages, entrer une clé personnelle Twelve Data. Actualiser manuellement depuis Accueil. Les données peuvent être différées et les symboles limités selon le forfait. Aucune cotation fictive n'est fournie.
Les clés API enregistrées dans le navigateur ne sont pas sécurisées comme sur un serveur : utiliser une clé dédiée et limitée, et ne pas partager l'appareil.

LIMITES
Les alertes fonctionnent uniquement lors des actualisations manuelles, pas en arrière-plan. Pas de connexion Trade Republic, pas de passage d'ordre, pas de recommandations garanties. Portefeuille initial saisi à partir des montants approximatifs communiqués.
Les données restent dans le stockage local du navigateur : utiliser Exporter pour les sauvegarder. Une suppression des données du navigateur peut les effacer.
