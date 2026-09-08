# gpu-pricing-desk-site

Serves https://shadawgk.github.io/gpu-pricing-desk-site/

This repo holds **only the encrypted output** of the private `gpu-pricing-desk` repo: two HTML files
whose content is AES-256 ciphertext (staticrypt, PBKDF2) that the browser decrypts with the desk
passphrase. No plaintext is committed here and no source lives here. The daily job overwrites both
files each morning, so history in this repo carries no information.
