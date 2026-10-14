# GEI NXP Cup — Mechanical Design

Dépôt regroupant les pièces mécaniques conçues au département Génie Électrique et Informatique (GEI) de l'INSA Toulouse pour adapter le châssis **Alamak** du véhicule utilisé dans le cadre de la compétition NXP Cup.

Les pièces sont développées à l'aide de [FreeCAD](https://www.freecad.org/), logiciel libre de conception assistée par ordinateur (CAO) paramétrique.

## Organisation du dépôt

| Répertoire | Description |
|---|---|
| `./` | Modèles mécaniques développés avec FreeCAD pour adapter le châssis Alamak |
| [`Piste/`](Piste/) | Modèles 2D des éléments constituant la piste |
| [`Inventor/`](Inventor/) | Anciennes pièces conçues les années précédentes |

## Conception mécanique avec FreeCAD

Les modèles mécaniques permettent d'adapter le châssis Alamak aux besoins du robot NXP Cup.

FreeCAD est utilisé pour concevoir et modifier les pièces mécaniques. Les fichiers natifs permettent de conserver les modèles de conception et de les faire évoluer en fonction des besoins du projet.

Pour ouvrir ou modifier les modèles, installer FreeCAD depuis le [site officiel](https://www.freecad.org/).

## Répertoire `Piste/`

Le répertoire `Piste/` contient les modèles 2D des différents éléments de piste utilisés dans le cadre du projet.

Ces modèles servent de référence pour représenter les éléments de la piste et préparer leur réalisation (découpage laser).

## Répertoire `Inventor/`

Le répertoire `Inventor/` conserve les anciennes pièces conçues au cours des années précédentes.

Ces fichiers constituent une archive des conceptions historiques du projet. Ils peuvent être consultés pour retrouver des solutions mécaniques antérieures ou servir de point de départ à de nouvelles conceptions.

**Attention :** ces modèles historiques ne correspondent pas nécessairement à la configuration mécanique actuelle du véhicule.

## Contribuer au projet

Lorsqu'une pièce mécanique est créée ou modifiée :

1. Enregistrer les fichiers sources dans le répertoire approprié.
2. Utiliser des noms de fichiers explicites pour identifier les pièces et leur fonction.
3. Vérifier que les fichiers nécessaires à l'ouverture du modèle sont présents dans le dépôt.
4. Enregistrer les modifications dans Git afin de conserver l'historique des évolutions.

Privilégier la conservation des fichiers sources FreeCAD plutôt que de ne déposer que des exports géométriques, afin de permettre la reprise et la modification des conceptions.

## Ressources

- [FreeCAD — site officiel](https://www.freecad.org/)
- [Documentation FreeCAD](https://wiki.freecad.org/)

