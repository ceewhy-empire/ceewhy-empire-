CEEWHY EMPIRE — CLIENT CHECKOUT WEBSITE

This version adds:
- Design packages with prices
- Package selection
- Client name/email/phone
- Project deadline
- Full project brief
- Reference/extra notes
- Paystack checkout integration
- Payment-success reference sent to WhatsApp
- Mobile responsive luxury design

IMPORTANT PAYMENT SETUP
1. Create/verify your Paystack business account.
2. Open config.js.
3. Replace YOUR_PAYSTACK_PUBLIC_KEY with your Paystack PUBLIC key.
4. Use a pk_test_ key while testing.
5. After testing, replace it with your pk_live_ key for real payments.
6. NEVER place an sk_ secret key in config.js or index.html.

SECURITY NOTE
This frontend uses Paystack's public key only. For production-grade order fulfillment, payment verification should happen on a secure server/webhook before treating an order as paid. Do not rely only on the browser success callback.

EDITING PRICES
Open index.html and edit the PACKAGES array near the bottom. Prices are currently:
Premium Flyer — ₦5,000
Event / Birthday Design — ₦7,000
Social Media Pack — ₦10,000
Logo Design — ₦25,000
Brand Identity Starter — ₦50,000
Business Design Pack — ₦15,000

These are starter prices, not externally verified market prices. Change them to your actual Ceewhy Empire prices before going live.
