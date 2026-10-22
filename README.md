# Ksenia — client preview

Password-protected landing page preview. Open `index.html` over HTTPS in a current browser.

The page content is encrypted with AES-256-GCM. The key is derived from the visitor's password using PBKDF2-HMAC-SHA-256 (600,000 iterations and a random salt). Neither the password nor the plaintext source is stored in this repository.

This is a static preview gate, not server-side authentication or copy protection. Downloaded encrypted content permits offline password guessing. Anyone who knows the password can inspect and save the decrypted page. Refreshing the page locks the preview again; the application does not persist the password or key.

Prices are illustrative and must be confirmed before commercial launch. Photography in this preview comes from supplied portfolio screenshots.

Source code and visual materials are not offered under an open-source licence.
