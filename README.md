================================================================================
AGREGATEUR D'ACTUALITES MONDIAL, COMMUNAUTAIRE, GRATUIT ET NEUTRE
================================================================================

Document de conception - Plan complet

================================================================================
1. VISION ET PHILOSOPHIE
================================================================================

Le projet est un agregateur d'actualites veritablement mondial, entierement
gratuit, sans inscription obligatoire, communautaire et totalement neutre.

Principes fondateurs :

- Zero opinion, zero modification, 100% tracabilite.
- Le site ne produit aucun contenu. Il agregue, classe et presente du contenu
  provenant de sources verifiees.
- Chaque contenu est affiche tel quel (titre, extrait, lien vers la source
  originale), attribue clairement a sa source, et classe automatiquement par
  categorie, geographie et type de media.
- Aucune connexion n'est requise pour consulter le site. Tout est accessible
  a tout le monde, tout le temps, sans restriction.
- Le modele s'inspire de Wikipedia : un bien commun, maintenu par sa
  communaute, au service de l'information.
- Aucun flux d'argent. Le site ne genere aucun revenu, ne recoit aucun don,
  ne vend aucun service. Il fonctionne uniquement grace au benevolat et aux
  ressources gratuites ou mises a disposition par la communaute.
- Le site est MONDIAL. Il n'est centre sur aucun pays. La France, le Japon,
  le Bresil, le Nigeria, le Canada ont tous exactement la meme importance.
  Chaque pays du monde a sa place, au meme niveau que les autres.

Ce que le site est :
- Un point d'acces unique vers toute l'actualite mondiale verifiable.
- Un outil de transparence et de lisibilite de l'information.
- Un projet communautaire ou chaque contributeur peut proposer des sources,
  signaler des problemes, ameliorer le classement.
- Un projet entierement benevole, sans aucune dimension commerciale ou
  financiere.
- Un site ou quand on fouille, on trouve TOUT. La quantite d'information
  disponible est immense. Chaque sujet, chaque pays, chaque type de media
  est couvert en profondeur.

Ce que le site n'est pas :
- Un media. Il ne redige rien, ne commente rien, ne prend aucune position.
- Un reseau social. Pas de likes, pas de commentaires d'opinion, pas de
  profils publics.
- Un produit commercial. Pas de publicite, pas d'abonnement, pas de mur
  payant, pas de dons, pas de mecenat, pas de subventions, aucun argent
  entrant ou sortant.
- Un site franco-centre ou anglo-centre. C'est un site pour le monde entier,
  dans toutes les langues.

Differences avec les sites existants :

Ground News : regroupe les sujets a partir de dizaines de milliers de sources
et montre qui couvre quoi. Mais il classe les sources sur un spectre politique
gauche/centre/droite, ce qui est deja une forme d'interpretation. Il est aussi
partiellement payant et tres centre sur les Etats-Unis. Notre projet ne classe
rien politiquement, est totalement gratuit et couvre le monde entier.

AllSides : etiquette le biais politique de chaque source et presente
plusieurs points de vue cote a cote. Gratuit mais tres americano-centre et
axe sur le spectre politique. Notre projet ne fait aucune analyse de biais,
il presente l'info brute.

Google Actualites : agregateur algorithmique qui personnalise l'information.
Pas communautaire, pas transparent, appartient a Google. Notre projet est
open source, communautaire, sans personnalisation et sans entreprise derriere.

Newsvoice : application communautaire qui agregue les sites d'info. Le plus
proche de notre concept communautaire. Mais pas aussi complet, pas aussi
mondial, et pas totalement sans argent.

Notre projet est unique parce qu'il combine : veritablement mondial (tous
les pays au meme niveau) + communautaire type Wikipedia + neutralite absolue
+ couverture massive (on trouve TOUT) + open source + zero flux financier +
transcription automatique de tous les contenus audio et video.


================================================================================
2. DIMENSION MONDIALE
================================================================================

Le site est concu des le depart comme un projet mondial. Aucun pays n'est
privilegie. Aucune region n'est le "centre" du site.

A. Couverture geographique

Chaque pays du monde a :
- Sa propre page pays, accessible depuis la carte du monde ou depuis la
  navigation par continent/pays.
- Ses propres sources locales integrees (medias nationaux, agences de presse
  locales, institutions locales).
- Ses propres sous-categories (politique locale, economie locale, societe
  locale, etc.).

Les pays sont organises par continent :
- Afrique (54 pays, chacun avec sa page).
- Amerique du Nord (3 pays + territoires).
- Amerique Centrale et Caraibes (tous les pays et territoires).
- Amerique du Sud (12 pays).
- Asie (49 pays, chacun avec sa page).
- Europe (44 pays, chacun avec sa page).
- Oceanie (14 pays + territoires).
- Moyen-Orient (traite comme region transversale si pertinent).

Objectif : qu'un utilisateur au Senegal trouve autant d'informations sur
son pays qu'un utilisateur en Allemagne sur le sien. La couverture depend
du nombre de sources disponibles, mais l'effort de recherche et d'integration
est le meme pour tous les pays.

B. Multilinguisme

- L'interface du site est disponible en plusieurs langues (a terme, le
  maximum possible).
- Les contenus agreges restent dans leur langue d'origine. Un article en
  japonais reste en japonais, un article en arabe reste en arabe.
- Un filtre par langue permet a l'utilisateur de voir uniquement les contenus
  dans les langues qu'il comprend.
- A terme, un outil de traduction automatique (optionnel) peut etre propose
  pour afficher une version traduite d'un titre ou d'un extrait (en
  indiquant clairement que c'est une traduction automatique, pas le texte
  original).

C. Sources locales

Pour chaque pays, la communaute est invitee a proposer les sources locales
fiables et neutres :
- Agences de presse nationales (exemple : MAP pour le Maroc, Bernama pour
  la Malaisie, Prensa Latina pour Cuba, etc.).
- Medias publics nationaux (section info factuelle uniquement).
- Institutions gouvernementales (communiques officiels, donnees ouvertes).
- Organismes regionaux (Union Africaine, ASEAN, Mercosur, etc.).

L'objectif est d'avoir au minimum 5 a 10 sources locales par pays, et
beaucoup plus pour les pays ou les medias sont nombreux.

D. Equite de traitement

