# S06 – MODIFICATIONS À APPORTER AUX FICHIERS EXISTANTS

---

## 06_deroule.md → 2 MODIFICATIONS

### Modification 1 : ajouter le bloc format pédagogique FE3
Après la section `## 🧠 Notions du référentiel mobilisées`, ajouter :

```markdown
---

## 📐 Format pédagogique : Fiche élève à 3 niveaux (FE3)

La fiche élève propose un tronc commun (Travaux 1 à 3) suivi d'un TD différencié à 3 niveaux portant sur l'analyse de formulations lavantes réelles.

| Niveau | Public cible | Caractéristiques |
|--------|-------------|-----------------|
| N1 – Guidé | Étudiants en difficulté | Questions décomposées, cases à cocher, textes à trous sur le gel douche |
| N2 – Standard | Majorité de la classe | Comparaison gel douche / shampooing bébé, rédaction argumentée |
| N3 – Expert | Étudiants autonomes | Comparaison de 3 formules (corps/bébé/visage), argumentation E2 |

**Stratégie de circulation** : priorité N1 pendant le TD. N3 en autonomie.
```

### Modification 2 : remplacer la Phase 4 pour refléter la différenciation
Remplacer tout le contenu de `## 🔹 Phase 4 – TD : familles de tensioactifs (1 h)` par :

```markdown
## 🔹 Phase 4 – TD différencié : analyse de formulations lavantes (1 h)

### Organisation

Chaque niveau travaille sur des produits différents avec des niveaux d'exigence croissants.

**N1 – Guidé** : analyse du gel douche seul (doc. 1). Identification des tensioactifs par cases à cocher, classement par famille, texte à trous sur le lien pouvoir lavant / douceur.

**N2 – Standard** : comparaison gel douche (doc. 1) vs shampooing bébé (doc. 5). L'étudiant identifie les différences de familles, explique le choix des non ioniques pour bébé, rédige un paragraphe argumenté.

**N3 – Expert** : comparaison de 3 formules (gel douche, shampooing bébé, gel nettoyant visage peaux sensibles). Tableau comparatif + analyse de l'anionique doux (Sodium Cocoyl Glutamate) + argumentation type E2 sur mousse ≠ efficacité.

### Circulation de l'enseignant

Priorité N1 (20 min). Passage N2 pour vérifier les arguments. N3 en autonomie.
```

---

## 06b_trace_ecrite.md → CONSERVER TEL QUEL ✅

Excellente, complète avec schémas. Aucune modification.

---

## 06c_evaluation.md → 2 MODIFICATIONS

### Modification 1 : YAML title (cohérence)
Remplacer :
```
title: 06 🖊️ Évaluation
```
Par :
```
title: 06 🖋️ Évaluation formative
```

### Modification 2 : barème indicatif (cohérence S01)
Remplacer :
```
📌 Évaluation formative – barème indicatif
```
Par :
```
📌 Barème indicatif : /20
```

---

## 06c_evaluation_CO.md → 2 MODIFICATIONS

### Modification 1 : YAML title
Remplacer :
```
title: 06 🧴 Correction – Évaluation
```
Par :
```
title: 06 🖋️ Évaluation formative CORRIGE
```

### Modification 2 : titre H1/H2
Remplacer :
```
# 06 – Tensioactifs : rôle et usage en cosmétologie  
## 🧴 Correction de l'évaluation formative
```
Par :
```
# S06 – Tensioactifs : rôle et usage en cosmétologie
## Corrigé de l'évaluation formative
```

---

## README.md → 3 AJOUTS

### Ajout 1 : test rapide (après la section Ressources)

```markdown
---

## 🔬 "Test rapide" : Identifier un tensioactif dans une liste INCI

\```
1. Le nom contient-il "Sulfate", "Sulfonate", "Cocoate" ?
   → Probablement ANIONIQUE (lavant puissant)

2. Le nom contient-il "Betaine", "Amphoacetate" ?
   → Probablement AMPHOTÈRE (doux, co-tensioactif)

3. Le nom contient-il "Glucoside", "Polysorbate" ?
   → Probablement NON IONIQUE (très doux)

4. Le nom contient-il "Quaternium", "Cetrimonium" ?
   → Probablement CATIONIQUE (conditionnement, pas lavant)

⚠️ Un produit lavant contient souvent 2-3 tensioactifs
   associés pour combiner efficacité et douceur.
\```
```

### Ajout 2 : points clés

```markdown
---

## 🔑 Points clés

| Règle | Application |
|-------|-------------|
| Tensioactif = molécule **amphiphile** | Tête hydrophile + queue hydrophobe → micelles |
| 4 familles | Anioniques (lavants), cationiques (conditionneurs), amphotères (doux), non ioniques (très doux) |
| Le choix dépend de l'**usage** | Zone, public, fréquence → famille de TA adaptée |
| Mousse ≠ efficacité | Un produit peu moussant peut être efficace et mieux toléré |
| On **associe** plusieurs TA | Pouvoir lavant + douceur + tolérance |
```

### Ajout 3 : navigation (en fin de fichier)

```markdown
---

## 🔗 Navigation

⬅️ Séance précédente : [05 – Sécurité des produits cosmétiques](../05_securite/)

➡️ Séance suivante : [07 – Évaluation n°1](../07_eval/)
```

---

## RÉSUMÉ

| Fichier | Action |
|---------|--------|
| 06_deroule.md | 🔧 2 patchs (bloc FE3 + phase 4 différenciée) |
| 06a_fiche_eleve.md | ❌ REMPLACER (différenciation 3 niveaux ajoutée) |
| 06a_fiche_eleve_CO.md | ❌ REMPLACER (suit nouvelle fiche) |
| 06b_trace_ecrite.md | ✅ CONSERVER tel quel |
| 06c_evaluation.md | 🔧 2 petites modifs (YAML + barème) |
| 06c_evaluation_CO.md | 🔧 2 petites modifs (YAML + titres) |
| README.md | 🔧 3 ajouts (test rapide, points clés, navigation) |
