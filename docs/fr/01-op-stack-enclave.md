# 01 — OP Stack dans une enclave

`op-enclave` place des composants de derivation ou validation OP Stack dans une enclave AWS Nitro.
L enclave isole le calcul, tandis que l attestation permet a un tiers d identifier le code mesure.
Cette architecture ajoute une racine de confiance materielle sans remplacer les regles du protocole.
Le consommateur doit definir quelles mesures et versions il accepte.
Une attestation valide n implique pas une entree L1 correcte.
Source : [`README.md`](https://github.com/base/op-enclave/blob/main/README.md).

[Suite](02-attestation-et-politique.md)