- La page d'accueil n'est pas centree sur un pays. Les sujets affiches "a
  la une" sont determines par le nombre de sources qui en parlent dans le
  monde entier, pas par une region specifique.
- Si un utilisateur veut se concentrer sur un pays ou une region, il utilise
  les filtres ou la navigation geographique.
- Les algorithmes de classement ne privilegient aucune zone geographique.
- La communaute veille activement a ce que les pays sous-representes soient
  mieux couverts, en recherchant et proposant des sources locales.


================================================================================
3. ACCES ET INSCRIPTION
================================================================================

Consultation du site :
- 100% gratuit.
- Aucune inscription requise.
- Aucun mur payant, aucune limitation de consultation.
- Tout le contenu agrege est visible par tous, a tout moment.
- Aucune personnalisation basee sur un profil ou des donnees utilisateur.
  Tout le monde voit la meme chose (sauf utilisation des filtres manuels).

Compte contributeur (optionnel) :
- L'inscription est uniquement necessaire pour ceux qui souhaitent contribuer
  au projet (proposer des sources, signaler des erreurs, participer a la
  moderation, voter sur les propositions, etc.).
- L'inscription est gratuite, simple, et ne demande qu'un minimum
  d'informations (pseudo, email, mot de passe).
- Un contributeur n'a aucun avantage en termes de consultation. Il a
  simplement acces aux outils communautaires.

Niveaux de contributeurs (systeme de confiance progressif) :
- Nouveau contributeur : peut proposer des sources et signaler des problemes.
  Ses propositions sont soumises a validation.
- Contributeur actif : apres un certain nombre de contributions validees, il
  peut voter sur les propositions des autres et participer aux discussions
  internes.
- Moderateur communautaire : elu ou designe par la communaute. Il valide ou
  refuse les propositions de sources, gere les signalements, veille au respect
  de la charte.
- Moderateur regional : un type de moderateur specialise dans une zone
  geographique. Il connait les medias locaux et aide a evaluer les sources
  de sa region. L'objectif est d'avoir des moderateurs regionaux pour chaque
  continent au minimum, et idealement pour chaque grande region du monde.
- Administrateur : equipe fondatrice. Gere l'infrastructure, les decisions
  techniques et les cas litigieux. Dernier recours. Benevole comme tous les
  autres.


================================================================================
4. FONCTIONNEMENT COMMUNAUTAIRE
================================================================================

Le modele communautaire est au coeur du projet. Tout repose sur le benevolat.

A. Proposition de sources

N'importe quel contributeur inscrit peut proposer l'ajout d'une nouvelle source
d'information. La proposition doit inclure :
- Le nom du media ou de la source.
- Le lien vers le site ou le flux.
- Le type de source (agence de presse, journal, chaine TV, podcast,
  institution, etc.).
- Le pays d'origine.
- La langue principale du contenu.
- Une justification (pourquoi cette source est fiable, neutre et pertinente).

La proposition est ensuite soumise a un processus de validation communautaire :
- Discussion ouverte aux contributeurs actifs et moderateurs (en priorite les
  moderateurs regionaux de la zone concernee).
- Vote communautaire (pour/contre/neutre).
- Verification par les moderateurs selon la charte de fiabilite et de
  neutralite (voir section 7).
- Decision finale : acceptee, refusee, ou mise en attente avec demande de
  precisions.

B. Signalement de problemes

Tout visiteur (meme sans compte) peut signaler un probleme via un formulaire
simple :
- Lien mort ou source inaccessible.
- Contenu inapproprie ou ne correspondant pas a de l'information factuelle
  et neutre.
- Erreur de categorisation.
- Source qui ne respecte plus les criteres de fiabilite ou de neutralite.

Les contributeurs inscrits peuvent en plus :
- Signaler avec un commentaire detaille.
- Suivre l'evolution de leur signalement.

C. Gouvernance

La gouvernance est transparente et documentee publiquement.
- Les regles du site sont definies dans une charte publique, modifiable par
  proposition communautaire (comme les politiques de Wikipedia).
- Les decisions importantes (ajout/retrait de source majeure, changement de
  regles, evolution technique) sont soumises a vote communautaire.
- Les comptes rendus des decisions sont publies dans un journal de bord
  accessible a tous.
- Aucune decision editoriale n'est prise en coulisse.
- Aucune personne ni entite n'a plus de pouvoir qu'une autre en dehors du
  systeme de niveaux defini par la communaute.
- La gouvernance est elle aussi mondiale : les decisions ne sont pas prises
  par un groupe d'un seul pays. Les moderateurs regionaux representent la
  diversite du monde.

D. Transparence totale

- Le code source du site est open source (accessible sur GitHub ou equivalent).
- Les algorithmes de classement et de categorisation sont documentes
  publiquement.
- Les statistiques du site (nombre de sources, de contributions, de
  signalements, repartition par pays) sont publiques.
- Il n'y a aucune finance a rendre transparente puisqu'il n'y a aucun flux
  d'argent. Si des couts d'hebergement existent, ils sont pris en charge
  directement par des benevoles ou via des services gratuits, et cela est
  documente publiquement.


================================================================================
5. MODELE SANS ARGENT
================================================================================

Le projet ne fonctionne avec aucun argent. Aucun flux financier n'existe,
ni entrant ni sortant.

A. Principes

- Aucune publicite.
- Aucun don, aucune cagnotte, aucun Patreon, aucun systeme de contribution
  financiere.
- Aucun abonnement, aucune offre premium, aucun service payant.
- Aucune subvention, aucune bourse, aucun mecenat.
- Aucun partenariat commercial ou financier d'aucune sorte.
- Aucune vente de donnees, de services ou de quoi que ce soit.
- Le site ne possede aucun compte bancaire, aucune tresorerie, aucun budget.

B. Comment ca fonctionne sans argent

Hebergement :
- Utilisation de services d'hebergement gratuits (GitHub Pages, Vercel free
  tier, Cloudflare free tier, Netlify free tier, etc.).
- Si le trafic depasse les limites gratuites, des benevoles peuvent heberger
  des instances sur leurs propres serveurs (modele distribue/federe).
- Possibilite d'utiliser des hebergements gratuits pour projets open source
  (beaucoup de fournisseurs offrent des credits gratuits aux projets open
  source reconnus).

Infrastructure :
- Base de donnees hebergee sur des services gratuits (Supabase free tier,
  PlanetScale free tier, ou auto-heberge par un benevole).
