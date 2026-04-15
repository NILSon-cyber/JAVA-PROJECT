📚 Système de Gestion de Librairie (Java)

Ce projet est une application Java console permettant de gérer un inventaire de produits au sein d'une librairie. Il met en pratique les concepts fondamentaux de la Programmation Orientée Objet (POO).
🚀 Fonctionnalités

    Gestion de produits multi-types : Support des Livres et des Magazines.

    Vente et Disponibilité : Interface dédiée pour les articles vendables.

    Recherche et Gestion : Ajout, suppression et recherche de produits dans la librairie.

    Gestion d'Erreurs : Utilisation d'exceptions personnalisées pour les produits non trouvés.

🏗️ Architecture du Projet

Le projet est structuré autour de plusieurs classes et interfaces clés :
Classes Principales

    Produit.java (Classe abstraite) : La base de tous les articles de la librairie (Titre, ID, Prix).

    Livre.java : Extension de Produit, incluant des attributs spécifiques comme l'auteur et l'ISBN.

    Magazine.java : Extension de Produit pour les publications périodiques.

    Librairie.java : La classe "Cœur" qui gère la collection de produits (ArrayList) et contient la logique métier.

Interfaces & Exceptions

    Vendable.java : Interface définissant les méthodes liées à la vente d'un produit.

    ProduitIntrouvableException.java : Exception personnalisée levée lorsqu'une recherche de produit échoue.
    Concepts POO Appliqués

    Héritage : Livre et Magazine héritent de Produit.

    Abstraction : Utilisation d'une classe parente abstraite pour factoriser le code.

    Interfaces : Contrat de vente via Vendable.

    Encapsulation : Utilisation de getters/setters pour sécuriser les données.

    Gestion des Collections : Utilisation de ArrayList pour manipuler les données dynamiquement.
