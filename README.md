Here is the English version of your README.md. I have refined the terminology to match standard industry documentation.
📚 Library Management System (Java)

This project is a Java-based console application designed to manage a library inventory. It serves as a practical implementation of fundamental Object-Oriented Programming (OOP) concepts.
🚀 Features

    Multi-type Product Management: Full support for Books and Magazines.

    Sales & Availability: Dedicated interface for sellable items.

    Inventory Operations: Add, remove, and search for products within the library.

    Error Handling: Robust use of custom exceptions for handling missing items.

🏗️ Project Architecture

The project is structured around several key classes and interfaces:
Core Classes

    Produit.java (Abstract Class): The base class for all library items (Title, ID, Price).

    Livre.java: Extends Produit, adding specific attributes such as Author and ISBN.

    Magazine.java: Extends Produit for periodical publications.

    Librairie.java: The "Core" class managing the product collection (ArrayList) and containing the business logic.

Interfaces & Exceptions

    Vendable.java: Interface defining methods related to product sales.

    ProduitIntrouvableException.java: Custom exception thrown when a product search fails.
    📊 Applied OOP Concepts

    Inheritance: Livre and Magazine inherit from the Produit base class.

    Abstraction: Use of an abstract parent class to eliminate code redundancy.

    Interfaces: Implementation of a sales contract via Vendable.

    Encapsulation: Data protection through private attributes and public getters/setters.

    Collection Framework: Use of ArrayList for dynamic data manipulation.