- CDN gratuit (Cloudflare).
- Domaine : un benevole achete le nom de domaine (cout minime, quelques euros
  par an) ou utilisation d'un domaine gratuit si necessaire.

Transcription :
- Utilisation de Whisper, le modele open source d'OpenAI, sous licence MIT,
  entierement gratuit. Il transcrit l'audio dans environ 99 langues. On peut
  le telecharger et le faire tourner en local sans aucun cout par minute. Les
  benevoles peuvent faire tourner Whisper sur leurs propres machines.

Code :
- Tout le developpement est benevole.
- Le code est open source, chacun peut contribuer.

Moderation :
- Toute la moderation est benevole.
- Le systeme de niveaux permet de repartir la charge entre les contributeurs
  actifs.

C. Durabilite du modele

Ce modele est le meme que celui de nombreux projets open source qui
fonctionnent sans argent depuis des annees. La durabilite repose sur :
- Une communaute active et motivee, repartie dans le monde entier.
- Une architecture technique legere et peu couteuse.
- L'utilisation maximale de services gratuits et d'outils open source.
- La decentralisation : si un benevole part, un autre peut prendre le relais.


================================================================================
6. ARCHITECTURE DU SITE
================================================================================

A. Page d'accueil

La page d'accueil est le point d'entree principal. Elle n'est centree sur
aucun pays.

En haut :
- Logo et nom du site.
- Barre de recherche universelle (rechercher dans toutes les sources, tous les
  types de contenu, tous les pays, toutes les langues).
- Filtres rapides : par pays, par continent, par langue, par type de contenu
  (article, video, podcast, donnee officielle), par date, par source.
- Selecteur de langue pour l'interface du site.

Bandeau en direct :
- Une zone dediee aux informations de derniere minute (breaking news) du
  monde entier.
- Alimentee automatiquement par les agences de presse et sources les plus
  reactives, sans privilegier aucune region.

Section "A la une mondiale" :
- Les 10 a 15 sujets les plus couverts du moment a l'echelle mondiale,
  toutes sources confondues.
- Chaque sujet affiche le nombre de sources qui le couvrent, les pays
  concernes, et un lien vers la page sujet detaillee.

Section "Tendances" :
- Les sujets qui montent en couverture dans le monde (augmentation du nombre
  de sources qui en parlent).

Section "Par continent" :
- Un apercu rapide de l'actualite de chaque continent (Afrique, Ameriques,
  Asie, Europe, Oceanie, Moyen-Orient).
- Chaque bloc continental montre les 3 a 5 sujets les plus couverts de la
  zone.

Apercu des categories thematiques :
- Un bloc par grande categorie (politique, economie, tech, sport, etc.) avec
  les 3 dernieres actualites mondiales de chaque categorie.

Flux videos :
- Les dernieres videos d'actualite provenant des sources integrees du monde
  entier (chaines YouTube d'info, sites de chaines TV, etc.).

Carte du monde interactive :
- Une carte cliquable. Cliquer sur un pays affiche les actualites de ce pays.
- Cliquer sur un continent affiche l'apercu du continent.
- Code couleur possible : intensite de couverture (plus un pays a
  d'actualites en cours, plus il est colore).

B. Pages pays

Chaque pays a sa propre page dediee, organisee ainsi :

En haut :
- Nom du pays, drapeau, continent.
- Nombre de sources locales integrees pour ce pays.
- Lien vers la liste des sources locales et leurs fiches.

Contenu :
- Toutes les actualites concernant ce pays, classees par date.
- Sous-categories locales : politique nationale, economie, societe, sport,
  culture, etc.
- Sources locales et sources internationales couvrant ce pays.
- Filtres : par type de contenu, par source, par date, par langue.

C. Pages categories thematiques

Chaque grande categorie a sa propre page. Une page categorie affiche les
actualites mondiales de la categorie, avec possibilite de filtrer par pays,
continent, langue, source, date.

Liste des grandes categories :

Politique : actualites politiques mondiales, par pays.

Economie : marches financiers, entreprises, emploi, cryptomonnaies,
immobilier, commerce international, par pays et mondial.

Environnement : climat, energie, biodiversite, catastrophes naturelles,
pollution, transition ecologique, par pays et mondial.

Tech et Science : intelligence artificielle, espace, sante et medecine,
innovation, cybersecurite, recherche scientifique.

Sport : football, tennis, basketball, formule 1, rugby, jeux olympiques,
athletisme, cricket, baseball, sports de combat, et tous les autres sports
pratiques dans le monde.

Culture : cinema, musique, livres, jeux video, art, theatre, mode.

Societe : education, justice, faits divers, droits humains, immigration,
sante publique.

Monde : navigation par continent et par pays.

Fact-checking : contenus provenant exclusivement des sites de verification
des faits du monde entier.

D. Page sujet (fonctionnalite centrale)

C'est la fonctionnalite la plus importante du site. Quand un meme evenement
est couvert par plusieurs sources, le site le detecte et regroupe tout sur
une seule page.

Une page sujet contient :

Titre de l'evenement (genere automatiquement a partir des titres des
sources).

Pays concernes par l'evenement.

Nombre de sources couvrant ce sujet.

Section articles : liste de tous les articles de presse qui couvrent le
sujet, avec pour chacun le nom de la source, le pays de la source, la
langue, le titre de l'article, un court extrait (snippet) et le lien direct
vers l'article original.

Section videos : toutes les videos liees au sujet. Chaque video affiche :
le titre, la source, la date, un extrait texte (genere par transcription
automatique, voir section 8), et le lecteur integre (embed) ou le lien
direct. Nom de la source et date pour chaque video.

Section podcasts et audio : emissions de radio ou podcasts ayant traite le
sujet. Chaque contenu audio affiche : le titre, la source, la date, un
extrait texte (genere par transcription automatique), et le lecteur integre
ou le lien direct.

Section donnees officielles : si le sujet concerne des chiffres (economie,
sante, demographie, etc.), liens vers les sources de donnees officielles
(statistiques nationales, OMS, Eurostat, Banque Mondiale, etc.).

Frise chronologique : une timeline automatique qui montre comment le sujet
a evolue dans le temps, basee sur les dates de publication des differentes
sources.

E. Fiche source

Chaque source presente sur le site a sa propre fiche, accessible par tous.
Cette fiche contient :
- Nom de la source.
- Pays d'origine.
- Langue(s) du contenu.
- Type (agence de presse, quotidien, hebdomadaire, chaine TV, radio, podcast,
  institution, organisme international, etc.).
- Proprietaire ou actionnariat (qui possede ce media).
- Mode de financement du media (public, prive, abonnements, publicite, etc.).
- Indicateur de neutralite : explication de pourquoi cette source est
  consideree comme neutre et factuelle.
- Site officiel.
- Date d'ajout sur le site.
- Historique communautaire (qui a propose la source, quand, resultat du vote).
- Nombre de contenus agreges depuis l'ajout.

F. Page de recherche

La recherche permet de trouver n'importe quel contenu agrege sur le site.
- Recherche par mots-cles (dans les titres, extraits, tags, et dans les
  transcriptions de videos et podcasts).
- Filtres avances : date, source, categorie, pays, continent, langue, type
  de contenu.
- Resultats classes par pertinence ou par date.

G. Pages communautaires

Espace contributeurs :
- Liste des propositions de sources en cours (classees par pays/region).
- Historique des propositions (acceptees, refusees).
- Signalements en cours.
- Journal de bord des decisions.
- Charte du site (neutralite + fiabilite).
- Guide du contributeur.
- Tableau de bord communautaire : statistiques sur la couverture par pays
  (quels pays sont bien couverts, lesquels manquent de sources, appels a
  contributions).

H. Page "A propos"

- Presentation du projet et de sa philosophie.
- Charte de neutralite.
- Charte de fiabilite des sources.
- Explication du fonctionnement technique (vulgarisee), incluant le systeme
  de transcription.
- Equipe fondatrice (tous benevoles).
- Lien vers le code source (open source).
- Explication du modele sans argent.
- Statistiques mondiales : nombre de pays couverts, nombre de sources par
  pays, nombre total de contenus agreges.


================================================================================
7. CHARTE DE FIABILITE ET DE NEUTRALITE DES SOURCES
================================================================================

Une source ne peut etre integree que si elle remplit TOUS les criteres
suivants. Ces criteres s'appliquent de la meme maniere a tous les pays.

A. Criteres de fiabilite

Critere 1 - Professionnalisme :
La source doit disposer d'une redaction professionnelle identifiable, composee
de journalistes ou de professionnels de l'information.

Critere 2 - Deontologie :
La source doit etre signataire ou adherente a des chartes deontologiques
reconnues dans son pays ou au niveau international (Charte de Munich, codes
de deontologie nationaux, etc.) ou demontrer un engagement equivalent.

Critere 3 - Transparence :
La source doit rendre publiques les informations sur son financement, son
actionnariat ou son mode de gouvernance.

Critere 4 - Historique :
La source doit avoir un historique verifiable et suffisamment long pour
evaluer sa fiabilite. Les sites recents ou obscurs ne sont pas acceptes
sauf s'ils emanent d'une institution reconnue.

Critere 5 - Reconnaissance :
La source doit etre reconnue par des organismes professionnels ou
institutionnels dans son pays d'origine (conseils de presse, associations
de journalistes, etc.).

