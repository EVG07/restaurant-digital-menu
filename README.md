# BRASA — Restaurant Digital Menu

Responsive restaurant menu demonstration built with HTML, CSS and vanilla JavaScript.

## Features
- Product catalog with categories
- Product search
- Shopping cart with quantity controls and estimated total
- WhatsApp order-message handoff
- QR code generated from the published URL
- Responsive layout for mobile and desktop

## Run locally
Open `index.html` in a modern browser. Some external assets (Google Fonts, QRCode.js and remote imagery) require internet access.

## Before client delivery
1. Replace `WHATSAPP_NUMBER` in `index.html` with the restaurant's number in international digits-only format.
2. Replace demo business details, menu items, prices, hours and imagery with client-approved content.
3. Publish over HTTPS.
4. Test the WhatsApp handoff and QR code on a phone.
5. Confirm the order, delivery and payment workflow with the client.

## Important limitations
- Demo products, prices, address, hours and phone are placeholders.
- The WhatsApp button opens a prefilled message; this project does not process online payments.
- The QR code points to the current public URL and requires the site to be hosted.
- Images and some libraries are loaded from external services.

## Stack
HTML5 · CSS3 · JavaScript
