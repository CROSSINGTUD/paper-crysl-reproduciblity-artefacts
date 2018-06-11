

# RQ1:

Manually analyzed apps: [List of apps](RQ1/list.pdf)

# RQ2 + RQ3:
CogniCryptSAST Rule Set: [Full Rule Set](https://github.com/CROSSINGTUD/Crypto-API-Rules)

# RQ4:
Paper ['An empirical study of cryptographic misuse in android applications'](http://dl.acm.org/citation.cfm?id=2516693) by Egele et al.

Original CryptoLint Rules:

Rule 1: Do not use ECB mode for encryption.

Rule 2: Do not use a non-random IV for CBC encryption.

Rule 3: Do not use constant encryption keys.

Rule 4: Do not use constant salts for PBE.

Rule 5: Do not use fewer than 1,000 iterations for PBE.

Rule 6: Do not use static seeds to seed SecureRandom().

CogniCrypt<sub>SAST</sub> CryptoLint Rule Set: [CryptoLint Rule Set in CrySL](https://github.com/CROSSINGTUD/Crypto-API-Rules/tree/Egele13)