B. Criteres de neutralite

Critere 6 - Factualite pure :
La source doit produire du contenu strictement factuel. Les articles doivent
rapporter des faits, pas des analyses subjectives, des editoriaux ou des
opinions.

Critere 7 - Absence de ligne editoriale partisane :
La source ne doit pas avoir de positionnement politique, ideologique ou
partisan revendique ou identifiable. Si une source est reconnue comme
penchant vers un bord politique (meme legerement), elle n'est pas acceptee.

Critere 8 - Ton neutre :
Le ton des contenus de la source doit etre neutre et descriptif, sans
sensationnalisme, sans formulations orientees, sans titres racoleurs.

Critere 9 - Separation stricte info/opinion :
Si la source produit a la fois de l'information et de l'opinion, seuls les
contenus clairement identifies comme informatifs et factuels peuvent etre
agreges. Les editoriaux, chroniques, tribunes, billets d'humeur et analyses
personnelles ne sont jamais agreges.

C. Sources privilegiees (dans tous les pays)

- Les agences de presse (AFP, Reuters, AP, et toutes les agences de presse
  nationales du monde).
- Les institutions officielles (gouvernements, parlements, organismes
  statistiques nationaux, organisations internationales).
- Les services publics d'information (dans leur dimension factuelle).
- Les sites de fact-checking reconnus dans chaque pays.
- Les sources de donnees ouvertes.

D. Sources exclues (dans tous les pays)

- Les medias avec une ligne editoriale partisane revendiquee ou reconnue.
- Les medias d'Etat sans independance editoriale (dans tous les pays).
- Les sources satiriques.
- Les blogs personnels.
- Les chaines YouTube personnelles ou les comptes de createurs de contenu (hors journaliste).
- Les influenceurs.
- Les tabloids et medias sensationnalistes.
- Toute source melangeant faits et opinions sans distinction claire.

E. Adaptation aux contextes locaux

Les criteres sont universels mais leur application tient compte du contexte
de chaque pays :
- Dans les pays ou la presse est moins developpee, les moderateurs regionaux
  evaluent les sources locales avec la meme grille mais en tenant compte
  des realites locales.
