# NASCO Android App — Version 2

This version extends the NASCO starter with:
- Product catalog and categories
- Cart quantity handling
- Checkout/order request form
- Guest checkout
- Delivery address and phone fields
- Order status model
- Admin dashboard structure
- Customer messaging structure
- Firebase-ready repository/service interfaces
- M-Pesa-ready payment service interface
- Call and map intents
- Local sample product data

## Before production
1. Create a Firebase Android project.
2. Add `google-services.json` to `app/`.
3. Enable Authentication, Firestore and Cloud Messaging.
4. Add a secure server/Cloud Function for M-Pesa STK Push.
5. Replace sample products with Firestore data.
6. Add your real NASCO phone number and delivery locations.
7. Add a real product image/logo asset.
8. Test orders, payments, messaging and permissions before Play Store release.

Never put M-Pesa consumer keys or secret credentials directly inside the Android app.
