# 02 - Autorisation prefectorale : demande de modification du systeme

> NB : dossier.prepare le 22/11/2026 a partir des informations officielles en vigueur (plateforme temporaire suite a l'indisponibilite de la tele-procedure ministerielle depuis le 21/10/2026). Verifier la page Videoprotection de la prefecture de la Meuse au moment du depot.

## Role dans la candidature FIPDR 2027

- Piece exigee : arrete d'autorisation en cours de validite OU accuse de depot de la demande de modification.
- **Le depot de la demande suffit pour candidater** au FIPDR 2027 (echeance : lundi 7 decembre 2026, 0h00, Subventia).
- L'arrete prefectoral de modification est obligatoire **avant toute mise en service** des nouvelles cameras, et le projet ne doit pas avoir debute avant l'attestation de completude du dossier FIPDR.

## Procedure en vigueur (verifiee le 22 novembre 2026)

1. La plateforme ministerielle habituelle (televideoprotection.interieur.gouv.fr) est **indisponible depuis le 21 octobre 2026**. Depot temporaire : https://demarche.numerique.gouv.fr/commencer/videoprotection (FranceConnect ou compte demarche.numerique.gouv.fr).
2. Formulaire : **Cerfa n°13806*04**, case « Modification d'un systeme autorise ».
3. Pre-requis : l'autorisation initiale doit etre **toujours en cours de validite** ; renseigner le **numero de dossier** de la demande initiale.
4. Une demande de modification **prolonge automatiquement l'autorisation de 5 ans**.
5. La prefecture de la Meuse n'accepte les dossiers complets **que de facon dematerialisee**.

## Etat du dossier (mis a jour le 22/11/2026)

- Commune porteuse : **Evres (55250)**, representee par M. **Clement FEVEZ**, maire (Place de la Halle, 55250 Evres ; tel. 03 29 92 05 97 ; evres@orange.fr).
- Arrete initial : **n° 2026-387 du 10 mars 2026**, autorisant **6 cameras visionnant la voie publique**, pour 5 ans renouvelable (valable jusqu'au 10 mars 2031).
- Demande initiale enregistree sous le **n° 20240253** ; dossier initial (lettre au prefet + description du projet d'aout 2025) archive dans dossier-initial/.
- Systeme existant : **6 cameras DAHUA DH-IPC-HFW5442E-ZE** sur 3 sites : site A (cameras 1-3 : entree Nord / Foucaucourt, arrivee D151 Ouest / Triaucourt, rue de la Tannerie Sud), site B (cameras 4-5 : rue du Moulin, rue de la Tannerie / Vaubecourt), site C (camera 6 : entree Est / Nubecourt) ; NVR DAHUA DHI-NVR5216-8P6EI et commutateur DH-PFS3110-8ET-96 en mairie, liaison radio NANO BEAM NBE-5AC-Gen2 ; enregistrement standard, autres options desactivees.
- **Extension visee** :
  - **2 cameras neuves (CAM 7 et CAM 8) sur un nouveau site D**, a localiser ;
  - **deplacement de la CAM 1** du site A (champ de vision redondant avec la CAM 2) vers un **nouveau site E**, a localiser ;
  - configuration future : **8 cameras** sur 5 sites (A : CAM 2-3 ; B : CAM 4-5 ; C : CAM 6 ; D : CAM 7-8 ; E : CAM 1).
- NB materiel : les CAM 7 et 8 occupent les 2 derniers ports PoE du commutateur (8/8 apres extension) ; liaisons radio/cablage a prevoir pour les sites D et E dans les devis.
- Installateur pressenti : **non certifie**, la piece 11 sera le questionnaire de conformite.
- Deport d'images : **non prevu** ; l'arrete en vigueur permet deja aux gendarmes habilites d'acceder a tout moment aux images (art. 4, conditions de l'art. R.253-1 du CSI).
- Justification : zones du village non couvertes ; remontees d'habitants decus de ne pas etre inclus ; bilan positif du dispositif (resolution d'une incivilite grave, assistance aux forces de l'ordre dans une investigation de cambriolage dans un village voisin).
- Finalites a reprendre telles quelles (arrete art. 1er) : protection des batiments et installations publics et de leurs abords ; prevention des atteintes a la securite des personnes et des biens dans des lieux exposes (agressions, vols, trafic de stupefiants) ; prevention et constatation des infractions relatives a l'abandon d'ordures, dechets, materiaux ou autres objets.
- La modification substantielle doit etre declaree aux services prefectoraux (arrete art. 5) : c'est l'objet de la presente demande.

## Pieces du dossier de demande de modification

| # | Piece | Gabarit / source |
|---|---|---|
| 0 | Cerfa 13806*04 (en ligne, case modification) | demarche en ligne |
| 0 bis | Lettre au prefet (facultative mais recommandee, a joindre en ligne) | demande-modification/00-lettre-au-prefet.tex |
| 1 | Rapport de presentation | demande-modification/01-rapport-de-presentation.md |
| 2 | Plan de masse | a faire produire par l'installateur |
| 3 | Plan de detail (voie publique ou 8 cameras et plus : cas d'Evres les deux) | a faire produire par l'installateur |
| 4 | Plan du perimetre (si perimetre videoprotege) | non applicable |
| 5 | Description transmission / enregistrement / traitement | demande-modification/03-description-dispositif.md |
| 6 | Personnes pouvant acceder aux images | demande-modification/04-personnes-habilitees.md |
| 7 | Information du public (affiche / panonceau) | demande-modification/05-information-du-public.md |
| 8 | Delai de conservation des images (+ justification) | demande-modification/06-conservation-et-acces.md |
| 9 | Responsable maintenance (si different) | section de 03-description-dispositif.md |
| 10 | Droit d'acces des personnes | demande-modification/06-conservation-et-acces.md |
| 11 | Conformite aux normes (arrete du 3 aout 2007) : questionnaire (installateur NON certifie) | demande-modification/07-installateur-conformite.md |
| 12 | Engagement de conformite | demande-modification/08-engagement-de-conformite.md |
| 13 | Analyse d'impact (AIPD) | demande-modification/09-aipd.md |

Les plans et la description du dossier initial (dossier-initial/description-projet-initial.tex) servent de modele pour ceux de l'extension.

## Etapes

1. Completer les gabarits de demande-modification/ : localisations des sites D et E, faits recents.
2. Demander a l'installateur pressenti : devis, plans (masse + detail) et questionnaire de conformite, en parallele des devis (dossier 04-devis/).
3. Deposer en ligne en suivant demande-modification/00-guide-depot.md.
4. Enregistrer ici l'accuse de depot PDF : accuse-depot-modification.pdf, et copier l'arrete 2026-387 : arrete-2026-387.pdf.
5. Cocher la piece correspondante du dossier FIPDR (README racine).
6. En parallele : solliciter l'avis du referent surete gendarmerie (determinant pour la selection FIPDR, cf. www.referentsurete.fr).
7. Attendre l'arrete prefectoral (instruction : referent surete, commission departementale des systemes de videoprotection) ; ordre de grandeur constate dans d'autres departements : 3 a 4 mois. Aucune mise en service avant reception de l'arrete.

### Reste a rassembler

- [ ] Localisation des sites D et E (voies visees, champs de vision)
- [ ] Faits recents survenus depuis la mise en service (pour le rapport de presentation et la lettre)
- [ ] Entreprise installeur retenue (devis, plans, questionnaire conforme)
