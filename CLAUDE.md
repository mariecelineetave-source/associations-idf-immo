# associations.idf.immo — consignes pour les sessions automatisées

Site de **proposition de partenariat** de Marie-Céline Etave aux **associations
loi 1901 d'Île-de-France**.

Objectif unique : convaincre le bureau d'une association de signaler à ses
adhérents qu'elle a une conseillère immobilière partenaire, pour la **vente** et
la **recherche** de leur bien immobilier **personnel** (pas le patrimoine de
l'association).

## La proposition, en une ligne

| Ce qui se passe | Ce que reçoit l'association |
|---|---|
| Un adhérent confie un **mandat de vente**, et la vente est actée | **10 % des honoraires nets**, versés à la signature de l'acte authentique |
| Un adhérent confie un **mandat de recherche**, et l'acquisition aboutit | **10 % des honoraires nets**, versés à la signature de l'acte authentique |
| Un adhérent commande une **expertise en valeur vénale** | **10 % des honoraires nets** de la mission, versés après remise et règlement du rapport — **même sans vente** |

**Assiette confirmée par Marie-Céline (8 août 2026) : les honoraires NETS
hors taxes qu'elle perçoit réellement**, c'est-à-dire après déduction de la TVA
**et** de la quote-part revenant au réseau mandant (BSK). **Ce ne sont pas les
honoraires d'agence bruts facturés au client** — ne jamais réécrire le site en
ce sens, l'écart est d'environ un quart et il a déjà fallu corriger une première
version. La même règle vaut pour les trois volets ; ne jamais réduire le
dispositif à la seule transaction.

La convention de partenariat (document Word, hors dépôt) reprend cette assiette
à son article 5.2 : **le site et la convention doivent toujours dire la même
chose.** Toute évolution de l'un impose de vérifier l'autre.

Points non négociables du discours, à ne jamais contredire :

1. **L'adhérent ne paie aucun surcoût.** Le reversement est prélevé sur les
   honoraires de Marie-Céline, il ne s'y ajoute pas. Le taux du mandat n'est pas
   majoré parce que l'adhérent vient d'une association partenaire.
2. **L'association ne débourse rien** : ni droit d'entrée, ni cotisation, ni
   avance de trésorerie. Elle ne peut pas perdre d'argent dans l'opération.
3. **L'association n'est jamais intermédiaire.** Elle informe ses adhérents, et
   c'est tout : elle ne vend pas, ne négocie pas, ne conseille pas, ne perçoit
   rien de ses membres. Ne jamais écrire quoi que ce soit qui laisse penser
   qu'elle joue un rôle dans la transaction ou qu'elle est rémunérée pour un
   apport d'affaires.
4. **Aucun fichier d'adhérents n'est demandé ni transmis.** Ce sont les
   adhérents qui prennent contact d'eux-mêmes. C'est un argument central : ne
   jamais l'affaiblir.
5. **Le versement a lieu à la signature de l'acte authentique**, jamais au
   compromis ni à la signature du mandat. Si l'opération échoue, personne ne
   doit rien.
6. **Ni exclusivité, ni durée d'engagement, ni volume à atteindre.**

## Positionnement par rapport aux autres sites

Chaque site est autonome. **Ne jamais mélanger les contenus, et ne jamais
modifier un autre dépôt depuis celui-ci.**

- **antony.immo** — transaction locale à Antony (92), actu immo quotidienne,
  estimateur en ligne. Grand public. Bleu.
- **cse.idf.immo** — offre aux comités d'entreprise (CSE), Île-de-France. Bleu.
- **associations.idf.immo** — ce site : partenariat avec les associations loi
  1901, reversement de 10 %. Bleu.

**Palette : le bleu de la famille `.immo`**, aligné sur antony.immo à la demande
de Marie-Céline (11 août 2026) après un essai en prune et corail, jugé trop peu
classique. Valeurs : `--sable:#EBF2F9`, `--craie:#F7FAFD`, `--parterre:#DCE8F4`,
`--buis:#1C5A9E`, `--ombre:#0E2E52`, `--brique:#1668B5` (accent),
`--paille:#B7DCF8` (accent clair sur fonds sombres), `--or:#0C7350`.
Les accents `--brique` et `--or` sont **volontairement plus foncés** que ceux
d'antony.immo et de cse.idf.immo, pour tenir le seuil de contraste 4.5 : ne pas
les « réaligner » sur les autres sites sans revérifier les contrastes.

Les trois sites sont désormais bleus : c'est assumé, c'est une famille. Ce qui
doit rester distinct, c'est le **contenu**, jamais la couleur.

**Couleurs chaudes : usage strictement réservé.** Deux exceptions au bleu, toutes
deux voulues par Marie-Céline (11 août 2026) :

- `--fete-jaune`, `--fete-rouge`, `--fete-vert`, `--fete-orange` — **uniquement
  pour les fanions des trois guirlandes** (toits du héros, frise du bandeau,
  vignette « Amicales et comités des fêtes »). Une guirlande monochrome n'est pas
  une guirlande.
- `--dore:#F5B841` — **uniquement pour le sceau « 10 % »** du héros, dont c'est
  ce qui assure la visibilité (contraste 7,7 contre le ciel marine, contre 2,4
  quand le disque était bleu).

**Ne jamais employer ces teintes ailleurs** : titres, boutons, liens, encadrés,
fonds. Diluées dans la page, elles cessent d'être une touche de fête et abîment
le sérieux du bleu. Et ne pas les fusionner entre elles : le doré du sceau est
volontairement plus chaud que le jaune des fanions.

Ce qui appartient en propre à ce site : la skyline illustrée sous une guirlande
de fête, le sceau « 10 % », les six vignettes par famille d'associations et la
frise. Aucune image externe : tout est en SVG inline et reprend les variables de
couleur, donc **un changement de palette suffit à faire suivre les dessins**.

Pas d'actu immo ici, pas d'estimateur de prix au m², pas de contenu « comité
d'entreprise », pas de contenu « associations » sur les autres sites.

## Structure

- `index.html` — la proposition aux associations (page principale, CSS et JS
  inclus). Sections : héros, chiffres clés, pourquoi, le principe en 3 temps,
  simulateur + bloc « aucun surcoût », ce que reçoivent les adhérents (mandat de
  vente / mandat de recherche / expertise), rôle de l'association (fait / ne fait
  pas), le cadre pour le trésorier, pour quelles associations, bande
  « je viens vous en parler », mise en place en 4 étapes, l'interlocutrice, FAQ
  des bureaux, formulaire de demande.
