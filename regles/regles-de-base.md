# JDR Wakfu : règles de base (version 0.10)

> Document de travail. Il pose le socle mécanique du jeu : caractéristiques, jets de dés, PA/PM/PW, points de vie, résolution des actions et du combat. Les classes, sorts, bestiaire et univers viendront s'y brancher.

---

## 1. Principes de conception

1. **Un seul jet pour tout** : 1d20 + modificateurs contre une difficulté. Facile à apprendre, facile à arbitrer.
2. **Le combat ressemble au jeu vidéo** : grille de cases, Points d'Action (PA) pour agir, Points de Mouvement (PM) pour se déplacer, Points de Wakfu (PW) pour les grands effets, positionnement (dos, tacle, ligne de vue) décisif.
3. **Les quatre éléments sont au cœur du système** : Terre, Feu, Eau, Air. Chaque sort a un élément, chaque personnage a des forces et des résistances élémentaires.
4. **On meurt rarement, on tombe souvent** : comme dans WAKFU, les héros vaincus sont ramenés par le Phénix, au prix d'une blessure.
5. **Des chiffres petits** : les valeurs restent lisibles de tête (caractéristiques de 0 à +5, dégâts de l'ordre de la dizaine).

---

## 2. Les caractéristiques

Chaque personnage possède six caractéristiques, notées par un **modificateur de 0 à +5** (jusqu'à +6 avec l'équipement légendaire).

| Caractéristique | Élément | Rôle en combat | Rôle hors combat |
|---|---|---|---|
| **Force** | Terre | Dégâts et précision des sorts Terre, Tacle | Soulever, casser, escalader, intimider |
| **Intelligence** | Feu | Dégâts et précision des sorts Feu, Initiative | Savoir, magie, enquête, artisanat complexe |
| **Chance** | Eau | Dégâts et précision des sorts Eau, Points de Destin | Fouille, jeux de hasard, prospection |
| **Agilité** | Air | Dégâts et précision des sorts Air, Défense, Esquive | Discrétion, acrobaties, adresse |
| **Vitalité** | (corps) | Points de Vie | Endurance, résister aux poisons et maladies |
| **Sagesse** | (Wakfu) | Points de Wakfu, résistance aux effets mentaux | Perception, volonté, intuition, empathie |

### Origine : les enfants des Dieux

Il n'y a **pas de races** dans ce jeu, seulement des **classes**. Dans le Monde des Douze, un enfant naît du Dieu de son père ou de sa mère : l'enfant de parents Iop devient un Iop, celui d'une mère Sadida et d'un père Crâ devient Sadida ou Crâ. La classe définit donc à la fois le peuple, l'apparence, la culture et les pouvoirs du personnage.

À la création, **le joueur choisit librement sa classe**. Les parents du personnage relèvent uniquement de son histoire (lore) et n'ont aucun effet de règle.

### Les Sans-classe

Un Dieu peut **renier** un fidèle qui bafoue ses principes (voir les principes de chaque Dieu dans le document des classes). Le renié devient **Sans-classe**.

**Reniement**
- Le MJ avertit d'abord le joueur par des présages (rêves, sorts qui faiblissent, malaise au temple). Le reniement tombe si le personnage persiste ou commet une faute grave.
- Le Sans-classe **perd** tout ce qui vient de son Dieu : bonus de caractéristique de classe, bonus de PV de classe, passif, résistances et sorts de classe.
- Il **garde** son niveau, ses caractéristiques, ses compétences, ses métiers, ses PV de base et ses Points de Wakfu (le Wakfu est la vie elle-même, pas un don divin).
- **Un enfant de Sans-classe naît Sans-classe.** Un joueur peut donc aussi créer un personnage Sans-classe dès le départ.

**Ce que garde un Sans-classe pour se battre**
- Il manie toutes les armes et ajoute son bonus de maîtrise à ses attaques d'arme.
- **Débrouillard** : +2 compétences et +1 métier.
- **Volonté propre** : avantage aux tests pour résister aux effets mentaux et divins.
- À chaque niveau où une classe gagnerait un sort, il gagne à la place **+2 PV** ou une **technique d'arme** (liste à écrire avec l'équipement).

