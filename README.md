# WMS Dolibarr Multi-Filiales — Biopietra Group (cas client)

**Problème :** un groupe BTP avec dépôt central + chantiers perdait la trace de son
matériel entre 7 instances Dolibarr séparées. Transferts papier, stocks faux,
aucune consolidation.

**Solution livrée :** hub WMS central + module Dolibarr sur mesure **`wmsbon`**.
- Bons de transfert internes, **PDF A5 paysage avec QR code de retour**, double signature
- Synchronisation des stocks filiale → hub (API REST, isolation SQL stricte, loopback)
- 7 instances Dolibarr hébergées (VM Virtualmin), base consolidée temps réel
- **Déployé et actif depuis août 2026** (hub + démo)

**Stack :** PHP · Dolibarr ERP (module custom) · MariaDB · API REST · QR · Virtualmin

> Code privé (données client) — démo et code sur demande / NDA.

**Vous gérez stocks multi-sites ?** Modules Dolibarr sur mesure, intégrations, montées de version.
**Mohamed Maache** — Tech Lead, 26 ans d'expérience · [Malt](https://www.malt.fr/profile/mohamedmaache3) · [LinkedIn](https://www.linkedin.com/in/mohamed-maache-538828239/)
