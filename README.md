# MARISATEL — version complète sans images satellitaires

## Contenu
- Site multipage : accueil, carte, indicateurs, analyse, rapport, sources et services.
- Pages séparées pour SST, salinité, chlorophylle-a, bathymétrie, courants, turbidité, vagues et oxygène dissous.
- Données tabulaires disponibles dans `data/` et intégrées dans les pages correspondantes pour éviter le blocage de lecture CSV en ouverture locale.
- CSS/JavaScript dans `assets/`.
- Aucune image satellitaire n'est incluse : elles seront ajoutées dans une étape ultérieure.

## Remplacement complet du dépôt GitHub
1. Téléchargez et décompressez cette archive.
2. Ouvrez le dossier `MARISATEL_VERSION_FINALE_SANS_IMAGES`.
3. Dans le dépôt GitHub `Marisatel`, remplacez les anciens fichiers du site par **tout le contenu de ce dossier** (pas le dossier parent lui-même).
4. Conservez les chemins `assets/` et `data/`.
5. Validez avec `Commit changes`. GitHub Pages publiera ensuite la version mise à jour.

## Notes scientifiques
- Les points représentent les données fournies, pas une interpolation raster continue.
- Les dates et périodes peuvent différer selon l'indicateur.
- La salinité, les courants, les vagues et l'oxygène peuvent provenir de produits de modèles/réanalyses ou d'autres sources : ne pas les qualifier de mesures satellitaires directes sans métadonnées justificatives.
- Les images satellitaires et les rasters thématiques définitifs ne sont pas inclus dans cette version.
- Vérifier les métadonnées, unités, résolution et contrôle qualité avant toute interprétation ou décision aquacole.
