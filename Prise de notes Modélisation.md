# Prise de notes - Modélisation

## Dépendance fonctionnelle

- **Définition** : Relation entre deux attributs au sein d’une même entité. Une dépendance fonctionnelle existe lorsque la valeur d’un attribut dépend de celle d’un autre attribut.
- **Dépendance fonctionnelle composée** : Quand plusieurs attributs dépendent ensemble d’un même attribut au sein de l'entité.
- **Clé primaire** : Un numéro d’identification (ID) peut servir de clé primaire. Il s’agit de l’attribut unique qui identifie chaque enregistrement de manière distincte et qui permet d’établir une dépendance fonctionnelle.
- **Dépendance fonctionnelle élémentaire** : Si aucun autre attribut (ex. : C) n’intervient pour relier deux attributs (ex. : A et B), alors la dépendance est dite élémentaire.

## Correction du tableau

- **Types de données** : Pour les premiers modèles, il faut définir des types de données simples (ex. : texte alphabétique).
- **Numéro de client** : Exemple de dépendance fonctionnelle élémentaire (non calculé).
- **Notation** :
  - **E** : Type élémentaire (non calculé).
  - **C** : Type calculé (ex. : totaux).

## MCD : Modèle Conceptuel de Données

### Propriétés

- **Définition** : Informations de base d’une entité. Chaque propriété est définie par un nom et peut avoir un type et une longueur (pas toujours).
- **Note** : Au niveau conceptuel, on se concentre sur la définition des propriétés sans spécifier leur type.

### Entités

- **Définition** : Ensemble de propriétés qui décrivent un objet ou un élément du système d'information.
- **Identifiant** : Propriété particulière appelée « Identifiant », qui distingue chaque instance de l’entité. Toujours unique pour chaque entité dans un MCD. Indiqué par un soulignement dans le modèle.

### Relations

- **Définition** : Les entités sont reliées entre elles par des relations qui établissent des liens logiques entre elles.
- **Exemple** : Un client peut être associé à plusieurs commandes, mais chaque commande est liée à un seul client.

### Informations supplémentaires

- **Cardinalité** : Précise le nombre minimum et maximum d'occurrences possibles entre les entités (ex. : un client peut passer plusieurs
