
# Projet — Avancement d'une transformation chimique

## Contexte
Simulation interactive pour élèves de première (spécialité physique-chimie).
Développée avec Cyril Denis, lycée de Vernon (Normandie).

## Fichiers existants
- `avancement_chimique.html` : simulation complète (Chart.js, vanilla JS)
  - Menu déroulant : 3 réactions (C+O₂, 2H₂+O₂, 4Al+3O₂)
  - Histogramme + graphique n(x) avec points mobiles
  - Slider x par pas de 0,1 mol, bloqué à xmax avec alerte rouge
  - Encart dépliable "Repérage du réactif limitant" (quotients n₀/ν)
  - Tableau d'avancement dépliable (4 lignes : initial/formule/valeurs/final)
  - Mode clair, responsive, palette bleu #1a56db / rouge #c0392b / vert #16a34a

- `fiche_avancement.typ` : fiche élève Typst
  - Importe ../_assets/template_physique.typ (fonctions : conf, chapitre, travail, box)
  - 3 parties : C+O₂ guidée / 2H₂+O₂ semi-guidée / 4Al+3O₂ autonome
  - Défi final : m(Al₂O₃)=408g, résultats vérifiables dans la simulation

## Prochaines tâches possibles
- Feuille d'exercices de renforcement (dont "12g C + 12g O₂ → pourquoi pas 24g ?")
- Fiche corrigé professeur
- Ajout de réactions en solution (acido-basique, dosage)
- ...

## Contraintes techniques
- HTML : vanilla JS uniquement, Chart.js 4.4.1 CDN, pas de framework
- Typst : respecter les fonctions du template (travail, experience, box, chapitre)
- Quantités initiales entières (boutons ±1), avancement par pas de 0,1 mol
- Simulation : réactions limitées à 3 espèces, coefficients entiers
