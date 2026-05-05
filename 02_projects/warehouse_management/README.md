# Lightweight Warehouse Management System (V1.0)

## Business Context
Drawing from my previous experience at Amazon and Huawei, I understand that real-time inventory tracking and accurate valuation are the lifelines of any e-commerce or supply chain business. This project is a lightweight simulation of a warehouse management backend.

## Current Features (V1.0)
Currently, this script runs in-memory using core Python data structures (Lists and Dictionaries). It supports:
- **Inventory Query:** Loops through the current stock and prints a formatted inventory list.
- **Inbound Storage:** Appends new product data (ID, name, price, stock) into the warehouse system.
- **Valuation Calculation:** Automatically calculates the total asset value of the entire warehouse by multiplying individual stock levels by their unit prices.

## Future Roadmap
This is just the MVP. In the coming 100 days, I plan to upgrade this project to a professional standard:
- [ ] **V2.0:** Replace in-memory lists with a **MySQL / PostgreSQL database** for persistent data storage.
- [ ] **V3.0:** Refactor the code using Object-Oriented Programming (OOP) principles.
- [ ] **V4.0:** Deploy the database and the Python script onto **AWS (EC2 & RDS)** to make it a cloud-based application.
