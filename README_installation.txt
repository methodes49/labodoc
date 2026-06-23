OUTILS MÉTHODES — LABO.DOC + GÉNÉRATEUR DE STANDARDS

UTILISATION LOCALE
1. Dézipper le dossier complet.
2. Ouvrir le fichier index.html.
3. Depuis l'écran Modèles, cliquer sur la carte "Générateur de standards".
4. Le générateur s'ouvre depuis : ./standards/index.html

IMPORTANT
- Ne pas sortir le fichier standards/index.html de son dossier "standards", sinon le lien local cassera.
- Pour partager sur un réseau, copier le dossier complet "Outils_Methodes_LABODOC_Standards".

OPTION WEB / INTRANET / GITHUB PAGES
Dans index.html, une option est prévue pour ouvrir une adresse web à la place du fichier local.
Chercher ces lignes :

  window.LABODOC_STANDARDS_WEB_URL = window.LABODOC_STANDARDS_WEB_URL || '';
  window.LABODOC_STANDARDS_USE_WEB = window.LABODOC_STANDARDS_USE_WEB || false;

Puis remplacer par exemple par :

  window.LABODOC_STANDARDS_WEB_URL = "https://adresse-validee-par-le-si/";
  window.LABODOC_STANDARDS_USE_WEB = true;

Tant que LABODOC_STANDARDS_USE_WEB vaut false, la carte ouvre le lien local ./standards/index.html.
