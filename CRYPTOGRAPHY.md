# Cryptography

A scheme will be assumed to be cryptographically secure, if it provides more than 100-bits (~10^30) of post-quantum security level.

Quantum computers can reduce the security of any algorithm with [Grover's algorithm](https://en.wikipedia.org/wiki/Grover%27s_algorithm).
This reduces the domain from `N` to `sqrt(N)` or in other words halves the key size.

Not supporting insecure schemes makes downgrade attacks impossible, below should only be encryption methods that are considered to be secure.


## Symmetric Encryption

### AES-256

**Key size:** 256 bit

**Post-Quantum:** 128 bit

**Best known attack:** 254.3 bit (Biclique attack, not PQC)


## Asymmetric Encryption

### TBA


## Disk encryption

Look out for watermarking attacks, when hidden containers are desired.


## Side Channel Attacks

### Timing based attacks

Archiving true constant time and leaving no side effects is difficult.
Below are a list of possible solutions:

- Hardware support (e.g. AES-NI)
- Branch-less code and constant memory access patterns


## Scrambled thoughts

- Forward secrecy by default
- Post quantum cryptographic algorithm
- Cache bleed