- Dans les pays ou la liberte de la presse est limitee, les sources
  officielles etatiques sont integrees avec une mention claire de leur nature
  (comme pour tout media d'Etat).
- Les indices de liberte de la presse (Reporters Sans Frontieres, Freedom
  House) peuvent etre affiches a titre informatif sur les fiches sources,
  sans que cela constitue un jugement de la part du site.

F. Retrait d'une source

Une source peut etre retiree si :
- Elle ne respecte plus les criteres ci-dessus.
- Plusieurs signalements communautaires concordants demontrent un probleme
  de neutralite ou de fiabilite.
- La communaute vote son retrait apres discussion.
Le retrait est documente dans le journal de bord.


================================================================================
8. SYSTEME DE TRANSCRIPTION AUTOMATIQUE
================================================================================

C'est une fonctionnalite essentielle du site. Elle permet de traiter les
contenus video et audio exactement comme les articles texte : on en extrait
un titre, un extrait, des mots-cles, et le texte complet est indexe pour la
recherche.

A. Pourquoi c'est necessaire

Les articles texte ont deja un titre, un extrait, un corps de texte. On peut
les lire, les classer, les chercher facilement.

Les videos et les podcasts, par defaut, sont des "boites noires" : on sait
qu'ils existent mais on ne sait pas ce qu'ils contiennent sans les regarder
ou les ecouter en entier. C'est un probleme pour un agregateur qui veut
etre exhaustif.

La transcription automatique permet de :
- Extraire un titre et un extrait texte de chaque video et podcast.
- Classer automatiquement le contenu par categorie et par sujet.
- Regrouper les videos et podcasts avec les articles texte qui traitent du
  meme sujet.
- Rendre les videos et podcasts cherchables par mots-cles.
- Generer des tags automatiques.
- Offrir a l'utilisateur un apercu texte de ce que contient la video ou le
  podcast avant de le regarder ou l'ecouter.

B. Comment ca fonctionne

Etape 1 - Recuperation du contenu audio/video :
Le site recupere les contenus video et audio des sources integrees via les
methodes habituelles (API YouTube, flux RSS de podcasts, embeds, etc.).

Etape 2 - Obtention de la transcription :
Deux cas de figure :

Cas 1 : La transcription existe deja.
- YouTube propose par defaut une retranscription automatique pour la plupart
  des videos. On peut la recuperer via l'API YouTube.
- Certains podcasts fournissent une transcription dans leur flux RSS ou sur
  leur site.
- Certaines chaines TV publient le texte de leurs reportages sur leur site.
Dans ces cas, on utilise directement la transcription existante.

Cas 2 : La transcription n'existe pas.
- On utilise Whisper, le modele open source de reconnaissance vocale d'OpenAI.
  Whisper est entierement gratuit, sous licence MIT, et peut etre telecharge
  et utilise en local sans aucun cout. Il transcrit l'audio dans environ 99
  langues avec une precision proche de l'humain, meme avec des accents, du
  bruit de fond et du vocabulaire technique.
- Whisper est disponible en plusieurs tailles de modele (tiny, base, small,
  medium, large). Les petits modeles tournent sur un simple ordinateur, les
  grands modeles necessitent un GPU.
- Les benevoles qui disposent de machines avec GPU peuvent faire tourner
  Whisper pour transcrire les contenus qui n'ont pas de transcription
  existante.
- Des outils communautaires comme faster-whisper et whisper.cpp permettent
  d'accelerer la transcription.

Etape 3 - Traitement de la transcription :
Une fois la transcription obtenue (qu'elle vienne de YouTube, du podcast ou
de Whisper), le systeme NLP du site la traite :
- Extraction du titre (si le contenu n'a pas de titre clair, le systeme
  genere un titre descriptif a partir du contenu).
- Extraction d'un extrait (les phrases les plus informatives et
  representatives du contenu).
- Categorisation automatique (politique, sport, economie, etc.).
- Tagging automatique (mots-cles).
- Regroupement avec les articles et autres contenus qui traitent du meme
  sujet.
- Indexation pour la recherche.

Etape 4 - Affichage sur le site :
Chaque video ou podcast est affiche avec :
- Le titre (original si disponible, sinon genere).
- La source et la date.
- Un extrait texte (quelques phrases representatives).
- Le lecteur integre (embed) ou le lien direct.
- La transcription complete, accessible en cliquant sur un bouton "Voir la
  transcription".
- Une mention claire : "Transcription automatique" ou "Transcription fournie
  par la source", pour que l'utilisateur sache d'ou vient le texte.

C. Transparence sur la transcription

- Chaque transcription est clairement identifiee comme automatique (generee
  par Whisper ou recuperee de YouTube) ou comme fournie par la source
  originale.
- Les transcriptions automatiques peuvent contenir des erreurs. Une mention
  le rappelle.
- Les contributeurs peuvent signaler des erreurs de transcription.
- Le site ne modifie jamais le contenu original. La transcription est un
  outil d'indexation et de consultation, pas une modification du contenu.

D. Impact sur le site

Grace a la transcription, le site peut :
- Indexer et rendre cherchable une quantite immense de contenu video et audio
  qui serait autrement invisible.
- Offrir une experience "on trouve TOUT" : meme les informations cachees dans
  une video de 30 minutes ou un podcast d'une heure sont accessibles par
  recherche textuelle.
- Traiter les videos et podcasts exactement comme les articles : meme
  categorisation, meme regroupement par sujet, meme tags, meme recherche.
- Permettre a un utilisateur qui ne peut pas regarder une video (connexion
  lente, environnement bruyant, handicap auditif) d'en lire le contenu.


================================================================================
9. TYPES DE SOURCES INTEGREES
================================================================================

Le site agregue les types de sources suivants, a condition qu'ils respectent
la charte de neutralite et de fiabilite. Pour CHAQUE type, l'objectif est
de couvrir le monde entier, pas seulement l'Europe ou l'Amerique du Nord.

Agences de presse (colonne vertebrale du site) :
Agences mondiales : AFP (France), Reuters (UK), Associated Press (USA).
Agences regionales et nationales : EFE (Espagne), ANSA (Italie), DPA
(Allemagne), Kyodo (Japon), Yonhap (Coree du Sud), PTI (Inde), Anadolu
(Turquie), MAP (Maroc), APS (Algerie), PANA (panafricaine), Prensa Latina
(Cuba), Xinhua (Chine, avec mention etatique), TASS (Russie, avec mention
etatique), Bernama (Malaisie), WAM (Emirats), IRNA (Iran, avec mention
etatique), et toutes les agences nationales identifiables dans le monde.
Les agences de presse sont les sources les plus brutes et factuelles. Elles
constituent le socle du site.

Presse ecrite et en ligne (section info factuelle uniquement) :
Uniquement les articles factuels et neutres. Objectif : couvrir la presse
de qualite de chaque pays, pas seulement les medias occidentaux.

Chaines de television et leurs sites (section info uniquement) :
Chaines d'information internationales et nationales du monde entier.
Integration via leurs flux RSS, API ou chaines YouTube officielles.
Uniquement les contenus d'information factuelle.
La transcription automatique permet de traiter ces contenus comme du texte.

Radio et podcasts (sections info uniquement) :
Bulletins d'information factuels du monde entier.
La transcription automatique permet de traiter ces contenus comme du texte.