**Allégeance**
- Un Sans-classe peut se rendre au **temple d'un Dieu** pour prouver son souhait d'allégeance, que ce soit le Dieu qui l'a renié ou un autre.
- Le Dieu, par ses prêtres, impose **trois épreuves** : une de **corps**, une d'**esprit** et une de **foi**, qui met à l'épreuve les principes de ce Dieu. Le MJ les construit comme une aventure à part entière.
- Si le Dieu le juge digne, le personnage reçoit sa **bénédiction** : il gagne la classe avec toutes les capacités correspondant à son niveau. Il perd alors les avantages de Sans-classe.
- En cas d'échec, il peut retenter l'épreuve plus tard, après avoir réparé sa faute ou fait ses preuves.

### Création

- Chaque personnage répartit **6 points** entre les six caractéristiques.
- Maximum **+3** dans une caractéristique à la création.
- La classe (voir document des classes) ajoute **+1** dans une caractéristique imposée ou au choix.

### Valeurs dérivées

| Valeur | Calcul |
|---|---|
| **Points de Vie (PV)** | 30 + 5 × Vitalité + bonus de PV de classe au niveau 1, puis + (6 + Vitalité) par niveau |
| **Points d'Action (PA)** | 6 |
| **Points de Mouvement (PM)** | 3 |
| **Points de Wakfu (PW)** | 3 + Sagesse (maximum) |
| **Défense** | 10 + Agilité + bonus d'armure (0 à +3) |
| **Initiative** | 1d20 + Intelligence |
| **Tacle** | 10 + Force + bonus de maîtrise |
| **Esquive** | 1d20 + Agilité + bonus de maîtrise |
| **Points de Destin** | 1 + Chance par séance |
| **Bonus de maîtrise** | selon le niveau (voir §9) |

Les PA, PM et PW de base évoluent ensuite par l'équipement, les sorts et la progression.

---

## 3. La résolution des actions

### Le test

Quand l'issue d'une action est incertaine et que l'échec a une conséquence intéressante, le joueur fait un **test** :

> **1d20 + caractéristique + bonus de maîtrise (si le personnage est compétent) ≥ Difficulté**

| Difficulté | Valeur | Exemple |
|---|---|---|
| Facile | 8 | Sauter un ruisseau |
| Moyenne | 12 | Crocheter une serrure simple |
| Difficile | 16 | Escalader une falaise sous la pluie |
| Très difficile | 20 | Convaincre un garde Brâkmarien de trahir |
| Héroïque | 25 | Traverser un portail de Zaap instable à la nage |

### Réussites et échecs critiques

- **20 naturel** : réussite critique. L'action réussit avec un bonus (effet supplémentaire, temps gagné, dégâts renforcés en combat).
- **1 naturel** : échec critique. L'action échoue avec une complication.

### Avantage et désavantage

Quand la situation aide ou gêne nettement le personnage, le MJ accorde un **avantage** (on lance 2d20 et on garde le meilleur) ou un **désavantage** (on garde le pire). Ils ne se cumulent pas et s'annulent l'un l'autre.

### Tests opposés

Deux personnages s'opposent (bras de fer, se cacher contre repérer) : chacun fait son test, le plus haut l'emporte. En cas d'égalité, le défenseur gagne.

### Attitude des PNJ

L'attitude d'un PNJ envers le groupe se lit sur une échelle à quatre crans : **hostile**, **méfiant**, **neutre**, **amical**. Un test social réussi (Persuasion, Intimidation, cadeau, service rendu) peut la faire monter d'un cran ; une offense la fait descendre. Un PNJ hostile ne rend aucun service, un PNJ amical aide dans la mesure de ses moyens.

### Points de Destin

