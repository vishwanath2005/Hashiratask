🔐 Shamir Secret Sharing – Secure Access Control
📘 Summary
This project demonstrates **Shamir’s Secret Sharing Algorithm**, used to securely split a secret (like a nuclear access code) among `N` people, requiring at least `K` to reconstruct it. It ensures that **no single person has full control**, enabling secure and collective decision-making.
🔧 What It Does
* Splits a secret using Shamir’s scheme.
* Takes shares in different number systems (binary, octal, hex, etc.).
* Converts all shares to base-10.
* Reconstructs the secret using **Lagrange interpolation**.
* Output = Original secret.
