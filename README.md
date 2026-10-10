# merch-gallery

This repository only hosts an encrypted page. `index.html` is AES-256-GCM encrypted
(key derived with PBKDF2-SHA256, 600,000 iterations) and decrypts in the browser only
with the correct password. There is nothing readable here without it.

It is generated automatically; do not edit by hand.