Au début de chaque séance, un personnage reçoit **1 + Chance** Points de Destin. Dépenser 1 point permet de **relancer n'importe quel d20** que le personnage vient de lancer. Les points non utilisés sont perdus en fin de séance.

---

## 4. Les compétences

Une compétence est un domaine où le personnage est formé. S'il est compétent, il ajoute son **bonus de maîtrise** au test. Chaque personnage est formé dans **6 compétences** à la création : les **2 compétences de sa classe**, acquises d'office, et **4 au choix**. Un Sans-classe, qui n'a pas de compétences de classe, en choisit 6, plus 2 grâce à *Débrouillard*, soit **8**.

Il existe **27 compétences**. Leur liste complète, avec un descriptif de chacune, se trouve au chapitre 1 (`regles/creation-de-personnage.md`, étape 5).

| Caractéristique | Compétences |
|---|---|
| Force | Athlétisme, Intimidation |
| Agilité | Acrobaties, Discrétion, Escamotage, Monte, Spectacle |
| Intelligence | Arcanes, Baragouin, Bricolage, Enquête, Érudition |
| Chance | Baratin, Chasse au trésor, Fouille, Négoce, Tripot |
| Vitalité | Endurance, Ripaille, Roupillon |
| Sagesse | Almanax, Dressage, Intuition, Médecine, Perception, Persuasion, Survie |

La caractéristique est indicative : le MJ peut en demander une autre si la situation s'y prête (Intimidation par l'Intelligence pour une menace glaciale et calculée).

### Métiers

Les métiers du Monde des Douze (paysan, bûcheron, mineur, herboriste, pêcheur, trappeur, et leurs métiers d'artisanat associés) fonctionnent comme des compétences à part. Un personnage commence avec **1 métier**. Les règles de récolte et de fabrication feront l'objet d'un document séparé.

---

## 5. Le combat

### 5.1 Le terrain

- Le combat se joue sur une **grille de cases carrées**. Une case = environ 1,5 m.
- Les obstacles bloquent le passage ; certains bloquent aussi la **ligne de vue**.
- Les personnages ont une **orientation** (face, côtés, dos) choisie à la fin de leur tour.

### 5.2 Déroulement

1. **Placement** : le MJ désigne les zones de départ, chacun y place sa figurine.
2. **Initiative** : chaque combattant lance 1d20 + Intelligence. Les monstres identiques d'un même groupe peuvent partager un jet.
3. **Tours en alternance par camp**, comme dans le jeu vidéo : on classe les combattants de chaque camp par initiative décroissante, puis on alterne un combattant de chaque camp, en commençant par le camp dont le meilleur combattant a la plus haute initiative. Quand un camp n'a plus de combattant à faire jouer, les combattants restants de l'autre camp jouent à la suite.
4. Un **round** se termine quand tout le monde a joué. L'ordre reste le même d'un round à l'autre ; un combattant KO garde sa place mais passe son tour.

### 5.3 Le tour d'un combattant

Au début de son tour, le combattant récupère **tous ses PA et PM**, et **1 PW**. Les effets « au début du tour » (poison, soin continu) s'appliquent.

Pendant son tour, il dépense ses points dans l'ordre qu'il veut :

| Action | Coût |
|---|---|
| Se déplacer d'une case (y compris en diagonale sur grille carrée) | 1 PM |
| Lancer un sort | Coût du sort (en PA, parfois PM ou PW) |
| Attaque avec l'arme équipée | 3 PA (ou coût indiqué sur l'arme) |
| Utiliser un objet (potion, parchemin) | 2 PA |
| Interagir (ouvrir, ramasser, actionner) | 1 PA |
| Se relever | 2 PM |
| Changer d'arme | 1 PA |
| Parler | gratuit (quelques mots) |

Les PA et PM non dépensés sont perdus à la fin du tour. Un sort ne peut normalement être lancé que **2 fois par tour** et **1 fois par tour sur la même cible**, sauf mention contraire.

### 5.4 Tacle et Esquive

