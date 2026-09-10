# 03 — Derivation et provenance des entrees

Le calcul enclave reste correct seulement si les donnees L1, configurations et points de depart sont authentiques.
La derivation doit conserver ordre, finalite et identite de chaine.
Les entrees non verifiees peuvent conduire une enclave saine a attester un mauvais contexte.
Chaque sortie doit etre liee a hauteur, hash, version et configuration.
La disponibilite de l enclave reste distincte de son integrite.
Source : [`src`](https://github.com/base/op-enclave/tree/main/src).

[Suite](04-checklist-et-limites.md)
