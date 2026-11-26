---
titre: Base de connaissances RC Pro Nostrum Care (assureur Hiscox)
version: 0.3-brouillon
date: 2026-11-26
usage: Gabriel (assistant WhatsApp / chat) — réponses aux prospects et clients RC Pro
langue: fr
statut: à relire par un gestionnaire RC Pro avant mise en production
---

# Base de connaissances RC Pro — Nostrum Care

## 0. Comment utiliser ce fichier (règles pour l'assistant)

### 0.1 Hiérarchie des sources (en cas de conflit, la plus haute gagne)

1. **Documents contractuels Hiscox** : conditions générales, conditions particulières, IPID, conventions spéciales. Ils ne sont PAS encore dans ce fichier : aucune réponse sur une garantie précise, une exclusion ou un plafond ne peut être garantie par ce fichier seul.
2. **La Calculette Hiscox (v0726)** : seule source pour les prix et pour la liste des activités réellement proposées. La section 12 n'en donne qu'une grille d'indicatifs.
3. **Formations Hiscox** (module RCP d'avril 2024, délégation de souscription) : bonne base sur le périmètre et les exclusions, mais indicative et datée.
4. **Contenus marketing Nostrum Care** : à utiliser pour le ton et l'argumentaire, jamais comme preuve d'une garantie.

Chaque section porte une étiquette de fiabilité : `[HISCOX-FORMATION]`, `[HISCOX-GARANTIES]`, `[MARKETING]`, `[À VALIDER]`.

### 0.2 Ce que l'assistant ne fait jamais

- Annoncer un prix hors de la grille de la section 12 ou en dehors de ses conditions d'usage : il renvoie alors vers le simulateur.
- Affirmer qu'un sinistre précis sera pris en charge : il peut expliquer ce que le contrat vise en général, puis dit qu'un conseiller ou l'équipe sinistres confirmera.
- Dire qu'une activité est assurable sans avoir vérifié les exclusions de la section 6. En cas de doute, il passe la main à un conseiller.
- Donner un conseil juridique, fiscal ou financier.
- Demander des données sensibles dans le chat (IBAN, pièce d'identité, mot de passe, code SMS).
- Citer des statistiques de marché (voir section 13, aucune n'est sourcée).
- Donner un numéro de téléphone de contact tant que le conflit de la section 13 n'est pas résolu.

### 0.3 Quand passer la main à un humain

- Sinistre en cours ou déclaration de sinistre.
- Question sur l'interprétation d'une exclusion ou sur la couverture d'un cas précis.
- Activité exercée à la frontière d'une exclusion (section 6), ou profession réglementée.
- Client déjà assuré ailleurs qui demande comment résilier.
- Réclamation, mécontentement, demande de remboursement.
- Chiffre d'affaires supérieur aux plafonds de la section 5.

## 1. Qui est qui `[HISCOX-FORMATION]`

- **Hiscox** est l'assureur qui porte le risque. Hiscox France est la succursale française du groupe Hiscox depuis 1995, avec des bureaux à Paris, Bordeaux et Lyon. Elle distribue via trois canaux : courtage, partenaires et vente en ligne.
- **Nostrum Care** distribue la RC Pro Hiscox dans le cadre d'une **délégation de souscription** : Nostrum Care applique le périmètre d'appétit et les exclusions définis par Hiscox.
- Le contrat est un contrat d'assurance **« tous risques sauf »** : ce qui n'est pas exclu est couvert.

## 2. L'offre RC Pro Nostrum Care `[MARKETING]`

**Nom commercial : Nostrum Pro.** Face à un prospect, dire « Nostrum Pro » ou « la RC Pro ». Le site vitrine annonce « à partir de 19 €/mois », une couverture immédiate et une souscription en environ 5 minutes. Secteurs mis en avant : tech et informatique, communication et événementiel, consulting en entreprise, culture, médias et journalisme, métiers du bien-être, autres services (services à la personne, taxi et VTC, formation).

Argumentaire officiel :

- Une RC Pro pensée pour les indépendants, « au prix juste ».
- Une **protection juridique** incluse, pour un soutien et des conseils à tout moment.
- **En option** : assurance du matériel informatique (garantie TDMI), pour éviter de souscrire une multirisque pro séparée. Le texte marketing cite aussi l'« immobilier » : formulation à clarifier, ne pas l'affirmer.
- **Zéro franchise** en cas de sinistre pour la majorité des profils (voir la condition en section 5 : elle dépend du chiffre d'affaires et du plafond, et ne vaut ni pour TAG ni pour SECU).
- Engagement commercial : en cas de sinistre, Nostrum Care part du principe que la réclamation est juste et n'interprète pas le contrat en défaveur de l'assuré. C'est un engagement de ton, pas une clause contractuelle : ne jamais le présenter comme une garantie écrite.
- Souscription en ligne simplifiée et conseil humain disponible.
- Page produit : https://nostrumcare.fr/responsabilite-civile-professionnelle

Options du contrat (d'après les noms de documents contractuels) : **RC Exploitation (RCE)** et **TDMI** (garantie matériel, intitulé Hiscox « Tous Risques Matériel »).

## 3. Les documents du contrat `[À VALIDER]`

Le client reçoit à la souscription (liste de l'e-mail de bienvenue) : conditions générales, conditions particulières, **IPID** (résumé standardisé des garanties), échéancier, facture annuelle, attestation. Ils sont aussi disponibles dans l'espace assuré de l'app Nostrum Care.

Documents par produit : contrat, attestation et IPID existent en trois versions (RC Pro, RCE, TDMI), plus les conventions spéciales Hiscox correspondantes.

Structure d'un contrat Hiscox : conditions générales RC Pro + conditions générales RC Exploitation + recours juridiques / protection juridique, complétées par un **module de garantie par famille d'activités** et les conditions particulières.

## 4. Les garanties `[HISCOX-GARANTIES]`

Source : fiche « Garantie RC Pro ». Les formulations ci-dessous résument des définitions contractuelles. Les conditions particulières priment.

### 4.1 Réclamations à votre encontre

| Garantie | Ce qu'elle vise |
|---|---|
| Manquement contractuel | Inexécution totale ou partielle de vos obligations au titre d'un contrat |
| Faute professionnelle / négligence | Erreur, omission ou négligence commise par vous ou vos préposés dans l'exécution d'un contrat |
| Événement cyber | Cas où vos engagements contractuels n'ont pas pu être tenus à cause d'un événement cyber, dans la seule limite de ces engagements et sous réserve des conditions particulières |
| Faute intentionnelle ou dolosive des préposés | Acte commis par vos préposés avec une intention dolosive, malveillante ou malhonnête |
| Divulgation d'informations confidentielles | Divulgation commise par vous ou vos préposés |
| Dénigrement | Discrédit jeté sur les produits ou services de tiers |
| Atteinte à la vie privée | Y compris nom, image, voix, intimité, correspondance, droit à l'oubli |
| Concurrence déloyale | Confusion avec les produits ou services d'un tiers, parasitisme, usurpation de nom, enseigne, nom de domaine, charte graphique |
| Atteinte aux droits de propriété intellectuelle | Contrefaçon (droit d'auteur, droits voisins, marques y compris cybersquatting, dessins et modèles, droit sui generis des bases de données) |
| Perte des biens et documents confiés | Perte ou destruction, totale ou partielle, de biens ou documents confiés par un client, y compris données électroniques |
| Livrables / produits non conformes | Ne correspondant pas aux caractéristiques prévues au contrat avec le client |
| Livrables / produits défectueux | N'offrant pas la sécurité attendue (article 1245-3 du Code civil ou droit étranger applicable) |

### 4.2 Garanties « Avantages Plus »

- **Atteinte à la réputation** : si une réclamation couverte vous cause un préjudice d'image, prise en charge des frais d'un consultant en communication, engagés par vos soins et préalablement agréés par l'assureur.
- **Remplacement d'un homme clé** : en cas de baisse de revenu ou d'activité due à l'incapacité totale et permanente, à une incapacité temporaire de plus de trois mois, à la perte totale d'autonomie ou au décès d'un homme clé, prise en charge des frais de recrutement, des frais de consultant en communication et des frais de personnel supplémentaire, pour 6 mois maximum à compter de l'indisponibilité.
- **Contestation de créance** : si un de vos clients fait l'objet d'une procédure collective (Livre VI du Code de commerce) et que le mandataire ou l'administrateur remet en cause un paiement qu'il vous a fait avant l'ouverture, prise en charge des frais d'examen juridique et, le cas échéant, d'avocat.

### 4.3 Protection juridique

- **Protection pénale** : poursuites devant un tribunal répressif pour une infraction non intentionnelle (maladresse, imprudence, négligence, inobservation des règlements…), ou action pénale que vous engagez parce que vous ou vos préposés êtes victimes d'injures, diffamation, dénigrement ou dommages corporels du fait d'un tiers.
- **Complément de la responsabilité civile** : quand votre responsabilité est recherchée mais que vos garanties RC sont inopérantes (réclamation inférieure à la franchise, préjudice non établi).
- **Garanties recours** : vous êtes victime d'un préjudice causé par un tiers (négligence, violation d'une obligation professionnelle, atteinte à votre propriété intellectuelle, manquement à la confidentialité, atteinte à votre image ou réputation).

### 4.4 Avantages de la formation Hiscox non retrouvés dans la fiche garanties `[À VALIDER]`

La formation Hiscox cite aussi, comme garanties additionnelles, le **piratage de site internet** et la **violation de données personnelles**. La fiche « Garantie RC Pro » ne les détaille pas. Ne pas les affirmer sans les conditions générales.

## 5. Capacités de souscription en délégation `[HISCOX-FORMATION]`

Document daté (délégation de souscription, sans date précise ; module RCP d'avril 2024). À recouper avec la Calculette v0726.

| Famille | Limite d'indemnité (LOI) minimale |
|---|---|
| TECH (informatique, digital) | 100 000 € |
| MAC (marketing, communication) | 100 000 € |
| MAN (conseil en entreprise) | 50 000 € |
| MISC (services divers, bien-être) | 50 000 € |
| MEDIA / MIC (médias, culture) | 100 000 € |
| TAG (tourisme) | 1,5 M€ |
| SECU (sécurité) | 300 000 € |

- **LOI maximale** : 3 M€ (TECH, MAC, MAN, MISC, MEDIA, TAG) ; 1 M€ pour SECU.
- **Chiffre d'affaires maximal** : 5 M€ pour les classes HC1 et HC2, 1,5 M€ pour HC3 et HC4 (TECH, MAC, MAN, MISC, MEDIA, TAG) ; 1 M€ pour SECU. Le sens de « HC1 à HC4 » n'est pas défini dans les documents fournis.
- **Sans sous-limite RCP**, y compris en DINC (dommages immatériels non consécutifs, terme d'assurance standard).
- **Sans franchise** sur les volets RCP et RCE pour un chiffre d'affaires ≤ 1,5 M€ et jusqu'à 1 M€ de garantie. Vérifié dans la Calculette v0726 : au-delà (TAG, dont la garantie démarre à 1,5 M€), la franchise RC Pro est de 1 500 à 3 000 € selon le niveau de garantie ; **SECU a toujours une franchise de 1 500 €**. « Zéro franchise » ne doit donc jamais être dit pour TAG et SECU.
- **Options de la Calculette** : matériel (TRM, garantie de 5 000 à 75 000 €, franchise de 300 €) et cyber (garantie de 50 000 €, franchise de 1 000 €). Le TDMI vendu par Nostrum Care correspond à l'option matériel ; l'option cyber n'apparaît pas dans les documents marketing et n'est pas confirmée dans l'offre.
- **Codes produit de la Calculette** : TECH, MAC, MAN, MISC, BIE (bien-être), MED (médias), TAG, SECU.
- **Prime forfaitaire** jusqu'à 1,5 M€ de chiffre d'affaires, sans ajustement. Au-delà de 1,5 M€, ajustement si le chiffre d'affaires varie de ±20 %.
- **Frais additionnels et correctifs** pris en charge pour éviter une réclamation ou limiter le coût d'un sinistre.
- **Extension monde entier** possible en cas d'exposition aux USA / Canada (avec des restrictions d'activité, voir section 7).

## 6. Exclusions générales de la RC Pro Hiscox `[HISCOX-FORMATION]`

Hiscox ne couvre pas, en RC Pro :

- l'immobilier (agent immobilier ; l'appétit existe pour les mandataires immobiliers, assimilés à des agents commerciaux) ;
- le bâtiment ;
- le médical ;
- la marine et le transport ;
- l'aéronautique, le spatial, le ferroviaire, le nucléaire ;
- les **professions réglementées**, sauf pour les produits TAG et SECU : expert-comptable, avocat, géomètre, notaire, conseiller financier, huissier, etc.

Conséquence pour l'assistant : un avocat, un expert-comptable, un notaire ou un conseiller financier n'est **pas** assurable avec ce produit.

## 7. Périmètre et exclusions par famille d'activités `[HISCOX-FORMATION]`

Les exclusions listées valent « en délégation » : un cas exclu ici peut parfois être étudié directement par Hiscox, mais l'assistant ne le promet jamais.

### MAC : marketing et communication

- **Couvert** : communication corporate et publicitaire ; connaissance client et analytics ; conseil et stratégie de communication / marketing ; événementiel (coordination des prestataires) ; marketing opérationnel.
- **Exclu** : architecture d'intérieur ; design industriel et prototypes ; fabrication et installation non sous-traitées de goodies, enseignes ou produits dérivés ; fabrication de matériel informatique ou de télécommunication ; développement de moyens de paiement sécurisés ou de processeur de paiement.
- Avec l'extension Monde entier, ne pas exercer en plus : réalisation / production de films publicitaires, marketing direct.

### MAN : conseil en entreprise

- **Couvert** : conseil en stratégie, organisation, développement commercial ; gestion administrative et financière de l'entreprise ; RH, recrutement, développement personnel ; environnement, qualité, certification, santé ; formation ; externalisation ; sécurité / compliance ; fonctions par intérim ou de transition ; diffamation (trade & slander).
- **Exclu** : conseil en décontamination, gestion de déchets, audit technique d'impact environnemental ; conseil en investissement financier ou gestion de patrimoine ; prescription technique assimilée à de l'ingénierie ou à un bureau d'études ; réalisation, suivi ou réception de travaux de bâtiment ou de génie civil ; conseil en brevets ; obligations de résultat ; conseil en optimisation fiscale et sociale (dont montage de dossiers de crédit d'impôt).
- Avec l'extension Monde entier, ne pas exercer en plus : conseil en fusion-acquisition, en recherche de financement, en qualité / santé / sécurité / environnement, direction par intérim, conseil en RSE, turnaround management, conseil en réduction des coûts, travail temporaire.

### TECH : informatique et digital

- **Couvert** : infrastructures, réseaux, hébergement, cloud ; télécoms ; logiciels, progiciels, applications spécifiques (y compris SaaS) ; jeux vidéo ; applications web / mobile, e-commerce ; services et conseil en informatique (gestion de projet, audit, AMOA, formation, infogérance).
- **Exclu** : construction de véhicules, drones ou logiciels embarqués ; data center ; moyens de paiement sécurisés et logiciels financiers ; jeux mobiles et applications mobiles grand public ; logiciels BIM ; fabrication de matériel informatique ou télécom ; prescriptions assimilées à de l'ingénierie ; systèmes de contrôle de véhicules routiers et ferroviaires ; manutention de bagages en aéroport ; machines pilotant un process de fabrication (SCADA) ; applications de biométrie ou en environnement médical et laboratoires.

### MISC : métiers variés, bien-être

- **Couvert** : accompagnement personnel et thérapie ; bien-être (dont tatoueur / perceur) ; service à la personne ; environnement, qualité, certification, santé ; formation ; autres services aux particuliers et aux entreprises ; gestion administrative.
- **Exclu** : conseil en décontamination et audit environnemental ; diagnostics immobiliers ; conseil juridique ; conseil en investissement ou gestion de patrimoine ; prescription technique assimilée à de l'ingénierie ; travaux de bâtiment ; conseil en brevets ; optimisation fiscale et sociale. En bien-être : blanchiment dentaire, médical / paramédical, détatouage, tatoueur à domicile, soin esthétique avec laser.

### MEDIA / MIC : culture, médias, journalisme

- **Couvert** : culture et divertissement ; médias ; journalisme ; spectacles vivants et événementiel ; audiovisuel.
- **Exclu** : professions réglementées soumises à obligation d'assurance ; conseil juridique ; agent artistique, manager d'artiste, impresario, éditeur musical ; cirque ; agences de presse nationales ou mondiales ; radio, web radio, télé d'actualités nationales ; presse people ou d'investigation ; conception, production ou diffusion de programmes d'investigation, débats politiques, sportifs ou religieux, téléréalité, jeux télévisuels, téléfilms, séries, dessins animés, films de cinéma ; événements tauromachiques ; manifestations de soutien ou de contestation sur la voie publique ; événements aux USA / Canada ou dans un pays sous sanctions ; rave parties et concerts grand public de techno, rap, hard rock, heavy metal ; événements avec structures gonflables ou feux d'artifice ; spectacles d'artistes connus pour des propos provocateurs ou pornographiques.

### TAG : tourisme

- **Couvert** : billetterie ; agence de voyages (revente de forfait dynamique) ; tour-opérateur ; représentant local / réceptif (tourisme d'accueil).
- **Exclu** : courtage en affrètement aérien ; voyages à caractère médical ; exploitation d'hébergement hôtelier ; exploitation de moyens de transport ; voyages festifs (enterrement de vie de garçon / jeune fille) ; voyages incluant sports extrêmes, héliski, ski hors-piste, safari chasse ; séjours spirituels, religieux ou ésotériques.

### SECU : sécurité

- **Couvert** : formation aux activités de sécurité privée soumises à agrément CNAPS ; gardiennage, surveillance, filtrage (hors télésurveillance) ; installateurs d'alarmes sociales ; intervention sur site en cas d'alarme intrusion ; sécurité incendie ; télésurveillance ; vente et installation de détecteurs incendie, fumée, gaz, extincteurs et RIA ; vente, installation et maintenance de systèmes anti-intrusion, contrôle d'accès, vidéosurveillance, télésurveillance.
- **Exclu** : garde rapprochée ; convoyage de fonds ; chargé de sécurité d'un site ou d'une manifestation ; conception et fabrication d'alarmes ou d'équipements de vidéosurveillance ; intervention sur site en cas d'alarme sociale ; surveillance de process industriels ; activités en zones aéroportuaires, militaires, sites classés, sites nucléaires, dépôts pétroliers.

## 8. RC Professionnelle et RC Exploitation `[HISCOX-FORMATION]`

- **RC Professionnelle (RCP)** : concerne les services, sans livraison de bien. Soit des prestations intellectuelles (dommages immatériels), soit des interventions sur des biens ou auprès de personnes (nettoyage, entretien, maintenance, surveillance : dommages matériels et / ou immatériels). Risque principal : erreur, omission, négligence.
- **RC Exploitation (RCE)** : pour Hiscox, tout ce qui n'est pas l'activité professionnelle elle-même et ne relève pas d'une relation contractuelle avec le client. Exemples : RC employeur (faute inexcusable), dommage corporel type « pot de fleur », intoxication alimentaire.
- Exemples RCE : lors d'un événement pour ses employés, un salarié abîme le matériel sono du DJ en ouvrant du champagne (Hiscox rembourse le matériel et la location de remplacement, 20 k€ au total) ; lors d'une garde d'enfant, une braise tombe d'une cheminée chez le client (changement de parquet, 2 k€).
- La RCE est une **option** du contrat Nostrum Care.

## 9. Exemples de sinistres `[HISCOX-FORMATION]`

Exemples illustratifs fournis par Hiscox, non contractuels.

- **Bien-être** : défaut de conseil (programme de coaching ou de remise en forme inadapté aux besoins ou capacités du client) ; divulgation accidentelle d'un fichier de données clients ; faute professionnelle (un coiffeur brûle le cuir chevelu d'une cliente avec un produit de décoloration).
- **Marketing / communication** : une agence se trompe de montre lors d'un clip pour un annonceur, qui exige un nouveau tournage (manquement contractuel ; Hiscox a pris en charge le tournage en urgence au titre des frais correctifs) ; une agence crée un logo déjà déposé et son client est assigné pour contrefaçon (Hiscox a mandaté un avocat, 6 000 € de frais, et indemnisé 45 000 €) ; un hébergeur de blog est mis en cause pour des propos diffamatoires d'un tiers (5 500 € d'avocat pris en charge).
- **Conseil** : un consultant en stratégie est attaqué en justice par un client en difficulté (frais de défense pris en charge, consultant mis hors de cause) ; une externalisation de paie provoque un redressement URSSAF (17 000 € indemnisés) ; une agence d'intérim place un agent qui commet un vol (80 000 € + 1 500 € d'expertise).
- **Médias / culture** : un site de cinéma illustre une critique avec la photo d'une actrice et le photographe l'attaque pour violation du droit d'auteur (Hiscox a négocié le rachat des droits, royalties non perçues comprises).
- **Tech** : création de site web (retard de livraison, défaut de fonctionnement, contrefaçon, atteinte à la vie privée) ; développeur d'applications (non-respect du cahier des charges, violation de droits d'auteur sur du code) ; conseil en SI (erreur d'appréciation des besoins) ; hébergeur (responsabilité LCEN, perte de données) ; maintenance (non-respect d'engagements de délai d'intervention).
- **Tourisme** : un vacancier est blessé lors d'une excursion organisée par un prestataire de l'assuré ; une chute de dromadaire pendant une excursion du forfait vendu ; une agence oublie de mentionner l'obligation de passeport et le client ne peut pas partir ; un fichier clients (dont numéros de passeport) est diffusé à des tiers.
- **Sécurité** : un chien de ronde bouscule une personne âgée ; une installation de 11 détecteurs au lieu de 13 nécessaires ; perte de clés (sans sous-limite) ; retard de signalement d'un incendie.

## 10. Parcours client `[À VALIDER]`

- **Souscription** : en ligne, via le parcours de souscription RC Pro (webapp). Le prospect saisit ses informations personnelles, obtient un tarif, puis signe et paie en ligne. Un conseiller peut accompagner par téléphone.
- **Déclarer un sinistre** : via l'app Nostrum Care. Aucune autre voie (e-mail, téléphone) n'est confirmée dans les documents fournis.
- **Utiliser la protection juridique** : procédure non documentée (l'e-mail de bienvenue contient encore des champs vides à ce sujet).
- **Espace assuré** : documents du contrat et attestation disponibles dans l'app Nostrum Care.

## 11. Cibles et profils de prospects `[MARKETING]`

À utiliser pour reconnaître un prospect et adapter le ton. Ne prouve jamais qu'une activité est assurable.

- **Cible prioritaire de la campagne** : freelances et indépendants de la tech, du marketing et de la communication.
- **Profils fréquents** : freelances et indépendants digitaux (25-40 ans, grandes villes), créatifs et professionnels tech (25-45 ans), professionnels du bien-être et des services personnels (28-50 ans), consultants et formateurs, petites entreprises.
- **Besoins récurrents** : une attestation rapide, un tarif abordable, la protection juridique contre les litiges clients, la couverture des erreurs professionnelles, parfois la couverture du matériel.
- **Deux grandes attentes** : ceux qui veulent seulement une attestation vite ; ceux qui veulent un conseiller au téléphone.

## 12. Grille de prix indicatifs `[CALCULETTE v0726]`

Générée depuis la Calculette Hiscox (Tarificateur RC Pro version Classique v0726), majoration de 10 % incluse. Prix « à partir de », jamais un devis. Elle se régénère avec le script `rcp_generate_grid.py` à chaque nouvelle version de la Calculette.

### Règle d'usage pour Gabriel
- Ne jamais annoncer moins de 19 € par mois : c'est le prix d'appel du site vitrine, et la grille ci-dessous affiche 17 € dans quelques cases (à confirmer, voir section 13).

- Ne donner qu'une fourchette « à partir de », arrondie, avec la formule : « le prix exact dépend de votre activité et de votre chiffre d'affaires, vous l'avez en 2 minutes sur le simulateur ».
- Valable uniquement si le chiffre d'affaires annuel est **≤ 140 000 €** (en dessous, le plancher de la Calculette s'applique à toutes les activités). Au-dessus : renvoyer vers le simulateur ou un conseiller, sans chiffre.
- Jamais de prix pour les options TDMI (matériel) et cyber, ni pour un chiffre d'affaires hors USA/Canada particulier.
- Si le prospect donne sa famille d'activité et son niveau de garantie, utiliser la ligne correspondante. Sinon donner la ligne d'entrée de sa famille.

### Prix annuel TTC (RC Pro + protection juridique incluse)

| Garantie (LOI) | TECH | MAC | MAN | MISC | BIE | MED |
|---|---|---|---|---|---|---|
| 50 000 € | 196 € | 192 € | 199 € | 166 € | 166 € | 192 € |
| 100 000 € | 417 € | 230 € | 269 € | 199 € | 199 € | 230 € |
| 200 000 € | 601 € | 464 € | 403 € | 325 € | 251 € | 464 € |
| 300 000 € | 746 € | 643 € | 540 € | 468 € | 336 € | 643 € |
| 500 000 € | 1 092 € | 975 € | 870 € | 798 € | 551 € | 975 € |
| 750 000 € | 1 381 € | 1 318 € | 925 € | 1 029 € | 787 € | 1 318 € |
| 1 000 000 € | 1 670 € | 1 682 € | 1 090 € | 1 249 € | 1 079 € | 1 682 € |

### Prix mensuel TTC approximatif (annuel x 1,232 / 12)

| Garantie (LOI) | TECH | MAC | MAN | MISC | BIE | MED |
|---|---|---|---|---|---|---|
| 50 000 € | 20 € | 20 € | 20 € | 17 € | 17 € | 20 € |
| 100 000 € | 43 € | 24 € | 28 € | 20 € | 20 € | 24 € |
| 200 000 € | 62 € | 48 € | 41 € | 33 € | 26 € | 48 € |
| 300 000 € | 77 € | 66 € | 55 € | 48 € | 35 € | 66 € |
| 500 000 € | 112 € | 100 € | 89 € | 82 € | 57 € | 100 € |
| 750 000 € | 142 € | 135 € | 95 € | 106 € | 81 € | 135 € |
| 1 000 000 € | 171 € | 173 € | 112 € | 128 € | 111 € | 173 € |

### TECH, garantie 100 000 €, chiffre d'affaires ≤ 70 000 € (paliers spéciaux)

| Chiffre d'affaires | Annuel TTC | Mensuel TTC |
|---|---|---|
| moins de 30 000 € | 199 € | 20 € |
| 30 000 à 50 000 € | 258 € | 27 € |
| 50 000 à 70 000 € | 318 € | 33 € |

Attention : sur ces paliers la Calculette n'applique pas la majoration de 10 % (voir points ouverts).

### TAG et SECU

| Famille | Garantie (LOI) | Annuel TTC | Mensuel TTC | Franchise RC Pro |
|---|---|---|---|---|
| TAG | 1 500 000 € | 914 € | 94 € | 1 500 € |
| TAG | 2 000 000 € | 1 260 € | 129 € | 2 000 € |
| TAG | 3 000 000 € | 1 549 € | 159 € | 3 000 € |
| SECU | 300 000 € | 927 € | 95 € | 1 500 € |
| SECU | 400 000 € | 1 433 € | 147 € | 1 500 € |
| SECU | 500 000 € | 1 664 € | 171 € | 1 500 € |
| SECU | 750 000 € | 2 184 € | 224 € | 1 500 € |
| SECU | 1 000 000 € | 2 415 € | 248 € | 1 500 € |

SECU : le plancher n'est garanti que jusqu'à 180 000 € de chiffre d'affaires.

### Option RC Exploitation (RCE), prix minimum annuel TTC à ajouter

| TECH | MAC | MAN | MISC | BIE | MED | TAG | SECU |
|---|---|---|---|---|---|---|---|
| 63 € | 50 € | 60 € | 60 € | 60 € | 50 € | 126 € | 126 € |

### Franchise
- 0 € en RC Pro et RCE si le chiffre d'affaires est ≤ 1,5 M€ et la garantie ≤ 1 M€, sauf SECU (1 500 € toujours). Au-delà (donc pour TAG, dont la garantie démarre à 1,5 M€), une franchise s'applique, voir tableau TAG et SECU.

## 13. Points ouverts et conflits à trancher avant la mise en production

1. **Téléphone : résolu.** Le service client est commun à tous les produits (section 15). Les deux autres numéros trouvés dans les documents RC Pro ne sont pas utilisés.
2. **Cibles marketing contre exclusions Hiscox** : la fiche « Target Audience » cite avocats, comptables, agents immobiliers et professionnels de santé comme cible « industries réglementées ». Ils sont exclus en délégation (section 6). L'assistant suit les exclusions Hiscox.
3. **Statistiques de marché sans source** : « 49 % des indépendants ne sont pas assurés », « 13 % ne se prononcent pas », « plus de 60 % des freelances ont rencontré des problèmes de RC » (la source est marquée « source ? » dans le brouillon). La fiche « Discours » dit par ailleurs « 49 % de professionnels ont des métiers réglementés », ce qui attribue le même chiffre à deux réalités différentes. Aucun de ces chiffres n'est utilisable.
4. **Déclaration de sinistre et protection juridique** : contacts (e-mail, téléphone) non renseignés.
5. **Garanties additionnelles** (piratage de site, violation de données personnelles) : à confirmer dans les conditions générales.
6. **Franchise du TDMI** et des cas au-delà de 1,5 M€ de chiffre d'affaires : non documentées.
7. **Signification de « HC1 à HC4 »** : non définie.
8. **Fraîcheur** : les formations datent de 2024 ; la Calculette v0726 (2026) peut avoir changé les capacités et les activités proposées.
9. **Documents manquants** : conditions générales, conditions particulières et IPID Hiscox (RC Pro, RCE, TDMI). À ajouter en priorité, car ce sont eux qui font foi.
10. **Coefficient mensuel 1,232** de la grille (section 12) : vient des règles de bordereau, à confirmer sur un contrat mensuel réel.
11. **Palier TECH 100 k€ / CA ≤ 70 k€** : la Calculette n'applique pas la majoration de 10 % (formule du minimum). À confirmer avec Hiscox si c'est voulu.
12. **Niveau de garantie proposé par le parcours** (par défaut et en choix) : à aligner avec la grille.
14. **Prix d'appel** : le site annonce « à partir de 19 €/mois » alors que la grille (coefficient mensuel 1,232 non confirmé) donne 17 € pour certaines activités et garanties de 50 000 €. À rapprocher d'un prix réel.
13. **Fichiers vides ou non exploitables** : le compte rendu de synchronisation RC Pro est vide ; la fiche « Discours » est surtout des maquettes de landing page.

## 14. Glossaire

- **RCP / RC Pro** : responsabilité civile professionnelle.
- **RCE** : responsabilité civile exploitation.
- **PJ** : protection juridique.
- **TDMI** : garantie matériel (intitulé Hiscox « Tous Risques Matériel »).
- **IPID** : document d'information standardisé sur le produit d'assurance.
- **CG / CP** : conditions générales / conditions particulières.
- **LOI** : limite d'indemnité (montant maximum de garantie).
- **DINC** : dommages immatériels non consécutifs.
- **Préposé** : personne agissant pour le compte de l'assuré (salarié, collaborateur).
- **Famille d'activités** : TECH, MAC, MAN, MISC, MEDIA / MIC, TAG, SECU.

## 15. Contacts et liens `[MARKETING]`

- Service client, commun à tous les produits Nostrum Care : 01 62 45 01 05 (appel gratuit, du lundi au vendredi de 9h à 18h), hello@nostrumcare.fr
- Simulation et souscription en ligne : https://pro.nostrumcare.fr/
- Rendez-vous ou rappel d'un conseiller : https://meetings-eu1.hubspot.com/conseil/demande-de-rappel-nc-acv?utm_source=nostrumcare&utm_medium=ia-gabriel
- Page de présentation : https://nostrumcare.fr/responsabilite-civile-professionnelle/
- Ne jamais inventer ni modifier un lien. Ne jamais utiliser les liens des mutuelles pour Nostrum Pro.
