# ONLINE-STORE
# OnlineStore-Database

A MySQL relational database for an Online Store, containing tables, relationships, and sample data.

## 📋 Tables

- `customers`: Customer info (Name, Email, Phone)
- `products`: Product details (Name, Price, Stock)
- `orders`: Order records linked to customers
- `orderdetails`: Items in each order (many-to-many)
- `payments`: Payment information for orders

## 🔗 Relationships

- One customer → many orders  
- One order → many items  
- One order → one payment  

## 💾 How to Use

1. Import database:
   ```bash
   mysql -u root -p < OnlineStore.sql
