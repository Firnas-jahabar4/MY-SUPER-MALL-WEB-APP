# Low Level Design – Super Mall Web Application

## 🔸 Login & Auth
- Firebase Authentication with Email/Password
- Auth state checked on each protected page

## 🔸 Shop Module
- CRUD operations using Firestore `shops` collection
- Fields: name, owner, category, floor, createdAt

## 🔸 Offers Module
- Linked with `shopId`
- Firestore `offers` collection
- Add/delete offers for selected shop

## 🔸 Products Module
- Linked with `shopId`
- Firestore `products` collection
- Compare and filter by category/shop

## 🔸 Category & Floor
- Simple Firestore collection or string fields
- Filter frontend using dropdown/text

## 🔸 Navigation
- Dashboard with links to all modules

## 🔸 Logging
- Console-based action logs
- Can be extended with Firebase Analytics or log collection
