# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** : refaites à la main les résultats de référence de `SUJET.md`, puis comparez avec votre programme. 
- Nombre d'observation:10 Observations
- pH min 4,8 correspond à S04
- pH max = 7,6 correspond à S08

- Nombre de texture: sableux (3) S01, S04, S08
- Nombre de texture limoneux (4) S02, S05, S07, S10
- Nombre de texture argileux (3) S03, S06, S09

- Id: S04
- parcelle: p2
- texture: sableux
- pH: 4.8
- etatHumidité


**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action                   | Attendu                                            | Obtenu  |                    | Testeur |
| -------------------------------------------------------------------------------------------------------------------------------
|ajout valide              |observation ajoutée                      | observation ajouter                | ADAMA  KONATE        | 
|chaque règle refusée      |aucun ajout                              |          aucun ajout               | ADAMA  KONATE        |
|une recherche introuvable |introuvable                              |      trier reussi                  | ADAMA  KONATE        |
| chaque tri               |trier reussi                             |       trier reussi                 | ADAMA  KONATE        |
| la synthèse              |affiche les statistiques de lobservation | afficher observation          ;    | ADAMA  KONATE        |
| un choix inconnu         |aucune observation                       |  aucune observation                | ADAMA  KONATE        |





**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : ✏️.
