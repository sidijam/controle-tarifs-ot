# Contrôle Tarifs OT Pro

Application de contrôle mensuel des nouveaux tarifs (feuilles CB et FH) par rapport aux Ordres de travail clôturés — DDEP_DSE-SROP.

**Accès :** https://sidijam.github.io/controle-tarifs-ot/

- Le fichier Excel chargé est lu dans le navigateur de l'utilisateur ; il n'est envoyé nulle part.
- Décisions et historique sont conservés dans le navigateur de chaque poste.
- Exports : classeur Excel mis en forme et rapport PowerPoint.

Règle de contrôle : montant facturé attendu = REDEVENCE_FORMULE − DISCOUNT, à comparer à la REDEVANCE facturée. Les refontes (upgrade avec baisse de tarif, discount à 0, ancienne redevance supérieure à la formule) sont conformes.
