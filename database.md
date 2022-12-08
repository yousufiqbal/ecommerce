# Tables

1. Categories
2. Products
3. Variants

4. Orders
5. Order Details
6. Returns

7. Guests
8. Guest Cart Items

9. Users
10. User Cart Items

11. Promos
12. Reviews

13. Admins
14. Admin Activities

## Categories

1. Id
2. Name
3. Url Name
4. Position
5. Created

## Brands

1. Id
2. Name
3. Url Name
4. Position
5. Created

## Products

1. Id
2. Brand Id (Optional)
3. Category Id (FK)
4. Name
5. Url Name
6. Description
7. Status
8. Created

## Variants

1. Id
2. Product Id (FK)
3. SKU
4. Barcode
5. Name
6. Url Name
7. Attributes
8. Stock
9. Cost
10. Status
11. Fair Limit (Optional)
12. Created

## Guests

1. Id
2. Name (Guest)
3. Created

## Guest Cart Items

1. Id
2. Guest Id (FK)
3. Variant Id (FK)
4. Quantity

# Users

1. Id
2. Other Id
3. Name
4. Email
5. Contact
6. Last Notificaiton Read
7. Last Order Read
8. Last Promo Read
9. Last Wallet Read
10. Created

## Addresses

1. Id
2. User Id
3. City
4. Address
5. Is Default
6. Created

## Wishlist

1. Id
2. Variant Id
3. 

## Cards

1. Id
2. User Id (FK)
3. Name on Card
4. Card Number
5. Expiry
6. Created

## Wallets

1. Id
2. User Id (FK)
3. Order Id (FK)
4. In
5. Out
6. Comment
7. Created

## Notifications

1. Id
2. User Id
3. Message
4. Status (read/unread)
5. Created

# Cart & Orders

## Cart Items

1. Id
2. User Id (FK)
3. Variant Id (FK)
4. Quantity

## Orders

1. Id
2. User Id (FK)
3. Promo Id (Optional)
5. Name (Hard)
6. Email (Hard)
7. Contact (Hard)
8. City (Hard)
9. Address (Hard)
10. Payment Method (card, cod)
11. Created

## Order Statuses

1. Id
2. Order Id (FK)
3. Status
4. Comment
5. Created

## Order Details

1. Id
2. Order Id (FK)
3. Variant Id (FK)
4. Quantity
5. Cost
6. Price

## Returns

1. Id
2. Order Id
3. Loss

## Promos

1. Id
2. User Id
3. Code
4. Max Discount
5. Percentage
6. Validity
7. Is Used
8. Created

## Reviews

1. Id
2. User Id (FK)
3. Product Id (FK)
4. Stars
5. Comment
6. Status (Approved, Pending, Rejected)
7. Created

## Admins

1. Id
2. First Name
3. Last Name
4. Email
5. Contact
6. Password
7. Created

## Admin Activities

1. Id
2. Admin Id
3. Summary (readable)
4. Detail (json, etc.)
5. Operation (create, update, delete, other)
6. Created