Institutions et organismes officiels :
ONU, OMS, UNESCO, Union Europeenne, Union Africaine, ASEAN, Mercosur,
Banque Mondiale, FMI, gouvernements nationaux (communiques officiels),
parlements, organismes statistiques nationaux de chaque pays, etc.

Sites de donnees ouvertes :
Instituts de statistiques nationaux de chaque pays, Eurostat, base de donnees
de l'OMS, Banque Mondiale Open Data, Our World in Data, et les plateformes
de donnees ouvertes de chaque pays.

Sites de fact-checking :
AFP Factuel, Les Decodeurs (France), Snopes (USA), Full Fact (UK),
PolitiFact (USA), Africa Check (Afrique), Chequeado (Argentine), Aos Fatos
(Bresil), Alt News (Inde), et tous les fact-checkers reconnus dans le monde,
notamment ceux certifies par l'IFCN (International Fact-Checking Network).

Comptes officiels sur les reseaux sociaux :
Uniquement les comptes officiels d'institutions, de gouvernements, d'agences
de presse, d'organisations internationales. Jamais de comptes personnels,
jamais de comptes d'opinion.
Pour les contenus video provenant des reseaux sociaux, la transcription
automatique s'applique.


================================================================================
10. FONCTIONNALITES DETAILLEES
================================================================================

A. Fonctionnalites de consultation (accessibles a tous, sans compte)

Recherche universelle :
Taper un mot-cle ou un sujet pour obtenir tous les contenus agreges
(articles, videos, podcasts, donnees) de toutes les sources, de tous les
pays. La recherche s'effectue dans les titres, extraits, tags, ET dans les
transcriptions de videos et podcasts. Cela signifie qu'on peut trouver un
passage precis mentionne dans une video YouTube ou un podcast.

Filtrage avance :
Filtrer les resultats par pays, continent, langue, type de contenu, source
specifique, date ou periode.

Navigation par categorie :
Parcourir les actualites par grande categorie et sous-categorie.

Navigation geographique :
Utiliser la carte du monde interactive pour voir les actualites par pays ou
par region. Naviguer par continent puis par pays.

Page pays :
Consulter toutes les actualites d'un pays specifique, avec ses sources
locales.

Page sujet :
Consulter la page regroupant toutes les couvertures d'un meme evenement par
toutes les sources du monde. Articles, videos (avec transcription), podcasts
(avec transcription), donnees officielles, tout au meme endroit.

Frise chronologique :
Voir l'evolution d'un sujet dans le temps.

Fiches sources :
Consulter la fiche de transparence et de neutralite de n'importe quelle
source.

Flux en direct :
Suivre les informations de derniere minute en temps reel, du monde entier.

Transcriptions :
Lire la transcription complete de n'importe quelle video ou podcast agrege.

Mode sombre et mode clair :
Basculer entre les deux modes d'affichage.

Accessibilite :
Le site respecte les normes d'accessibilite (WCAG 2.1 niveau AA minimum)
pour etre utilisable par tous.

B. Fonctionnalites contributeur (necessitent un compte gratuit)

Proposer une source :
Soumettre une nouvelle source (de n'importe quel pays) pour evaluation
communautaire.

Voter sur les propositions :
Participer aux votes d'ajout ou de retrait de sources (apres un certain
nombre de contributions validees).

Signaler un probleme :
Signaler un lien mort, une erreur de classification, un contenu non conforme
a la charte de neutralite, une erreur de transcription.

Participer aux discussions :
Echanger avec les autres contributeurs sur les propositions et les
signalements.

Suivi des contributions :
Consulter l'historique de ses propres contributions et leur statut.

C. Fonctionnalites de moderateur communautaire

Valider ou refuser les propositions de sources.
Traiter les signalements.
Gerer les discussions communautaires.
Appliquer la charte de neutralite et de fiabilite.
Participer aux decisions de gouvernance.
Pour les moderateurs regionaux : veiller a la couverture de leur region et
evaluer les sources locales.


================================================================================
11. FONCTIONNEMENT TECHNIQUE
================================================================================

A. Comment le site recupere les informations

Flux RSS :
La majorite des medias proposent des flux RSS. Le site les lit a intervalles
reguliers (toutes les 5 a 15 minutes selon les sources).

API officielles :
API YouTube (videos + transcriptions disponibles), API de certaines agences
de presse, API de donnees ouvertes, API des reseaux sociaux pour les comptes
officiels.

Integration (embed) :
Pour les videos et certains podcasts, le site utilise les systemes
d'integration prevus par les plateformes (embed YouTube, Dailymotion,
Spotify, etc.).

B. Comment le site traite les contenus audio et video

Pour les videos YouTube :
1. Recuperation des metadonnees via l'API YouTube (titre, description, date,
   chaine).
