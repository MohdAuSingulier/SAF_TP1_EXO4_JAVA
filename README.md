# SAF_TP1_EXO4_JAVA

## Gestion de magasin en Java

Projet d'apprentissage de la programmation orientée objet.
Le programme simule un magasin en console.

## Fonctionnalités

- Afficher les produits disponibles.
- Ajouter un produit au panier.
- Afficher le panier et son total.
- Passer une commande.
- Quitter le programme.

La classe Panier propose également une méthode de suppression,
sans option dédiée dans le menu.

## Organisation

Les six classes appartiennent au package `gestionMagasin` :

- `Produit` : informations d'un produit.
- `Client` : informations du client.
- `Panier` : produits sélectionnés et calcul du total.
- `Commande` : client, produits commandés et total.
- `Magasin` : catalogue et recherche par nom.
- `Main` : création des objets et menu interactif.

## Exécution

Ouvrir le projet dans un IDE Java et exécuter `Main.java`.

Saisir un nombre pour le menu et le nom exact du produit :
`Ordinateur HP`, `PlayStation 5` ou `Casque Auditif`.

## Notions utilisées

Classes, objets, constructeurs, getters, setters, ArrayList,
Scanner, boucles, conditions et switch.

## Limites

Les prix sont en euros entiers. Chaque ajout représente une unité.
Le stock n'est pas diminué après une commande.
Le menu attend une saisie numérique.

## Auteur

Mohamed_SF
