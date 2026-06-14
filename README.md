# Plateforme E-commerce – CAMPOST (Cameroon Postal Services)

Développement, maintenance et assurance qualité d'une plateforme e-commerce nationale pour CAMPOST, conçue pour gérer un large catalogue de produits et un fort volume de trafic.

---

## 📝 Contexte du Projet

Ce projet a été mené au sein d'ITGStore Consulting pour fournir à CAMPOST, l'opérateur postal national du Cameroun, une solution e-commerce moderne et robuste. Mon rôle était double : Développeur Full Stack pour construire et intégrer les fonctionnalités, et Analyste QA pour garantir la performance, la sécurité et la fiabilité de la plateforme avant son déploiement.

> **Note de confidentialité :** Ce projet étant une propriété intellectuelle de l'entreprise et de son client, le code source est confidentiel. Ce document sert de présentation détaillée de l'architecture, des défis techniques et de mes contributions.

---

## ✨ Fonctionnalités Clés

*   **Catalogue de Produits Complet :** Gestion de milliers de produits avec des catégories, des attributs personnalisés et des filtres.
*   **Moteur de Recherche Performant :** Recherche rapide et pertinente grâce à l'intégration d'**Elasticsearch**.
*   **Tunnel d'Achat Optimisé :** Processus de commande fluide, du panier au paiement.
*   **Intégration de Paiement National :** Connexion à l'agrégateur **CAMPOST Payment** pour permettre les paiements par Mobile Money (MTN, Orange).
*   **Synchronisation Mobile :** Une API REST assure la communication en temps réel entre la plateforme web et l'application mobile dédiée.
*   **Panel d'Administration Complet (Magento Backend) :** Gestion des commandes, des clients, des produits et des promotions, etc...

---

## 💻 Technologies & Outils

| Catégorie             | Technologies / Outils                                      |
| --------------------- | ---------------------------------------------------------- |
| **E-commerce & Backend** | **Magento 2**, PHP, XML                                    |
| **Base de Données**   | **MySQL**, SQL                                             |
| **Recherche**         | **Elasticsearch**                                          |
| **Infrastructure**    | **Nginx**, **Varnish Cache**, Ubuntu, Déploiement Cloud Privé |
| **Tests de Performance** | **JMeter**                                                 |
| **Tests de Sécurité** | **OWASP ZAP**, **SQLmap**                                  |
| **Outils**            | Git, GitLab, Insomnia, **PageSpeed Insights**              |

---

## 🚀 Mes Contributions (Double Rôle)

### En tant que Développeur Full Stack :

1.  **Développement d'API REST :** Conception et développement des endpoints de l'API REST pour permettre à l'application mobile de consommer les données du site (produits, commandes, utilisateurs) de manière sécurisée.
2.  **Intégration du Gateway de Paiement :** Implémentation complète de l'agrégateur **CAMPOST Payment**, en gérant le flux de paiement, les callbacks de confirmation et la gestion des erreurs.
3.  **Maintenance et Évolution :** Développement de nouvelles fonctionnalités et maintenance corrective sur la plateforme Magento.
4.  **Optimisation des Performances :** Analyse des performances avec **PageSpeed Insights** et collaboration à la configuration du cache **Varnish** pour réduire les temps de chargement.
5.  **Administration de Base de Données :** Tâches d'administration courantes sur la base de données MySQL pour assurer son intégrité et ses performances.

### En tant qu'Analyste QA & Sécurité :

1.  **Planification des Tests :** Analyse de la note de cadrage et rédaction des plans de tests fonctionnels et de sécurité.
2.  **Tests de Charge et de Stress :** Utilisation de **JMeter** pour simuler un grand nombre d'utilisateurs et identifier les goulots d'étranglement de la plateforme.
3.  **Audits de Sécurité :** Exécution de scans de vulnérabilités avec **OWASP ZAP** et réalisation de tests d'injection SQL de base avec **SQLmap** pour identifier et aider à corriger les failles de sécurité.
4.  **Documentation :** Rédaction de la documentation d'utilisation des API pour l'équipe de développement mobile et des rapports de tests pour les chefs de projet.

----

## Auteur

*   **Idriss Cabrel MBIAPO NZEPA**
*   [Profil LinkedIn](https://www.linkedin.com/in/idriss-cabrel-mbiapo-nzepa-b1222a363)
*   [Profil GitHub](https://github.com/idriss-mbiapo/)