2. Recuperation de la transcription automatique YouTube si disponible (via
   l'API).
3. Si pas de transcription YouTube, passage par Whisper (le modele open source
   de reconnaissance vocale d'OpenAI, gratuit, sous licence MIT, capable de
   transcrire environ 99 langues).
4. Traitement NLP de la transcription : extraction de titre, d'extrait, de
   mots-cles, categorisation, regroupement par sujet.
5. Indexation du texte pour la recherche.

Pour les podcasts :
1. Recuperation des metadonnees via le flux RSS du podcast (titre, description,
   date).
2. Si le podcast fournit une transcription, utilisation directe.
3. Sinon, telechargement de l'audio et passage par Whisper.
4. Meme traitement NLP que pour les videos.

Pour les videos sur les reseaux sociaux :
1. Recuperation des metadonnees via les API des plateformes.
2. Passage par Whisper si pas de transcription disponible.
3. Meme traitement NLP.

Outils de transcription utilises :
- Whisper (OpenAI) : modele principal. Open source, licence MIT, gratuit,
  environ 99 langues, precision proche de l'humain.
- faster-whisper : version optimisee de Whisper, plus rapide.
- whisper.cpp : version en C++ de Whisper, legere, peut tourner sur du
  materiel modeste.
- WhisperX : version avec alignement temporel precis.
Tous ces outils sont open source et gratuits.

C. Comment le site classe les informations

Categorisation automatique :
Un systeme NLP (traitement du langage naturel) analyse chaque contenu
(article, transcription de video, transcription de podcast) et le classe
automatiquement dans la categorie et les sous-categories appropriees. Il
attribue aussi des tags.

Regroupement par sujet :
Le systeme detecte quand plusieurs sources (articles, videos, podcasts)
parlent du meme evenement et les regroupe sur une meme page sujet. Ce
regroupement fonctionne a travers les langues (un article en espagnol et une
video en anglais sur le meme sujet sont regroupes).

Detection de langue :
Chaque contenu est automatiquement identifie dans sa langue.

Detection des doublons :
Le systeme evite d'afficher plusieurs fois le meme contenu.

Attribution geographique :
Le systeme identifie automatiquement le ou les pays concernes par chaque
contenu, pour l'afficher dans les bonnes pages pays.

D. Infrastructure technique

Front-end :
Framework web moderne (type Next.js ou Nuxt.js). Interface responsive.
Carte du monde interactive (Leaflet ou equivalent, open source et gratuit).

Back-end :
Serveur en Node.js ou Python. Base de donnees PostgreSQL ou equivalent.
Moteur de recherche type Meilisearch (open source et gratuit). Cache pour
les performances.

Transcription :
Whisper et ses variantes, tournes par des benevoles sur leurs machines ou
sur des services gratuits.

Hebergement (gratuit) :
Front-end : Vercel, Netlify ou Cloudflare Pages (tier gratuit).
Back-end : auto-heberge par des benevoles ou services gratuits.
Base de donnees : Supabase free tier ou auto-heberge.
CDN : Cloudflare gratuit.

Code source :
Public et ouvert, sur GitHub. Toute personne peut consulter le code,
proposer des ameliorations, ou verifier les algorithmes.


================================================================================
12. ASPECTS JURIDIQUES
================================================================================

A. Ce que le site peut faire

- Afficher le titre et un court extrait (snippet) de chaque article, avec un
  lien direct vers la source originale.
- Integrer (embed) des videos YouTube, Dailymotion et autres plateformes qui
  le permettent via leurs propres systemes d'integration.
- Utiliser les flux RSS publics mis a disposition par les medias.
- Utiliser les API officielles conformement a leurs conditions d'utilisation.
- Afficher les communiques et donnees publiques des institutions.
- Afficher les transcriptions automatiques des contenus audio/video pour
  faciliter l'indexation et la consultation (la transcription est un outil,
  pas une reproduction du contenu lui-meme).

B. Ce que le site ne peut pas faire

- Copier l'integralite d'un article ou d'un contenu protege par le droit
  d'auteur.
- Reproduire du contenu au-dela du droit de courte citation.
- Donner l'impression que le contenu agrege est produit par le site.
- Modifier, resumer ou reformuler le contenu des sources (les transcriptions
  automatiques sont des conversions de format, pas des modifications de
  contenu).

C. Points juridiques importants

Droits voisins :
La directive europeenne 2019/790 s'applique en Europe. D'autres pays ont
leurs propres legislations. Le site doit se conformer aux lois de chaque
juridiction et se limiter a ce que la loi autorise. Le caractere non
commercial et benevole du projet peut etre un argument mais ne constitue pas
une exemption automatique.

Transcriptions :
La publication de transcriptions automatiques de contenus video et audio
souleve des questions juridiques specifiques selon les pays. Il peut etre
necessaire de ne les utiliser qu'en interne (pour l'indexation et la
recherche) et de ne pas les afficher publiquement dans certains cas, ou de
ne les afficher que partiellement (extrait court).

Mentions legales :
Le site doit comporter des mentions legales conformement aux lois applicables.

Formulaire de retrait :
Toute source ou editeur peut demander le retrait de ses contenus du site.

Protection des donnees :
Respect du RGPD en Europe et des lois equivalentes dans les autres pays pour
les comptes contributeurs.

Statut juridique :
Le site peut etre porte par une association a but non lucratif ou un
collectif de personnes physiques, selon les lois du pays ou il est
enregistre.

Conseil :
Demander un avis juridique (meme benevole) pour securiser le projet,
notamment sur les droits voisins et la question des transcriptions.


================================================================================
13. PRINCIPES DE DESIGN
================================================================================

Sobriete :
Pas de couleurs criardes, pas de visuels tapageurs, pas de mise en page
sensationnaliste. Le site doit inspirer confiance et serieux.

Universalite :
Le design ne doit evoquer aucun pays, aucune culture specifique. Pas de
couleurs nationales dominantes, pas de symboles culturellement marques. Le
site est pour le monde entier.

Typographie :
Soignee, lisible, avec une hierarchie claire. Utilisation de polices qui
supportent tous les alphabets (latin, arabe, cyrillique, CJK, devanagari,
etc.) pour une experience multilingue fluide.

Densite et aeration :
Le site affiche beaucoup d'informations mais de maniere aeree et organisee.

Mode sombre et mode clair :
Les deux modes sont disponibles.

Responsive :
Le site s'adapte parfaitement aux ordinateurs de bureau, tablettes et
telephones.

Accessibilite :
WCAG 2.1 niveau AA minimum. Contrastes suffisants, navigation au clavier,
compatibilite avec les lecteurs d'ecran, textes alternatifs.

Zero distraction :
Aucune publicite, aucun popup, aucune notification intrusive, aucun
autoplay video non demande.

Performance :
Chargement rapide meme sur des connexions lentes. Architecture legere.


================================================================================
14. ROADMAP (PLAN DE DEVELOPPEMENT)
================================================================================

Le developpement est organise en grandes etapes successives. Aucune duree
fixe n'est imposee : chaque etape est terminee quand elle est prete, selon
la disponibilite des benevoles et l'avancement technique.

Etape 1 - Fondations (MVP)

- Definir et documenter la charte de neutralite et la charte de fiabilite.
- Selectionner 50 a 100 sources strictement neutres et factuelles, reparties
  dans le monde entier (au moins une agence de presse par continent, des
  institutions internationales, des sources de donnees ouvertes).
- Mettre en place le systeme d'agregation des flux RSS.
- Developper un front-end epure avec page d'accueil mondiale et pages
  categories.
- Creer la structure des pages pays (meme si beaucoup seront encore vides).
- Mettre en place une recherche simple.
- Rendre le site responsive.
- Creer les mentions legales et la page "A propos".
- Publier le code source en open source sur GitHub.
- Deployer sur un hebergement gratuit.

Etape 2 - Transcription et Intelligence

- Mettre en place le pipeline de transcription automatique (YouTube
  transcriptions + Whisper pour le reste).
