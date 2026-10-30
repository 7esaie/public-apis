# Kaonty Pro

Logiciel de devis et de factures pour une entreprise de services à Madagascar.

## Fonctions (version 1)

- Fiche entreprise : NIF, STAT, RCS, TVA (assujetti ou non), banque, Mobile Money
- Clients et catalogue de prestations
- Mise en page identique au modèle papier de C.E.R.F (logo, bloc « DOIT », Objet, Référence, Concerne, délais)
- Numérotation continue au format `CERF-N°01751/2026`, préfixe et numéro de départ réglables
- Calcul en Ariary : total HT, remise, TVA, total TTC, montant en lettres
- Statuts des devis (brouillon, envoyé, accepté, refusé) et transformation en facture en un clic
- Suivi des paiements (espèces, virement, chèque, MVola, Orange Money, Airtel Money) et des retards
- Téléchargement en PDF

## Fonctionnement

`index.html` est publié comme Artifact claude.ai. Les données sont enregistrées
grâce à la capacité `db` de l'Artifact : elles sont partagées entre l'ordinateur
et le téléphone, et réservées aux personnes qui ont un accès Contributeur ou Éditeur.

## Étapes suivantes prévues

- Lecture de la boîte Gmail pour repérer les offres et les bons de commande
- Comptabilité : recettes, dépenses, journal selon le PCG 2005
