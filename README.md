# Chinook — Exercices SQL (MySQL Workbench)

## 📷 Captures (MySQL Workbench)
<img width="736" height="500" alt="agent vente" src="https://github.com/user-attachments/assets/5ea310c2-5ecf-48cc-bffd-8efc74e5720e" />
<img width="736" height="500" alt="client noamericans" src="https://github.com/user-attachments/assets/d7452829-ed95-453d-b33b-85ba0f68d918" />
<img width="736" height="500" alt="exemple1" src="https://github.com/user-attachments/assets/daf2498b-8b99-4122-891b-a7c1a6efb30d" />


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
