# Projet : Quantités de matière — Physique-chimie Seconde & Première

## Contexte
Application web destinée à des élèves de Seconde et de Première en physique-chimie.
Utilisée individuellement sur ordinateur ou mobile (iPhone et Android).
La page d'accueil est divisée en deux sections : "Classe de Seconde" et "Classe de Première".

## Objectif pédagogique
Calculer une quantité de matière ou un nombre d'entités à partir de la relation
n = N / N_A, dans les deux sens (n → N et N → n).

---

## Structure pédagogique

### Phase 1 — Modelage (entièrement rédigé, lecture seule)

Présentation de la relation :
  n = N / N_A

Définitions des grandeurs :
- n : quantité de matière, exprimée en mole (mol)
- N : nombre d'entités (atomes, molécules, ions, etc.) — sans unité
- N_A : constante d'Avogadro = 6,0 × 10²³ mol⁻¹

---

**Exemple 1 — Calculer n à partir de N**

Énoncé : Dans un verre d'eau, il y a 8,0 × 10²³ molécules d'eau.
Calcule la quantité de matière en molécules d'eau.

Réponse rédigée en 3 étapes :
1. Expression littérale : n = N / N_A
2. Application numérique : n = (8,0 × 10²³) / (6,0 × 10²³)
3. Résultat final : n = 1,3 mol

---

**Exemple 2 — Calculer N à partir de n**

Énoncé : Un comprimé d'aspirine contient 2,5 × 10⁻³ mol de molécules d'aspirine.
Calcule le nombre de molécules d'aspirine dans ce comprimé.

Réponse rédigée en 3 étapes :
1. Expression littérale : N = n × N_A
2. Application numérique : N = 2,5 × 10⁻³ × 6,0 × 10²³
3. Résultat final : N = 1,5 × 10²¹ molécules

---

### Phase 2 — Pratique guidée (2 exercices)

Format : réponse pré-structurée en 3 étapes avec des **menus déroulants** à la
place des éléments clés. L'élève choisit la bonne option parmi 3 ou 4 propositions
à chaque blank. Pas de saisie libre.

---

**Exercice 1 — Calculer N à partir de n**

Énoncé : Un clou en fer contient 0,050 mol d'atomes de fer.
Calcule le nombre d'atomes de fer dans ce clou.

Structure de la réponse guidée :
1. Expression littérale : N = [menu : n × N_A | n / N_A | N_A / n]
2. Application numérique : N = [menu : 0,050 | 6,0 × 10²³ | 0,050 × 6,0 × 10²³ | 0,050 / 6,0 × 10²³]
   × [menu : N_A | n | 6,0 × 10²³] (selon ce qui reste après le choix précédent)
   → simplifier : deux champs séparés (mantisse + exposant) pour le résultat
3. Résultat final : N = [champ mantisse] × 10^[champ exposant] atomes
   Réponse attendue : 3,0 × 10²² (tolérance ±1 sur le dernier chiffre significatif)

---

**Exercice 2 — Calculer n à partir de N**

Énoncé : Une molécule d'ADN contient 1,2 × 10²⁵ atomes.
Calcule la quantité de matière correspondante.

Structure de la réponse guidée :
1. Expression littérale : n = [menu : N / N_A | N × N_A | N_A / N]
2. Application numérique : n = [menu : 1,2 × 10²⁵ / 6,0 × 10²³ | 1,2 × 10²⁵ × 6,0 × 10²³ | 6,0 × 10²³ / 1,2 × 10²⁵]
3. Résultat final : n = [champ mantisse] × 10^[champ exposant] mol
   Réponse attendue : 2,0 × 10¹ soit 20 mol (tolérance ±1 sur le dernier chiffre)

---

### Phase 3 — Quiz de validation (obligatoire avant la pratique autonome)

L'élève doit répondre correctement aux 3 questions pour débloquer la phase 4.
En cas d'erreur sur une question, un feedback immédiat s'affiche et il peut réessayer.
Il ne passe à la question suivante qu'après avoir donné la bonne réponse.

**Question 1 — Formules correctes**
Consigne : "Parmi les 4 propositions suivantes, lesquelles sont des formules justes ?"
(cases à cocher — plusieurs réponses possibles)
- [ ] n = N / N_A      ✓ correcte
- [ ] N = n × N_A      ✓ correcte
- [ ] N_A = n × N      ✓ correcte
- [ ] n = N × N_A      ✗ incorrecte
- [ ] N = n / N_A      ✗ incorrecte

L'élève doit cocher exactement les 3 cases correctes pour valider.

**Question 2 — Valeur de la constante d'Avogadro**
Consigne : "Quelle est la valeur de la constante d'Avogadro à 2 chiffres significatifs ?"
Format de réponse : deux champs séparés — mantisse + exposant
Réponse attendue : mantisse = 6,0 / exposant = 23

**Question 3 — Unité de la quantité de matière**
Consigne : "Quel est le symbole de l'unité de la quantité de matière ?"
Format : champ texte libre (saisie courte)
Réponse attendue : mol (insensible à la casse)

---

### Phase 4 — Pratique autonome (5 questions, avec score)

