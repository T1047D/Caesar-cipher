CryptoHub — Multi-Cipher & Password Toolkit

A responsive, browser-only toolkit built with HTML, CSS and vanilla JavaScript. Designed for GitHub Pages.


Features


Caesar, Base64 (UTF-8), ROT13, Atbash and Vigenère cipher

Encrypt/decrypt modes, copy, swap, reset and sample text

Password generator using crypto.getRandomValues() with configurable length and character sets

Password strength/entropy estimate

Text statistics, letter-frequency analysis and Caesar brute force

Local-only recent cipher history (browser localStorage)

Mobile responsive dark cybersecurity interface


Deploy on GitHub Pages


Download and unzip this project.

Open the cryptohub-pro folder.

Upload index.html and README.md to your GitHub repository root.

In GitHub, open Settings → Pages.

Select Deploy from a branch, choose main and / (root), then Save.

Open the published Pages URL.


Privacy & security notes


No backend, database, analytics, API or external dependency is used.

Passwords are generated locally with the browser's Web Crypto API and are not stored by this app.

Cipher history is stored only in this browser's localStorage. Clear it from the History tab or clear site data.

Classical ciphers are educational and are not secure encryption for sensitive data.

The password strength estimate is approximate; use a password manager and unique passwords.
