# E-Commerce System Case Study

## Problem Statement
Design an object-oriented e-commerce system that enables customers to browse products, add them to a shopping cart, place orders, and track order status. The system should accommodate different product categories, manage inventory, process payments, and generate invoices.

## System Requirements
1. **User Management**:
   - Store user information (name, email, billing/shipping addresses)
   - Support different user roles (Customer, Admin, Guest)
   - Track user purchase history

2. **Product Catalog**:
   - Organize products in categories and subcategories
   - Support different product types (physical, digital, subscription)
   - Track product inventory and availability
   - Handle product attributes (size, color, weight, etc.)

3. **Shopping Cart & Order Processing**:
   - Allow adding/removing products from cart
   - Apply discounts and coupons
   - Process payments through various methods
   - Generate order confirmations and invoices

4. **Inventory Management**:
   - Track stock levels for products
   - Support restocking and inventory adjustments
   - Notify when products fall below threshold

5. **Payment Processing**:
   - Support multiple payment methods
   - Handle payment status (pending, completed, failed)
   - Process refunds when necessary

## Identify Classes and Relationships

**User-related Classes:**

**Product-related Classes:**

**Order-related Classes:**


## Key OOP Concepts to Identify

1. **Inheritance**: User → Customer/Admin, Product → PhysicalProduct/DigitalProduct
2. **Encapsulation**: Private attributes with getter/setter methods
3. **Polymorphism**: Different product types can be handled uniformly
4. **Abstraction**: Base classes define common interfaces
5. **Composition**: Order contains OrderItems, User has Addresses
6. **Aggregation**: ProductCategory contains Products
