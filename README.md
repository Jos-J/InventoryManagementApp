# 📦 InventoryManagementApp

The **InventoryManagementApp** is a simple inventory management system for tracking and checking out items such as books, equipment, or other resources.  
It provides a **checkout page** for borrowing items, while all inventory data is stored and managed directly in a SQL database.

---

## ✨ Features
- Checkout page  for borrowing items  
- Return functionality to update item availability  
- Items managed directly via SQL  
- Backend powered by **Java (Spring Boot + Maven)**  
- Frontend built with **HTML, CSS, and JavaScript**  
- Includes images for logos, banners, and icons  

---

## 📂 Project Structure


```
InventoryManagementApp/
├── backend/
│   ├── src/main/java/com/inventorymanagementapp/
│   │   ├── controller/            # REST controllers (CheckoutController, AuthController)
│   │   ├── model/                 # Entities (Item, Loan, User - optional)
│   │   ├── repository/            # Data access (Spring Data JPA repositories)
│   │   └── service/               # Business logic (CheckoutService, UserService)
│   ├── src/main/resources/
│   │   └── application.properties   # Database + server configuration
│   └── pom.xml                      # Maven configuration                    
│
├── frontend/
│   ├── assets/
│   │   ├── css/
│   │   │   └── style.css
│   │   └── js/
│   │       └── main.js
│   ├── images/
│   │   ├── logo.png
│   │   ├── banner.jpg
│   │   └── icon-checkout.png
│   ├── pages/
│   │   └── checkout.html           
│   └── index.html 
│
├── database/
│   ├── schema.sql                  
│   └── seed.sql
│
└── README.md
                 

```

## License
![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)


Copyright (c) 2025 Jos

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.