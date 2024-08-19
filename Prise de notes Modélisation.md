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

- **Cardinalité** : Précise le nombre minimum et maximum d'occurrences possibles entre les entités (ex. : un client peut passer plusieurs commande ne peut être passée que par un seul client).

- **Contraintes d'intégrité** : 
  - Assurent que les relations entre les entités respectent certaines règles.
  - Par exemple, une commande doit toujours être associée à un client existant pour maintenir l'intégrité des données.

---

### Notes supplémentaires

- **Importance de la modélisation** : 
  - La modélisation des données est cruciale pour structurer les informations de manière cohérente et éviter les redondances.
  - Elle permet également de clarifier les relations entre les différentes entités du système d’information.

- **Outils utilisés** : 
  - Les modèles conceptuels, comme le MCD, servent à visualiser et structurer les données avant leur implémentation dans une base de données.
  - Ces modèles facilitent la compréhension des dépendances et des relations entre les entités, et aident à définir les clés primaires et les contraintes d'intégrité.

- **Pratiques recommandées** :
  - Toujours vérifier les dépendances fonctionnelles pour éviter les anomalies lors de la mise à jour des données.
  - Documenter les relations et les contraintes dans le modèle pour garantir la cohérence et la clarté du système d’information.

---

