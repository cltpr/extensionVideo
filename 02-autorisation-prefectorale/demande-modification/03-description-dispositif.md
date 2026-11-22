# Description du dispositif de transmission, enregistrement et traitement des images (commune d'Evres)

## Architecture

- Existant : **6 cameras DAHUA DH-IPC-HFW5442E-ZE** (sites A, B et C, entrees du village) raccordees au commutateur **DH-PFS3110-8ET-96** (8 ports PoE, 6 utilises) vers l'enregistreur **DAHUA DHI-NVR5216-8P6EI** (16 canaux) en mairie, Place de la Halle.
- Extension : ajout de **1 a 3 cameras** [modeles a definir au devis], au-dela de 2 cameras nouvelles un equipement reseau PoE supplementaire sera necessaire (le NVR accepte 16 canaux mais le commutateur n'a que 8 ports PoE).
- Transmission : liaison radio **NANO BEAM NBE-5AC-Gen2** entre sites et mairie [a adapter selon implantation des nouvelles cameras], reseau dedie isole d'Internet.

## Enregistrement et stockage

- Enregistreur configure en **mode standard d'enregistrement**, les autres options disponibles demeurent **desactivees** (pas de traitement algorithmique, conforme aussi aux exclusions FIPDR 2027).
- Duree de conservation : **30 jours maximum** (arrete n° 2026-387, art. 2), ecrasement / effacement automatique ; destruction hormis cas d'enquete de flagrant delit, d'enquete preliminaire ou d'information judiciaire.
- Securite : acces restreint (comptes nominatifs, mots de passe individuels), local protege en mairie, journal des acces, mises a jour du constructeur.

## Poste(s) de visualisation

- Mairie d'Evres, Place de la Halle, 55250 Evres.
- Personnes habilitees : maire et secretaire de mairie (liste jointe, 04-personnes-habilitees.md).

## Transmission aux forces de l'ordre

- Pas de deport d'images en continu (choix retenu au 22/11/2026).
- Les fonctionnaires de gendarmerie habilites et designes dans les conditions de l'article R.253-1 du CSI peuvent acceder **a tout moment** aux images et enregistrements, comme le prevoit l'arrete en vigueur (art. 4) ; conservation par ces derniers de 30 jours maximum.
- NB FIPDR : aucun poste de deport a inscrire au plan de financement (03).

## Maintenance

- Responsable maintenance (si different du responsable du systeme) : [service technique de la commune / entreprise ...].
- Contrat : [maintenance sur site, garanties, mise a jour des micrologiciels].
