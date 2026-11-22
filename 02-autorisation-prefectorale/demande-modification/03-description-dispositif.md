# Description du dispositif de transmission, enregistrement et traitement des images (commune d'Evres)

## Architecture

- Existant : **6 cameras DAHUA DH-IPC-HFW5442E-ZE** (sites A, B et C, entrees du village) raccordees au commutateur **DH-PFS3110-8ET-96** (8 ports PoE, 6 utilises actuellement) vers l'enregistreur **DAHUA DHI-NVR5216-8P6EI** (16 canaux) en mairie, Place de la Halle.
- Extension :
  - **2 cameras nouvelles sur le nouveau site D** (CAM 7 et CAM 8), [modeles a definir au devis] ;
  - **deplacement de la CAM 1** du site A (champ de vision redondant avec la CAM 2) vers le **nouveau site E** [voie / lieu a preciser].
- Configuration future : **8 cameras** sur 5 sites : A (CAM 2, 3), B (CAM 4, 5), C (CAM 6), D (CAM 7, 8), E (CAM 1).
- Ports PoE : **8/8 utilises apres extension** (les CAM 7 et 8 occupent les 2 ports libres ; la CAM 1 deplacee conserve sa baie physique). Le NVR (16 canaux) reste evolutif mais toute camera supplementaire exigera un equipement PoE additionnel.

## Transmission

- Liaison radio **NANO BEAM NBE-5AC-Gen2** entre les sites et la mairie, reseau dedie isole d'Internet, **inchangee**.
- **Sites D et E : raccordement au site B par fibre optique**, sans antenne supplementaire ; le site B reste relie a la mairie comme a ce jour.
- Cheminement fibre, connectique optique et alimentation des nouvelles cameras (PoE ou injecteur) : a faire figurer dans le devis (dossier 04-devis/).

## Enregistrement et stockage

- Enregistreur configure en **mode standard d'enregistrement**, les autres options disponibles demeurent **desactivees** (pas de traitement algorithmique, conforme aussi aux exclusions FIPDR 2027).
- Duree de conservation : **30 jours maximum** (arrete n° 2026-387, art. 2), ecrasement / effacement automatique ; destruction hormis cas d'enquete de flagrant delit, d'enquete preliminaire ou d'information judiciaire.
- Securite : acces restreint (comptes nominatifs, mots de passe individuels), local protege en mairie, journal des acces, mises a jour du constructeur.

## Poste(s) de visualisation

- Mairie d'Evres, Place de la Halle, 55250 Evres.
- Personnes habilitees : maire et secretaire de mairie (liste jointe, 04-personnes-habilitees.md).

## Transmission aux forces de l'ordre

- Pas de deport d'images en continu (choix retenu).
- Les fonctionnaires de gendarmerie habilites et designes dans les conditions de l'article R.253-1 du CSI peuvent acceder **a tout moment** aux images et enregistrements, comme le prevoit l'arrete en vigueur (art. 4) ; conservation par ces derniers de 30 jours maximum.
- NB FIPDR : aucun poste de deport a inscrire au plan de financement (03).

## Maintenance

- Responsable maintenance (si different du responsable du systeme) : [service technique de la commune / entreprise ...].
- Contrat : [maintenance sur site, garanties, mise a jour des micrologiciels].
