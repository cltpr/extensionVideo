# Dossier technique - Extension du systeme de videoprotection (commune d'Evres)

## 1. Contexte et objectifs

- Systeme existant : **6 cameras DAHUA DH-IPC-HFW5442E-ZE** autorisees par l'arrete prefectoral **n° 2026-387 du 10 mars 2026** (demande n° 20240253). Sites A (cameras 1-3), B (cameras 4-5), C (camera 6) couvrant les entrees du village ; enregistreur et commutateur en mairie (Place de la Halle), liaison radio NANO BEAM NBE-5AC-Gen2.
- Problematique de securite publique visee : rodeurs et vehicules suspects, vols de carburant sur tracteurs, degradations des armoires electriques communales, introduction nocturne dans un domicile (cf. rapport de presentation, dossier 02).
- Objectif de l'extension : inclure dans le dispositif les zones du village non couvertes a ce jour (entree du village cote Vaubecourt, rue du Moulin, rue de Soisy), a la demande des habitants concernes, et renforcer la protection des abords de la mairie et de la salle des fetes.
- Bilan du dispositif actuel : resolution d'une incivilite grave, assistance aux forces de l'ordre dans une investigation de cambriolage dans un village voisin.

## 2. Typologie et caracteristiques des equipements

Existant (autorise) :

| Repere | Site | Localisation | Type | Caracteristiques |
|---|---|---|---|---|
| CAM 1 | A | Entree du village, provenance Foucaucourt (Nord) - **champ futur : abords de la mairie et de la salle des fetes** | fixe | DAHUA DH-IPC-HFW5442E-ZE |
| CAM 2 | A | Arrivee D151, provenance Triaucourt (Ouest) | fixe | DAHUA DH-IPC-HFW5442E-ZE |
| CAM 3 | A | Rue de la Tannerie (Sud) | fixe | DAHUA DH-IPC-HFW5442E-ZE |
| CAM 4 | B | Rue du Moulin (Ouest) | fixe | DAHUA DH-IPC-HFW5442E-ZE |
| CAM 5 | B | Rue de la Tannerie, provenance Vaubecourt (Sud) | fixe | DAHUA DH-IPC-HFW5442E-ZE |
| CAM 6 | C | Entree du village, provenance Nubecourt (Est) | fixe | DAHUA DH-IPC-HFW5442E-ZE |

- **CAM 1 : reorientation du champ de vision** (camera non deplacee, site A inchange). **Motif double** : (1) le champ actuel est **redondant** avec celui de la CAM 2 (aucune perte de couverture : la CAM 2 couvre seule le champ des actuelles CAM 1-2) ; (2) **interet de proteger la mairie et la salle des fetes**, batiments publics dont les abords doivent etre mieux surveilles. Le champ est reforme en consequence. Operation declaree dans la demande de modification ; sans acquisition, hors base eligible FIPDR.

Extension (perimetre du 24/11/2026) :

| Repere | Site | Localisation | Type | Caracteristiques |
|---|---|---|---|---|
| CAM 7 | D (nouveau) | Entree du village, cote Vaubecourt | [a definir au devis] | [resolution, angle, vision nocturne] |
| CAM 8 | E (nouveau) | Rue du Moulin | [a definir au devis] | [resolution, angle, vision nocturne] |
| CAM 9 | F (nouveau) | Rue de Soisy | [a definir au devis] | [resolution, angle, vision nocturne] |

- Les CAM 2 a 6 demeurent en place, sans modification.
- Configuration future : site A (CAM 1, 2, 3), site B (CAM 4, 5), site C (CAM 6), site D (CAM 7), site E (CAM 8), site F (CAM 9). **Total : 9 cameras sur 6 sites.**
- Enregistreur / stockage : DAHUA DHI-NVR5216-8P6EI (16 canaux ; capacite disque [ ]), duree de conservation **30 jours maximum**.
- Commutateur : DH-PFS3110-8ET-96 (8 ports PoE) en mairie, **sature a 8 ports** ; le passage a 9 cameras impose un **commutateur PoE additionnel** (au devis, en poste distinct : eligibilite FIPDR a confirmer aupres du service instructeur).
- Transmission : liaison radio NANO BEAM NBE-5AC-Gen2 entre sites existants et mairie, **inchangee** ; **sites D, E et F raccordes au systeme existant par cablage Ethernet direct** (cuivre), sans antenne supplementaire. **Vigilance : environ 100 m de longueur utile par segment Ethernet cuivre** ; cheminement, mode de pose et eventuels equipements intermediaires a faire figurer au devis.
- Alimentation / onduleur : [ ]
- Signalisation : **panonceaux deja en place**, conformes a l'arrete n° 2026-387 ; apposition de panonceaux identiques aux abords des sites D, E et F a la mise en service (aucune depense a chiffrer au devis ni au plan de financement) ; affichage du site A a verifier apres reorientation de la CAM 1

## 3. Localisation

- Joindre le **plan de situation** des cameras existantes et nouvelles (PDF nomme plan-localisation-cameras.pdf) ; reprendre la presentation du dossier initial (dossier-initial/description-projet-initial.tex : villageComplet.jpg par site, champs de vues par camera, zones privees masquees).
- [ ] Plan de localisation des equipements (sites A a F), avec le cheminement du cablage Ethernet vers les sites D (entree cote Vaubecourt), E (rue du Moulin) et F (rue de Soisy), et les champs de vision actualises (CAM 1 vers mairie / salle des fetes).
- Zones privees (fenetres, cours) a masquer dans les champs de vision des cameras nouvelles, comme dans le dossier initial.
- Captures des champs de vision : documentées dans champs-de-vision.md (fiche créée le 24/11/2026 ; **captures CAM 3, 4, 5 et 6 reçues et décrites** ; CAM 1 et 2 à fournir). Vigilance relevée : zones privées visibles sur CAM 4 et CAM 6 (voir champs-de-vision.md).

## 4. Exploitation et consultation des images

- Poste de visualisation : mairie d'Evres, Place de la Halle ; personnes habilitees : maire et secretaire de mairie (arrete 2026-387, art. 3).
- Conditions d'acces pour la gendarmerie : a tout moment, dans les conditions de l'art. R.253-1 du CSI (arrete, art. 4) ; pas de deport en continu.
- Maitre d'ouvrage : Commune d'Evres ; Maitre d'oeuvre / installateur : [ ]

## 5. Cadre juridique

- Arrete prefectoral d'autorisation : **n° 2026-387 du 10 mars 2026**, valable jusqu'au 10 mars 2031.
- Demande de modification deposee le : [date]
- References : code de la securite interieure (art. L.251-1 a L.255-1 et R.251-1 a R.253-4)
