# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ     | Signification                    | Type   | Règle de validation         | Unité    |Exemple |
| ---       | ---------------------------------|--------|---------------------------- |----------|--------|
| `id`      | Identifiant unique               |  texte | non vide,absence des données| aucune   |   S03  |
|`parcelle` | référence de la parcelle observée|  texte |  ne doit pas être vide      | aucune   |    P2  |   
| `texture` |texture du sol observé            |  texte |Argileux, sableux, limoneux  | aucune   |argileux|
| `pH`      |potentiel d'hydrogène(pH observé) |nombre  |  compris entre 0 à 14       | aucune   |  6.8   |
| `etatHumidité` | Humidité du sol             |  texte |sec, humide,  intermediaire  | aucune   | humide |

**Listes de valeurs autorisées** : 

TEXTURE (texture du sol) : Sableux, argileux, limoneux
HUMIDITE (etatHumidité)  : sec , humidité, intermediaire
PARCELLE : P1, P2, P3, P4, P5


**Sources**:
- observation.json
- Ajouter-lister.md
- fiches de relevées a la ferme avec le coach..
