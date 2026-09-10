# 02 — Attestation et politique

L attestation lie mesures, cle publique et metadonnees a une signature AWS.
Le verificateur doit aussi imposer fraicheur, challenge, chaine et politique PCR.
Les rotations de version exigent une transition explicite entre mesures acceptees.
Une liste trop large annule la valeur de l attestation sans casser sa signature.
La politique doit etre versionnee et observable onchain ou dans la configuration.
Source : [`docs`](https://github.com/base/op-enclave/tree/main/docs).

[Suite](03-derivation-et-entrees.md)