- `mentions-legales.html` — mentions légales, RGPD, portée du partenariat et du
  simulateur.
- `marie-celine-etave.jpg` — portrait affiché section « Votre interlocutrice ».
  Seul fichier image du dépôt ; voir la règle 6 ci-dessous.
- `CNAME` — domaine personnalisé (`associations.idf.immo`), ne pas toucher.
- `sitemap.xml` / `robots.txt` — référencement. **Quand le contenu d'une page
  publiée change, mettre sa balise `<lastmod>` à la date du jour (AAAA-MM-JJ).**

## Règles de contenu

1. **Aucun chiffre ni référence juridique inventés.** Sans source vérifiée, on
   n'écrit rien. En particulier : **ne jamais affirmer un « taux moyen du
   marché »** d'honoraires d'agence. Le simulateur laisse le visiteur choisir le
   taux ; seul le 10 % de reversement est présenté comme un engagement ferme.
2. **Ne pas inventer le taux d'honoraires de Marie-Céline sur ce site.** Il n'y a
   volontairement aucun pourcentage d'honoraires annoncé ici (contrairement à
   cse.idf.immo, où le 3 % est un engagement validé). On écrit « les honoraires
   convenus au mandat ». Ne pas y toucher sans validation explicite.
3. **Ne jamais promettre un résultat** (« vente garantie », « valeur acceptée par
   le fisc »). On décrit la méthode et la portée, pas une garantie.
4. **Ne pas dissimuler le point fiscal.** La section « Le cadre » invite
   l'association à faire valider le traitement comptable et fiscal du
   reversement par son expert-comptable ou sa fédération. C'est volontaire :
   c'est ce qui rend la proposition crédible auprès d'un trésorier. **Ne pas
   supprimer ce paragraphe** pour rendre le discours plus vendeur.
5. **Règle de vocabulaire commune à la famille idf.immo** : ne pas écrire
   « minimum » ni « sans minimum » dans le texte visible. La promesse se formule
   en positif.
6. **Portrait de Marie-Céline.** Le fichier `marie-celine-etave.jpg`, à la
   racine, est le portrait affiché dans la section « Votre interlocutrice ».
   C'est une publication **volontaire** de Marie-Céline : ne pas le retirer au
   motif que le dépôt est public. S'il est absent, la page retombe
   automatiquement sur le monogramme « MCE » — c'est le comportement prévu, pas
   un bug.
7. **Aucune autre donnée personnelle dans le dépôt** (le dépôt est public). Les
   formulaires restent en `mailto:` ; rien n'est stocké côté site. Ne jamais
   ajouter de nom d'association, d'adhérent ou de coordonnée dans le dépôt.
8. **Ne jamais contacter qui que ce soit.**
9. Avant tout commit : vérifier l'équilibre des balises HTML des pages modifiées
   (python `html.parser`).

## Contact — règle stricte

- **Adresse e-mail : `contact@idf.immo` uniquement.** Une seule boîte à la racine
  du domaine, valable pour ce site comme pour les autres sous-domaines de
  `idf.immo`. Ne jamais mettre `contact@antony.immo`, `contact@cse.idf.immo` ni
  `contact@associations.idf.immo` : ces adresses appartiennent à d'autres sites
  ou n'existent pas.
- **Téléphone : 06 60 98 92 92.**

## Publication

- Toute modification attend la validation explicite de Marie-Céline (« publie »).
- Aucune rubrique de ce site n'est en publication automatique.

## Divers

- Tout en français. Commits clairs en français.
- Le proxy réseau bloque le fetch HTTP direct (curl/WebFetch) : utiliser
  WebSearch uniquement ; un échec curl ne signifie PAS que le site est en panne.
- Push : `git push -u origin <branche>` ; en cas d'erreur réseau, retenter
  jusqu'à 4 fois (2, 4, 8, 16 s).

## Points à confirmer avec Marie-Céline

Ces points sont **volontairement absents du site** tant qu'ils ne sont pas
tranchés — ne rien y écrire d'inventé en attendant.

- **Tarif de l'expertise pour les adhérents.** Aucun prix n'est affiché ici (le
  site dit « tarif communiqué sur demande »). À fixer si un tarif dédié aux
  adhérents d'associations partenaires est souhaité — pour mémoire, l'expertise
  est à 1 190 € sur antony.immo et à 990 € pour les salariés d'un CSE partenaire
  sur cse.idf.immo. Ne rien afficher ici tant que ce n'est pas tranché.
- **Modèle de convention de partenariat.** Le site l'annonce (« une page »). Il
  reste à rédiger et n'est pas dans ce dépôt.
- **Cadre juridique de la rémunération d'un apporteur.** Le site est rédigé pour
  que l'association ne soit jamais présentée comme un intermédiaire rémunéré,
  mais comme bénéficiaire d'un reversement volontaire prélevé sur les honoraires.
  À faire valider par un professionnel du droit avant diffusion large.
