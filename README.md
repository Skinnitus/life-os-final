# LIFE OS — Personal Organizer 2.0
Pack complet pour installation sur une NOUVELLE adresse Cloudflare Pages ou un NOUVEAU dépôt GitHub, indépendants de la production.

Les fichiers applicatifs sont à la racine du ZIP. Ne pas déplacer ni renommer assets/. Les polices et images sont déjà dans assets/ ; aucun téléchargement supplémentaire n’est nécessaire.

Commencer par docs/GUIDE_DEPLOIEMENT_ET_RETOUR_ARRIERE.md. Les tests exécutés et leurs limites figurent dans docs/RAPPORT_VERIFICATION.md. Les captures réelles sont dans docs/captures/.

50 tests fonctionnels réussis dans deux fuseaux et 15 tests de service worker avec réseau simulé. Le test hors ligne réel, l’installation Samsung et la mise à jour sur l’adresse HTTPS Cloudflare restent à effectuer après publication. Aucune connexion Google n’est nécessaire au fonctionnement de LIFE OS.

L’application démarre vide. Le fichier tests/DONNEES_SYNTHETIQUES.json est facultatif et ne contient aucune donnée personnelle. Exporter les données de l’ancienne application avant toute future migration ; conserver cette application jusqu’à validation.
