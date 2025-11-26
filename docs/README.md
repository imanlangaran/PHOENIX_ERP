# Overview

This project consists of three main modules:

1. **Wallet** – Each customer has a personal wallet that supports deposits and withdrawals.  
2. **Accounting** – The system records all financial transactions, including income and payments.  
3. **Inventory** – The store manages a list of products available for sale.

---

## Project Phases

1. **Authentication & Authorization**  
   The first phase focuses on implementing a secure authentication and authorization system.
   for now, the Authentication part is implemented with a minimal setup.
   there is more TODO:
      1. use admin plugin in better auth. it offers role pased authorization. role are admin (super user) - staff (user of the system - have limited access that super user - have access to staff's dashboard) - customer (only have access to customer dashboard)

2. **Inventory**
   In this phase I implement the inventory system which in summary a staff user adds the shopping items into the system and manages them.
   what a staff user can do:
   - CRUD suppliers
   - CRUD categories
   - CRUD products - each product can have version - CRUD product version
   - CRUD purchase order and purchase order items
   - Inventory movements


<!-- https://chatgpt.com/c/69158ce1-01a4-8326-80d3-cd02efe67598 -->

