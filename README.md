# Chinook — Exercices SQL (MySQL Workbench)

## 📷 Captures (MySQL Workbench)
![Tables Chinook](docs/screenshots/schemas.png)
![Résultat - Top Tracks](docs/screenshots/top_tracks.png)
Projet SQL sur la base Chinook (MySQL).  
Objectif : importer Chinook puis résoudre 26 exercices (JOIN, GROUP BY, agrégations, analyses ventes).

## Prérequis
- MySQL Server (8.x+)
- MySQL Workbench

## Import de la base Chinook (Workbench)
1. Ouvrir `Chinook_MySql.sql` dans MySQL Workbench
2. Si erreur 1064 au début : supprimer le 1er caractère invisible (BOM) puis relancer
3. Exécuter tout le script (Ctrl+A puis ⚡)

## Vérifications
```sql
USE Chinook;
SHOW TABLES;
SELECT COUNT(*) AS customers_count FROM Customer;
SELECT COUNT(*) AS invoices_count  FROM Invoice;
SELECT COUNT(*) AS invoice_lines_count FROM InvoiceLine;
```
👤 **Auteur** : Arsène  
📅 **Année** : 2026
