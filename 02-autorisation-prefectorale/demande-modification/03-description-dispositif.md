# Description du dispositif de transmission, enregistrement et traitement des images (commune d'Evres)

## Architecture

- Existant : **6 cameras DAHUA DH-IPC-HFW5442E-ZE** (sites A, B et C, entrees du village) raccordees au commutateur **DH-PFS3110-8ET-96** (8 ports PoE, 6 utilises actuellement) vers l'enregistreur **DAHUA DHI-NVR5216-8P6EI** (16 canaux) en mairie, Place de la Halle.
- Extension : **3 cameras nouvelles sur trois nouveaux sites** : CAM 7 (site D, entree du village cote Vaubecourt), CAM 8 (site E, rue du Moulin), CAM 9 (site F, rue de Soisy), [modeles a definir au devis].
- **Aucune camera existante n'est deplacee** ; la **CAM 1** demeure sur son site (A) et verra son **champ de vision reoriente** vers les abords de la mairie et de la salle des fetes (champ actuel redondant avec la CAM 2, qui couvre seule le champ des actuelles CAM 1-2 : aucune perte de couverture).
- Configuration future : **9 cameras** sur 6 sites : A (CAM 1, 2, 3), B (CAM 4, 5), C (CAM 6), D (CAM 7), E (CAM 8), F (CAM 9).
- Ports PoE : le commutateur existant est limite a **8 ports** ; le passage a 9 cameras impose un **commutateur PoE additionnel** pour les cameras nouvelles (a faire figurer au devis, dossier 04-devis/).

## Transmission

- Liaison radio **NANO BEAM NBE-5AC-Gen2** entre les sites existants et la mairie, reseau dedie isole d'Internet, **inchangee** ; aucune antenne supplementaire.
- **Nouveaux sites D, E et F : raccordement au systeme existant par cablage Ethernet direct** (cuivre), cheminement a preciser par l'installateur.
- **Point de vigilance technique** : la longueur utile d'un segment Ethernet cuivre est d'environ 100 m ; l'installateur devra confirmer la faisabilite de chaque liaison (distances reels, mode de pose, eventuels equipements intermediaires) dans le devis.
- Cablage Ethernet et alimentation electrique dediee des nouvelles cameras : a faire figurer dans le devis (dossier 04-devis/), imputes par camera.

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