Un combattant **au contact** d'un ennemi (case adjacente, hors diagonale) est « taclé ». Pour quitter cette case :

- il fait un **test d'Esquive** : 1d20 + Agilité + maîtrise contre le **Tacle** du meilleur tacleur adjacent (10 + Force + maîtrise) ;
- **réussite** : il se déplace normalement ;
- **échec** : chaque ennemi adjacent lui fait perdre **1 PM** (et le déplacement coûte ce qui reste) ;
- **échec de 5 ou plus** : il perd tous ses PM restants.

Les téléportations et déplacements forcés (poussées, attirances) ne déclenchent pas de tacle.

La maîtrise figure des deux côtés : l'Esquive et le Tacle progressent ensemble, et c'est l'écart entre Agilité et Force qui décide.

### 5.5 Attaquer

Pour toucher avec un sort offensif ou une arme :

> **Jet d'attaque : 1d20 + caractéristique de l'élément + bonus de maîtrise ≥ Défense de la cible**

- La cible doit être **à portée** (en cases) et, sauf mention contraire, **en ligne de vue**.
- Les sorts de **zone** ne font pas de jet d'attaque : chaque cible dans la zone fait un **test d'Esquive** (1d20 + Agilité + maîtrise) contre **10 + caractéristique + maîtrise du lanceur**. Réussite : moitié des dégâts.
- Pour savoir si un sort de zone fait un **critique**, le lanceur lance aussi 1d20 : sur un **20 naturel**, les effets critiques du sort s'appliquent à toutes les cibles qui ont raté leur test.
- Les **soins** et **effets sur alliés** touchent automatiquement.

### 5.6 Dégâts

> **Dégâts = dés du sort + caractéristique de l'élément + bonus divers − résistance de la cible dans cet élément**