- Mettre en place le systeme NLP de categorisation automatique.
- Developper le regroupement par sujet (clustering), y compris entre langues
  differentes.
- Creer les pages sujet multi-sources.
- Developper le tagging automatique.
- Integrer les videos avec titre et extrait generes par transcription.
- Integrer les podcasts avec titre et extrait generes par transcription.
- Ajouter des sources (objectif : 200 a 300 sources dans 50+ pays).
- Creer les fiches sources.
- Mettre en place le systeme de signalement.

Etape 3 - Communaute

- Developper le systeme d'inscription contributeur.
- Creer l'espace communautaire (propositions, votes, discussions).
- Mettre en place les niveaux de contributeurs, incluant les moderateurs
  regionaux.
- Developper les outils de moderation communautaire.
- Creer le journal de bord public.
- Rediger le guide du contributeur.
- Lancer un appel mondial a contributions pour recruter des benevoles sur
  tous les continents.
- Mettre en place le tableau de bord communautaire montrant la couverture
  par pays.

Etape 4 - Experience et Couverture

- Developper la carte du monde interactive.
- Creer les frises chronologiques par sujet.
- Ajouter le mode sombre.
- Optimiser l'accessibilite (audit WCAG).
- Optimiser les performances.
- Objectif : 500 a 800 sources dans 100+ pays.
- Commencer la traduction de l'interface dans les langues principales
  (anglais, francais, espagnol, arabe, chinois, portugais, russe, hindi).

Etape 5 - Croissance mondiale

- Objectif : 1000 a 2000 sources dans 150+ pays.
- Developper l'application mobile (PWA).
- Elargir l'equipe de moderateurs regionaux sur tous les continents.
- Traduire l'interface dans le maximum de langues.
- Ameliorer les algorithmes de regroupement multilingue et de transcription.
- Couvrir les sports, medias et cultures de chaque region du monde.
- Chercher des benevoles Whisper supplementaires (personnes disposant de GPU
  pour la transcription).


================================================================================
15. DEFIS A ANTICIPER
================================================================================

Volume de donnees :
Avec la transcription de videos et podcasts, le volume de texte a stocker et
indexer sera enorme. L'architecture doit etre prevue pour ca, tout en restant
dans les limites des services gratuits.

Transcription a grande echelle :
Transcrire des milliers de videos et podcasts necessite de la puissance de
calcul. Le modele distribue (benevoles avec GPU) est la solution sans argent,
mais il faut organiser la repartition du travail.

Couverture mondiale inegale :
Certains pays auront beaucoup de sources disponibles, d'autres tres peu. Il
faut accepter cette realite tout en travaillant activement a combler les
lacunes via la communaute et les moderateurs regionaux.

Doublons et bruit :
Beaucoup de medias reprennent les memes depeches d'agence. Le systeme de
deduplication et de clustering doit etre performant.

Regroupement multilingue :
Regrouper des articles en espagnol avec des videos en arabe et des podcasts
en anglais sur le meme sujet est techniquement complexe. Les modeles NLP
multilingues existent mais necessitent un travail d'integration important.

Neutralite reelle :
La neutralite absolue n'existe peut-etre pas, mais le site doit s'en
approcher au maximum. Le risque est de selectionner inconsciemment des
sources qui ont un biais non detecte, ou de sous-representer certaines
regions du monde.

Droits d'auteur et droits voisins :
Le cadre juridique varie selon les pays. La transcription automatique de
contenus audio/video ajoute une couche de complexite juridique supplementaire.

Limites des services gratuits :
Les services d'hebergement gratuits ont des limites. L'architecture doit etre
optimisee pour rester dans ces limites le plus longtemps possible.

Motivation des benevoles :
Sans argent, le projet repose entierement sur la motivation des benevoles du
monde entier. Il faut creer une communaute soudee et mondiale.

Abus communautaires :
Tentatives de manipulation (propositions de sources biaisees, votes
coordonnes, etc.). Le systeme de niveaux de confiance et la moderation
doivent etre robustes.

Maintenance des sources :
Les flux RSS changent, les API evoluent, les sites ferment. Monitoring
automatique necessaire.

Alphabets et langues :
Le site doit gerer correctement tous les alphabets et systemes d'ecriture
du monde (latin, arabe, cyrillique, chinois, japonais, coreen, devanagari,
thai, etc.). La recherche doit fonctionner dans toutes ces langues.

Censure et acces :
Dans certains pays, le site pourrait etre bloque ou censure. Prevoir des
solutions d'acces alternatif (miroirs, tor, etc.) si pertinent.


================================================================================
16. RESUME
================================================================================

Le projet est un agregateur d'actualites veritablement mondial qui :

- Est entierement gratuit et accessible sans inscription.
- Fonctionne sans aucun flux d'argent : pas de publicite, pas de dons, pas
  d'abonnement, pas de subvention, pas de mecenat, rien.
- Ne produit aucun contenu propre et ne modifie aucune information.
- Agregue des contenus (articles, videos, podcasts, donnees) provenant
  exclusivement de sources rigoureusement selectionnees selon une double
  charte de fiabilite ET de neutralite.
- Couvre TOUS les pays du monde au meme niveau, sans privilegier aucune
  region. Chaque pays a sa page, ses sources locales, son importance egale.
- Transcrit automatiquement les contenus video et audio grace a Whisper
  (open source, gratuit, environ 99 langues), ce qui permet d'extraire un
  titre, un extrait et des mots-cles de chaque video et podcast, de les
  rendre cherchables, et de les regrouper avec les articles texte sur le
  meme sujet.
- Offre une quantite immense d'information : quand on fouille, on trouve
  TOUT. Articles, videos, podcasts, donnees officielles, de tous les pays,
  dans toutes les langues, tous cherchables, tous classes, tous regroupes
  par sujet.
- Est maintenu et gouverne par sa communaute mondiale de contributeurs
  benevoles, avec des moderateurs regionaux sur chaque continent.
- Est entierement transparent : code open source, algorithmes documentes,
  decisions tracees.
- Repose entierement sur le benevolat et les ressources gratuites.

L'objectif est de devenir le point de reference mondial pour acceder a une
information complete, verifiable et neutre, de n'importe quel pays, dans
n'importe quelle langue, en un seul endroit, sans qu'un seul euro ne soit
jamais implique.
