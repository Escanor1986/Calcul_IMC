# Application de Calcul d'Indice de Masse Corporelle (IMC)

Ce projet est une application web simple permettant de calculer l'Indice de Masse Corporelle (IMC) d'un utilisateur en fonction de sa taille et de son poids.

## Fonctionnalités

- Calcul de l'IMC en utilisant la formule : IMC = poids (kg) / (taille (m) * taille (m)).
- Affichage du résultat de l'IMC avec une classification en fonction des données de l'OMS.
- Gestion des erreurs pour les entrées invalides ou manquantes.

## Utilisation

1. Cloner ce dépôt sur votre machine locale.
2. Ouvrir le fichier `index.html` dans votre navigateur web.
3. Entrer votre taille en centimètres et votre poids en kilogrammes dans les champs prévus à cet effet.
4. Cliquer sur le bouton "Calculer un IMC !" pour obtenir votre résultat.

## Classification de l'IMC

L'IMC est classé en plusieurs catégories en fonction de ses valeurs, selon les critères de l'Organisation Mondiale de la Santé (OMS). Voici les classifications utilisées dans cette application :

- **Maigreur** : IMC < 18.5
- **Bonne santé** : 18.5 <= IMC < 25
- **Surpoids** : 25 <= IMC < 30
- **Obésité modérée** : 30 <= IMC < 35
- **Obésité sévère** : 35 <= IMC < 40
- **Obésité morbide** : IMC >= 40

## Auteur

Ce projet a été développé par [Escanor1986].

## Licence

Ce projet est sous licence [MIT](LICENSE).
