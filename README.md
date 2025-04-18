# 📦 Application de Gestion des Produits avec Spring Boot

Ce projet est un exemple de gestion des produits avec **Spring Boot**, utilisant **Spring Data JPA**, **H2 Database** pour le développement, et une migration vers **MySQL**. Le projet inclut la gestion des produits, et des étapes de configuration comme l'utilisation de **Lombok** pour réduire le code boilerplate.

## 🧰 Technologies utilisées

- **Java 17+**
- **Spring Boot 2.x**
- **Spring Data JPA**
- **Lombok**
- **H2 Database** (en mémoire pour le développement)
- **MySQL** (pour la production)
- **Maven** pour la gestion des dépendances

---

## 📦 Configuration du projet

### Étape 1 : Installation d'IntelliJ Ultimate

1. Télécharger et installer **IntelliJ Ultimate** depuis [le site officiel](https://www.jetbrains.com/idea/download/).
2. Lancer IntelliJ et configurer le projet.

### Étape 2 : Création du projet Spring Initializer

1. Créer un nouveau projet Spring Boot via **Spring Initializer**.
2. Sélectionner les dépendances suivantes :
   - **JPA**
   - **H2 Database**
   - **Spring Web**
   - **Lombok**

### Étape 3 : Configuration de Lombok dans le fichier `pom.xml`

Pour assurer que Lombok fonctionne avec les dernières versions de Java, ajouter les configurations suivantes dans le fichier `pom.xml` :

#### Dépendance Lombok :
```xml
<dependency>
    <groupId>org.projectlombok</groupId>
    <artifactId>lombok</artifactId>
    <optional>true</optional>
    <version>1.18.34</version> <!-- Ajouter cette ligne manuellement -->
</dependency>

