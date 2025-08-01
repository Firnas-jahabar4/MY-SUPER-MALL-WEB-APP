# Test Cases – Super Mall App

### TC01 – Register New User
- Input: valid email + password
- Expected: Success, redirect to login

### TC02 – Login
- Input: registered credentials
- Expected: Redirect to dashboard

### TC03 – Add Shop
- Input: Shop info
- Expected: Saved in Firestore, shows in list

### TC04 – Add Offer
- Input: Title, description, shop
- Expected: Appears in offer list

### TC05 – Compare Products
- Input: Add two products, filter by category
- Expected: Products listed with correct prices/features
