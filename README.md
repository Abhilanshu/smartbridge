TECHNICAL ARCHITECTURE
Frontend (User Interface):
├─ User Authentication
│   ├─ User Registration Page
│   ├─ User Login Page
│   └─ Logout Functionality
│
├─ Product Interface
│   ├─ View Products
│   ├─ Product Details Page
│   └─ Search & Categories
│
├─ Cart Interface
│   ├─ Add to Cart
│   ├─ Remove from Cart
│   └─ View Cart Items
│
├─ Order Interface
│   ├─ Order Details Page
│   ├─ Address Input
│   └─ Payment Selection
│
├─ User Profile
│   ├─ View Profile
│   ├─ Update Details
│   └─ View Orders
│
└─ Admin Dashboard
    ├─ Admin Login
    ├─ Manage Products
    ├─ Manage Categories
    └─ View Orders


    Backend (API Services):
├─ User APIs
│   ├─ Register User
│   ├─ Login User
│   ├─ Get User Details
│   └─ Update User Profile
│
├─ Product APIs
│   ├─ Add Product
│   ├─ Update Product
│   ├─ Delete Product
│   └─ Get Products
│
├─ Cart APIs
│   ├─ Add to Cart
│   ├─ Remove from Cart
│   └─ Get Cart Items
│
├─ Order APIs
│   ├─ Create Order
│   ├─ Get Orders
│   └─ Order Status
│
├─ Admin APIs
│   ├─ Admin Authentication
│   ├─ Manage Products
│   ├─ Manage Categories
│   └─ Manage Orders
│
└─ Server Functions
    ├─ Request Handling
    ├─ Data Validation
    └─ Business Logic
Database (MongoDB):
├─ Users Collection
│   ├─ user_id
│   ├─ name
│   ├─ email
│   ├─ password
│   └─ address
│
├─ Products Collection
│   ├─ product_id
│   ├─ product_name
│   ├─ description
│   ├─ price
│   └─ category
│
├─ Cart Collection
│   ├─ cart_id
│   ├─ user_id
│   ├─ product_id
│   └─ quantity
│
└─ Orders Collection
    ├─ order_id
    ├─ user_id
    ├─ products
    ├─ total_amount
    └─ order_status
