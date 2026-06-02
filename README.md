# ExpertAudit HACCP — Application d'audit hygiène alimentaire multi-secteurs

Application web d'audit HACCP basée sur les Guides de Bonnes Pratiques d'Hygiène (GBPH) officiels validés par le ministère de l'Agriculture français.

🔗 **Application en ligne :** https://[votre-nom].github.io/haccp-audit/

---

## Secteurs couverts

| Secteur | Guide de référence | Critères |
|---|---|---|
| 🍽 Restauration Traditionnelle | GBPH Restaurateur — CGAD, nov. 2015 | 44 |
| 🍔 Restauration Rapide | GBPH SNARR 2024 | 32 |
| 🥖 Boulangerie / Pâtisserie | GBPH Boulangerie Artisan | 43 |
| 🥩 Boucherie / Charcuterie | GBPH Boucher — CFBCT | 43 |

**Total : 162 critères d'audit**

---

## Fonctionnalités

- ✅ **Audit multi-secteurs** — questions adaptées selon le type d'établissement
- ✅ **Score pondéré** — Critique ×3 / Important ×2 / Standard ×1
- ✅ **Option N/A** — critères non applicables exclus du score
- ✅ **Notes par critère** — observations détaillées
- ✅ **Rapport complet** — avec recommandations correctives automatiques
- ✅ **Signatures** — auditeur et responsable (souris PC + tactile mobile)
- ✅ **Historique** — sauvegarde des 25 derniers audits (localStorage)
- ✅ **Export PDF** — rapport et audit complet
- ✅ **100% offline** — aucune dépendance externe, fonctionne sans connexion
- ✅ **Responsive** — PC, tablette et smartphone (iOS Safari + Android)

---

## Base réglementaire

- Règlement CE n° 852/2004 — Hygiène des denrées alimentaires
- Règlement CE n° 853/2004 — Denrées d'origine animale
- Règlement CE n° 178/2002 — Traçabilité (Food Law)
- Règlement UE n° 1169/2011 — Information consommateurs / Allergènes
- Règlement CE n° 2073/2005 — Critères microbiologiques
- Arrêté du 21/12/2009 — Températures de conservation
- Arrêté du 08/10/2013 — Refroidissement rapide
- Code rural L.233-4 — Formation hygiène alimentaire obligatoire

---

## Utilisation

1. Ouvrir `index.html` dans un navigateur (Chrome, Edge, Safari, Firefox)
2. Sélectionner le **secteur d'activité**
3. Remplir les **informations de l'établissement**
4. Évaluer chaque critère :
   - **A — Conforme** ✓
   - **B — À améliorer** ⚠
   - **C — Non conforme** ✗
   - **N/A — Non applicable** ○
5. Ajouter des **notes** d'observation si nécessaire
6. **Signer** (auditeur + responsable)
7. Générer le **rapport** avec recommandations
8. **Sauvegarder** ou **exporter en PDF**

---

## Structure du projet

```
haccp-audit/
├── index.html        # Application complète (HTML + CSS + JS)
├── README.md         # Ce fichier
├── INSTALLATION.md   # Guide de déploiement GitHub Pages
├── LICENSE           # Licence MIT
└── .gitignore        # Fichiers ignorés par Git
```

---

## Licence

Outil développé pour les auditeurs en hygiène alimentaire.
Les GBPH sont la propriété de leurs organisations professionnelles respectives.

*ExpertAudit HACCP — Version mars 2026*