- Les dégâts ne descendent jamais sous 1 sur un coup réussi.
- **Position** : attaque de **flanc** +2 dégâts, attaque de **dos** +4 dégâts (on regarde l'orientation de la cible et la case de l'attaquant).
- **Critique** (20 naturel sur l'attaque, ou plage critique élargie par un équipement) : on lance **les dés de dégâts deux fois** et on ajoute les effets critiques du sort s'il en a.
- **Échec critique** (1 naturel) : le sort échoue, les PA sont dépensés.

### 5.7 Résistances élémentaires

Chaque combattant a une **résistance de 0 à 5 dans chaque élément** (Terre, Feu, Eau, Air), issue de sa classe et de son équipement. Elle se soustrait aux dégâts de cet élément. Certaines créatures sont **immunisées** (la résistance est alors ∞) ou **vulnérables** (dégâts × 2) à un élément.

### 5.8 Soins et Armure

- **Soins** = dés du sort + caractéristique de l'élément. On ne dépasse pas les PV maximum.
- **Armure** : des points temporaires qui absorbent les dégâts avant les PV. L'Armure ne se cumule pas (on garde la plus haute valeur) et disparaît à la fin du combat.

### 5.9 Points de Wakfu

Les PW représentent l'énergie vitale du Wakfu que le personnage canalise.

- Maximum : 3 + Sagesse.
- +1 PW au début de chaque tour de combat ; recharge complète après un repos court (voir §7).
- Ils payent les sorts puissants (« 3 PA + 2 PW »), certains effets de classe, et peuvent servir de **carburant d'urgence** : 1 PW = +1 PA pour ce tour, une seule fois par tour.

### 5.10 États

| État | Effet |
|---|---|
| **Affaibli** | Désavantage aux jets d'attaque |
| **Ralenti** | −1 PM (cumulable jusqu'à −3) |
| **Épuisé** | −1 PA (cumulable jusqu'à −3) |
| **Étourdi** | Perd son prochain tour (ne peut que réagir) |
| **Pesanteur** | Ne peut être ni téléporté, ni poussé, ni se téléporter |
| **Enraciné** | 0 PM, ne peut pas être déplacé |
| **Invisible** | Ne peut être ciblé directement ; désavantage aux attaques de zone contre lui ; se révèle en attaquant |
| **Empoisonné** | Subit X dégâts de l'élément indiqué au début de son tour |
| **Stabilisé** | Ne peut pas être déplacé de force |
| **Porté** | Transporté par un allié ou ennemi (façon Pandawa) ; se déplace avec lui, ne peut pas bouger seul |

Sauf mention contraire, un état dure **jusqu'à la fin du prochain tour de celui qui l'a infligé**.

---

## 6. Tomber au combat : KO, Phénix et Blessures

- À **0 PV**, un combattant est **KO**. Il reste allongé sur sa case (qui reste occupée) et ne peut rien faire.
- Il a **3 tours** avant que son âme ne quitte son corps. Tout **soin** ou le sort *Relever* d'un allié pendant ce délai le remet sur pied avec les PV soignés (1 PV minimum).
- Si personne ne le relève, il devient un **fantôme** : il est ramené à la **statue du Phénix** la plus proche après le combat, avec **1 Blessure**.
- **Blessure** : −1 à toutes les caractéristiques jusqu'à guérison (un repos long chez un soigneur ou dans une ville par Blessure). Trois Blessures cumulées : le personnage ne peut plus partir à l'aventure avant d'être soigné.
- **Mort définitive** : réservée aux lieux et adversaires où le Phénix ne peut rien (Stasis, Shukrute, rituel d'Ogrest…). Le MJ l'annonce avant la scène.

---

## 7. Récupération

| Repos | Durée | Effet |
|---|---|---|
| **Fin de combat** | immédiat | Armure et états temporaires disparaissent |
| **Repos court** | ~1 heure (repas, pause) | Récupère la moitié des PV max, tous les PW |
| **Repos long** | une nuit | Récupère tous les PV, tous les PW ; 1 Blessure si soigné en ville ou par un soigneur |

---

## 8. Format d'un sort

Tous les sorts du jeu suivront cette fiche, pour que les classes restent comparables.

> **Nom du sort** — Élément — Coût — Portée — Zone
> Effet principal (dégâts, soins, déplacement)
> Critique : effet supplémentaire
> Limites : lancers par tour, par cible, ligne de vue, portée modifiable

**Exemple (Iop)**

> **Épée Céleste** — Air — 3 PA — Portée 1 à 3, ligne droite — Zone : cible + 2 cases derrière
> Dégâts : 1d8 + Agilité (sort de zone, test d'Esquive pour moitié)
> Critique : la cible principale est poussée d'une case.
> Limites : 2 fois par tour.

**Repères d'équilibrage (niveau 1)**

| Coût | Dégâts indicatifs |
|---|---|
| 2 PA | 1d6 |
| 3 PA | 1d8 ou 1d6 + effet |
| 4 PA | 2d6 |
| 5 PA | 2d8 ou 2d6 + effet |
| +1 à 2 PW | +1 dé, ou effet fort (étourdir, téléporter) |

Les sorts à zone ou à effet sont moins chers en dégâts d'un cran.

---

## 9. Progression

- Les personnages évoluent du **niveau 1 au niveau 20** (un « palier » tous les 4 niveaux).
- L'expérience est gagnée par objectif accompli plutôt que par monstre tué ; le MJ annonce les montées de niveau.

| Niveau | Bonus de maîtrise | Gains |
|---|---|---|
| 1–4 | +2 | Sorts de départ de la classe |
| 5–8 | +3 | +1 PM au niveau 5 |
| 9–12 | +4 | +1 PA au niveau 10 |
| 13–16 | +5 | +1 PW max au niveau 15 |
| 17–20 | +6 | Sort ultime de classe au niveau 20 |

À **chaque niveau** : PV + (6 + Vitalité), puis un sort de voie ou un choix de progression (voir Les voies et Choix de progression ci-dessous).
Aux **niveaux 4, 8, 12, 16 et 20** : +1 dans une caractéristique (maximum +5).

### Montée en puissance des sorts

Aux **niveaux 5, 11 et 17**, tous les sorts qui lancent des dés de dégâts ou de soins gagnent **+1 dé du même type** (un sort à 1d8 passe à 2d8 au niveau 5, 3d8 au niveau 11, 4d8 au niveau 17). Les dés d'effets secondaires (dégâts aux ennemis adjacents, poisons) ne sont pas concernés, sauf mention contraire. Sans cette règle, les dégâts ne suivraient pas la croissance des PV.

### Paliers de sorts

Les sorts de classe sont rangés en **paliers** : palier I dès le niveau 1, II au niveau 5, III au niveau 9, IV au niveau 13, V au niveau 17, et le **sort ultime** au niveau 20.

### Les voies

Chaque classe propose **trois voies**, une par élément de la classe (la voie du Colosse du Iop pour la Terre, par exemple).

- **Niveau 3** : le personnage **choisit sa voie**. Ce choix est définitif. Il gagne la **capacité de voie** et le premier **sort de voie**.
- **Niveaux 3, 5, 9, 13 et 17** : il apprend automatiquement le **sort de voie** du palier correspondant (I, II, III, IV, V). Chaque voie compte exactement **5 sorts de voie**, un par palier.
- Ces niveaux-là, le sort de voie **remplace** le choix de progression (voir ci-dessous).
- Les sorts de départ et les sorts **hors voie** (utilitaires, souvent neutres) sont communs à toute la classe.

### Choix de progression

À chaque niveau à partir du 2, **sauf aux niveaux 3, 5, 9, 13 et 17** (sort de voie) et au niveau 20 (sort ultime), le personnage fait **un choix** :
- apprendre **un sort** d'un palier auquel il a accès : un sort hors voie, ou un sort d'une **autre voie** de sa classe (pour jouer deux éléments) ;
- prendre **une amélioration** d'un sort qu'il connaît (chaque sort liste ses améliorations) ;
- prendre une **option d'aventure** (ci-dessous).

Un personnage fait ainsi **13 choix** entre les niveaux 2 et 19.

[À TRANCHER : système des voies en prototype sur le Iop (document de classe v0.6). Les 11 autres classes suivent encore l'ancien système (un choix libre à chaque niveau) en attendant leur conversion.]

Les **options d'aventure** sont :
- une **nouvelle compétence** ;
- un **nouveau métier** ;
- une **Expertise** dans une compétence ou un métier qu'il maîtrise déjà : il ajoute **deux fois** son bonus de maîtrise aux tests de cette compétence (une Expertise par compétence).

### Aptitudes d'aventure

Chaque classe gagne aussi des **aptitudes d'aventure** aux **niveaux 1, 4, 7, 11, 15 et 19**. Ce sont des capacités **hors combat** liées à l'identité de la classe et de son Dieu : exploration, enquête, relations sociales, artisanat, voyage, survie. Elles s'ajoutent aux autres gains et ne coûtent aucun choix. Chaque document de classe les détaille, avec les **usages hors combat** de ses sorts.

### Les habitants du Monde des Douze

Les niveaux sont réservés aux **aventuriers**. La grande majorité des habitants (paysans, marchands, gardes, artisans) ne monte pas en niveau par l'aventure : ils progressent lentement et naturellement avec l'âge et l'expérience de leur métier.

Pour le MJ, un PNJ ordinaire se décrit simplement :
- **Enfant** : niveau 0, caractéristiques à 0, 10 PV.
- **Adulte** : niveau 1, 2 à 3 points de caractéristiques, 1 à 2 compétences liées à son métier.
- **Ancien ou vétéran** : niveau 2 à 4, une compétence de métier supplémentaire, un bonus de maîtrise de +2.
- Seuls les PNJ exceptionnels (maîtres de classe, champions, antagonistes) sont construits comme des personnages joueurs.

---

## 10. Exemple de tour de jeu

*Tristepin le Iop (Agilité +3, maîtrise +2, 6 PA, 3 PM) est au contact d'un Bouftou (Défense 11, Tacle 14, Esquive +2, résistance Air 1).*

1. Il veut contourner le Bouftou pour l'attaquer de dos. Test d'Esquive : 1d20 (11) + 3 (Agilité) + 2 (maîtrise) = 16 contre Tacle 14, réussi. Il dépense 2 PM pour se placer derrière.
2. Il lance *Épée Céleste* (3 PA). C'est un sort de zone : le Bouftou teste son Esquive contre 10 + 3 + 2 = 15 et obtient 7 + 2 = 9, raté.
3. Dégâts : 1d8 (5) + 3 (Agilité) + 4 (dos) − 1 (résistance) = **11 dégâts**.
4. Il relance *Épée Céleste* avec ses 3 derniers PA, puis choisit son orientation face au Bouftou pour ne pas lui présenter son dos.

---

## 11. Points ouverts à trancher

1. **Stasis** : à décider plus tard (règles de corruption et pouvoirs de la Stasis, pour une campagne avancée ou un antagoniste seulement).
2. **Techniques d'arme des Sans-classe** : à écrire avec le document d'équipement.
3. **Montures, familiers, Kamas et équipement** : documents séparés à venir.

### Décisions prises (v0.2)

- (v0.10) **Jeu tactique assumé** : le cœur du jeu est le combat tactique. Les options d'aventure restent en concurrence avec les sorts dans les choix de progression : c'est au joueur de choisir entre puissance en combat et richesse hors combat.
- (v0.10) **Voies** : choix de la voie au niveau 3 ; 5 sorts de voie appris automatiquement aux niveaux 3, 5, 9, 13 et 17 (un par palier), plus une capacité de voie ; les autres niveaux restent des choix libres (13 choix). Prototype sur le Iop.
- (v0.9) **Points de Destin = 1 + Chance, sans plafond** : c'est la particularité de la Chance ; les nombreuses relances à haut niveau sont voulues.
- (v0.9) **Initiative = 1d20 + Intelligence** (au lieu de l'Agilité), pour alléger l'Agilité et donner un rôle en combat à l'Intelligence.
- (v0.9) **La maîtrise s'ajoute à l'Esquive et au Tacle** : Esquive = 1d20 + Agilité + maîtrise, Tacle = 10 + Force + maîtrise. Sans cela, l'Esquive contre les sorts de zone devenait inutile à haut niveau.
- (v0.8) **6 compétences à la création** (2 de classe + 4 au choix) au lieu de 4 ; *Débrouillard* donne +2 compétences, un Sans-classe commence donc avec 8 compétences.
- (v0.7) **Compétences** : les 2 compétences de classe sont acquises d'office, plus 2 au choix ; la liste passe à 27 compétences (ajouts : Monte, Spectacle, Baragouin, Bricolage, Baratin, Chasse au trésor, Tripot, Ripaille, Roupillon, Almanax, Médecine). Pas d'historique à la création.
- Tours en **alternance par camp**.
- **Grille carrée**.
- Sorts de zone : **test d'Esquive** de chaque cible pour moitié des dégâts.
- **Pas de races** : la classe vient du Dieu d'un des parents.
- Les habitants ordinaires ne montent pas en niveau par l'aventure.
- (v0.3) La classe est **au choix du joueur**, les parents ne sont que du lore.
- (v0.6) Le jeu n'est pas axé que sur le combat : aptitudes d'aventure de classe aux niveaux 1, 4, 7, 11, 15, 19 ; options d'aventure (compétence, métier, Expertise) à la place d'un sort.
- (v0.5) Critique des sorts de zone : le lanceur lance 1d20, critique sur 20 naturel.
- (v0.4) Les sorts gagnent +1 dé aux niveaux 5, 11 et 17 ; les sorts sont rangés en paliers.
- (v0.3) Un Dieu peut **renier** un fidèle, qui devient **Sans-classe** ; ses enfants naissent Sans-classe ; l'allégeance se regagne par des épreuves au temple.
