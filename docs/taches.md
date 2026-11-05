# Tableau des tâches

> Planifiez vous-même, puis tenez le tableau à jour. Une preuve : un commit, un test vert, un document.

| Tâche | Prévu | Fait le | Preuve |
| --- | --- | --- | --- |
| Poste et dépôt prêts ; besoin compris ; documents commencés | 03/11/2026| 03/11/2026|Commit: Départ du bref 3: kit fourni |
| Fiche 2 : lire et écrire le JSON | 03/11/2026|03/11/2026 |Commit: charges JSON |enregistrement JSON
| Fiche 3 : ajouter et lister ; choix 1 et 2 ; erreurs |03/11/2026 |03/11/2026 |Commit: Ajouter observation/ lister observation |
| Fiche 4 : rechercher et trier ; choix 3 et 4 |04/11/2026 |04/11/2026 | Commit:trier par pH/ filtrer par parcelle|
| Fiche 5 : synthèse ; choix 5 | 04/11/2026|04/11/2026 |Commit: points à discuter/pH min max |
| Tests par un camarade ; mes propres tests | 04/11/2026|04/11/2026 | App.js dictionnaire-donnes,fiche-agronomique|
| Fiche agronomique ; README ; documents |05/11/2026 |05/11/2026 |Commit: Dans le README, ajout du contexte |
| Dépôt cloné et lancé ailleurs ; démonstration répétée | 05/11/2026| 05/11/2026| tests de validation locale reussis|
| Bonus | 04/11/2026|04/11/2026 |Commit: Modifier observation/ Supprimer observation/texture la plus frequente |

**Blocages** (le message exact, ce que j'ai essayé, la solution) : 
problème racontré :
 Erreur de lecture/ecriture asynchrome lors de lattente du chargement du fichier JSON avec les fonctions de stockage(`donnees/observations.json`)

Message exact: 
`<< UnhandledPromiseRejectionWarning: TypeError: canot read properties of undefined (reading 'find')>>`

Ce que j'ai essayé: 
je me suis referé à AI pour decouvrir le problème

Solution: Ajouter le mot-clé `<<await>>` devant la fonction de chargement asynchrone pour récupérer correctements les données avant de les manipulées..