Règles générales :
- Résultats exprimés à 2 chiffres significatifs — consigne rappelée dans chaque énoncé
- Tolérance : ±1 sur le dernier chiffre significatif
- Saisie des résultats : deux champs séparés (mantisse + exposant) pour les puissances de 10
- N_A = 6,0 × 10²³ mol⁻¹ (l'élève doit la connaître — non fournie sauf mention contraire)
- Après chaque question : feedback immédiat
  - Bonne réponse → encouragement court
  - Mauvaise réponse → correction détaillée en 3 étapes + identification de l'erreur commise
- Score affiché à la fin (ex. "4/5")

**Question 1** (sens N → n, entiers simples)
Énoncé : "Un échantillon de sel de cuisine contient 3,6 × 10²⁴ ions chlorure Cl⁻.
Calcule, à 2 chiffres significatifs, la quantité de matière d'ions chlorure."
Réponse : n = 6,0 mol

**Question 2** (sens n → N, décimal)
Énoncé : "Un médicament contient 0,25 mol de molécules de paracétamol.
Calcule, à 2 chiffres significatifs, le nombre de molécules de paracétamol."
Réponse : N = 1,5 × 10²³ molécules

**Question 3** (sens N → n, écriture scientifique, contexte biologie)
Énoncé : "Un globule rouge contient environ 2,8 × 10⁸ molécules d'hémoglobine.
Calcule, à 2 chiffres significatifs, la quantité de matière d'hémoglobine dans un globule rouge."
Réponse : n = 4,7 × 10⁻¹⁶ mol

**Question 4** (sens n → N, N_A plus précise fournie, contexte chimie)
Énoncé : "Un ballon contient 0,040 mol de diazote N₂. On donne N_A = 6,02 × 10²³ mol⁻¹.
Calcule, à 2 chiffres significatifs, le nombre de molécules de diazote dans ce ballon."
Réponse : N = 2,4 × 10²² molécules

**Question 5** (sens N → n, nombre décimal difficile, contexte matériaux)
Énoncé : "Un fil de cuivre contient 4,5 × 10²² atomes de cuivre.
Calcule, à 2 chiffres significatifs, la quantité de matière de cuivre dans ce fil."
Réponse : n = 0,075 mol (ou 7,5 × 10⁻² mol)

---

## Validation des réponses numériques

- Résultats à 2 chiffres significatifs
- Tolérance : ±1 sur le dernier chiffre significatif
- Pour les saisies en notation scientifique : deux champs séparés (mantisse + exposant)
  identiques au format de l'activité puissances-de-10
- Accepter la virgule ou le point comme séparateur décimal
- Insensible aux espaces

---

---

# Activité Première — Masse molaire et concentration molaire

## Phase 1 — Cours (Première)

### Bloc 1 — Masse molaire des atomes
Définition : la masse molaire M d'un atome est la masse d'une mole de ces atomes, en g/mol.

Valeurs à connaître (tableau) :
| Atome | M (g/mol) |
|-------|-----------|
| H     | 1,0       |
| C     | 12        |
| N     | 14        |
| O     | 16        |
Les autres valeurs sont toujours données dans l'énoncé.

### Bloc 2 — Masse molaire des molécules
Règle : M(molécule) = somme des masses molaires de tous les atomes présents.

Exemple 1 — Eau H₂O :
  M(H₂O) = 2×M(H) + M(O) = 2×1,0 + 16 = 18 g/mol

Exemple 2 — Dioxyde de carbone CO₂ :
  M(CO₂) = M(C) + 2×M(O) = 12 + 2×16 = 44 g/mol

### Bloc 3 — Solides ioniques et ions
Même règle. Pour les ions : ignorer la charge, sommer uniquement les masses molaires des atomes.

Exemple 1 — NaCl (on donne M(Na) = 23 g/mol, M(Cl) = 35,5 g/mol) :
  M(NaCl) = 23 + 35,5 = 58,5 g/mol

Exemple 2 — Ion sulfate SO₄²⁻ (on donne M(S) = 32 g/mol) :
  M(SO₄²⁻) = M(S) + 4×M(O) = 32 + 4×16 = 96 g/mol
  Note explicite : "La charge 2− ne modifie pas le calcul."

### Bloc 4 — Concentration molaire
Relation : c = n / V
- c : concentration molaire, en mol/L
- n : quantité de matière de soluté, en mol
- V : volume de la SOLUTION (pas du solvant), en litre (L)

Lien avec la masse : n = m/M, donc c = m / (M × V)

Exemple — Glucose C₆H₁₂O₆ (on donne M = 180 g/mol) :
  On dissout 10 g de glucose. Le volume de solution obtenu est 200 mL.
  Calcule la concentration molaire.

Erreur fréquente à signaler EXPLICITEMENT :
  V = 200 mL → il faut convertir : V = 200 / 1000 = 0,200 L
  (erreur classique : oublier la conversion mL → L)

Réponse rédigée en 3 étapes :
1. Calcul de n : n = m/M = 10 / 180 = 5,6×10⁻² mol
2. Conversion du volume : V = 200 mL = 0,200 L
3. Calcul de c : c = n/V = 5,6×10⁻² / 0,200 = 0,28 mol/L

---

## Contraintes techniques
- Un seul fichier index.html, CSS et JS inclus dans le fichier
- Formules mathématiques rendues avec MathJax (seul CDN autorisé)
- Design sobre, lisible, adapté lycée (pas enfantin)
- Navigation linéaire : Phase 1 → Phase 2 → Phase 3 (quiz) → Phase 4
- Le quiz doit être validé pour débloquer la phase 4
- Bouton "recommencer" à la fin

## Contraintes d'interface et d'ergonomie
- Tous les champs de saisie affichent le clavier complet sur iOS et Android
  → utiliser inputmode="text" sur tous les éléments <input>
- Les champs mantisse/exposant utilisent inputmode="decimal"
- Taille de police minimum 16px sur les champs de saisie (évite le zoom automatique sur iOS)
