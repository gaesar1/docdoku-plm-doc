

* This will become a table of contents (this text will be scraped).
{:toc}

# Présentation

Le PLM (Product Lifecycle Management, littéralement gestion du cycle de vie du produit) est un
domaine d'activité dont le but est de créer et maintenir des produits tout au long de leur cycle de
vie, depuis l'établissement du cahier des charges du produit et des services associés jusqu'à la
fin de vie. (source: Wikipedia)

Il s’agit d’une stratégie permettant aux entreprises de partager leurs données produit autorisant
l’ensemble des parties prenantes (collaborateurs, fournisseurs, clients, etc.) à intervenir de
façon collaborative sur le développement des produits.

Au-delà des fonctionnalités traditionnelles d’un PLM, DocDokuPLM permet de visualiser et
collaborer sur une maquette numérique et/ou tous types de modèles 3D (Catia, Inventor,
AutoCAD, STEP, IFC, COLLADA, OBJ, etc.) sur tous types de terminaux (PC, Mac, Tablettes,
Smartphones) directement dans le navigateur internet sans aucune installation ou plugin.

De plus, DocDokuPLM offre des fonctions avancées telles que la gestion des droits d’accès, les
modèles de document ou encore le BPM (Business Process Management) au travers d’un
éditeur graphique de processus.

DocDokuPLM est un outil simple, à l’ergonomie soignée dont la prise en main est très rapide.
L’objectif de ce document est de présenter en détail l’ensemble des possibilités offertes par
cette solution pour une utilisation optimale.

# Gestion des utilisateurs

Dans DocDokuPLM, la notion d'utilisateur ne se restreint pas à un simple accès à l'application.
C'est par exemple à partir de ce même utilisateur que vous pourrez spécifier des droits sur un
document ou encore lui attribuer un rôle dans un processus.

Vous découvrez DocDokuPLM ? Les chapitres suivants devraient retenir toute votre attention...

## Création d'un utilisateur

Pour créer un compte, cliquez sur le lien inscrivez-vous depuis la page d'accueil.

{% image /assets/images/documentation/fr/image32.png "Lien d’inscription"%}

Chaque nouvel utilisateur doit effectuer cette action.

La toute première étape consiste ainsi à s'enregistrer. Ici, tous les champs sont obligatoires.

{% image /assets/images/documentation/2.0/fr/image17.png "Création d'un utilisateur"%}

## Modification de l’utilisateur

{% image /assets/images/documentation/2.0/fr/image04.png "Gestion du compte"%}

Dans le sous-menu “Mon compte” vous pouvez modifier toutes vos caractéristiques à l'exception de votre identifiant utilisateur.

Cette page vous permet également de modifier votre mot de passe. Le fuseau horaire permet d'afficher les heures selon vos préférences.

{% image /assets/images/documentation/2.0/fr/image10.png "Édition du compte"%}

# Gestion des espaces de travail

## Création d'un espace de travail

Votre compte désormais créé, vous avez la possibilité de créer un espace de travail.

{% image /assets/images/documentation/fr/image37.png "Création d’un espace de travail"%}

Une fois cette opération effectuée, vous en serez l’administrateur. Celui-ci regroupera l’ensemble des documents, articles, processus métier et produits.

L’option “geler la structure des répertoires sauf pour le gestionnaire de l’espace de travail” doit être cochée si vous ne souhaitez pas que les autres utilisateurs puissent modifier la structure des répertoires.

## Modification d'un espace de travail

Pour accéder aux options d’un espace de travail, cliquez sur le lien “Administration des espaces de travail”.

{% image /assets/images/documentation/2.0/fr/image04.png "Gestion du compte"%}

Plusieurs actions sont ici possibles :

L'édition de l'espace de travail permettra tout d'abord d’en modifier l'administrateur ainsi que sa description.

{% image /assets/images/documentation/fr/image27.png "Modification de l'espace de travail"%}

Vous pouvez également gérer les accès sur l'espace de travail, soit au niveau utilisateur, soit en créant des groupes de travail.

Cette gestion des droits est abordée dans le chapitre suivant.

### Tableau de bord

Le tableau de bord donne accès à des statistiques sur votre espace de travail (espace disque, nombre de documents et d'articles, taux de réservation par utilisateur, etc.).

{% image /assets/images/documentation/fr/image39.png "Tableau de bord de l’espace de travail Airplane-T01"%}

## Messagerie collaborative

L’ensemble des utilisateurs d’un même espace de travail peuvent échanger en temps réel grâce aux modules de communication intégrés dans DocDokuPLM.

Ces modules offrent la possibilité d’avoir des conversations de type messagerie instantanée et visioconférence. Il est par ailleurs possible de partager les visualisations d’articles entre collaborateurs dans l’objectif de faciliter l’échange d’informations et d’accélérer le processus de développement de produits.

Depuis le menu Collaborateurs, vous visualisez en temps réel les utilisateurs connectés (en vert). En cliquant sur l’icône de la caméra, vous lancez une conversation vidéo.

{% image /assets/images/documentation/fr/image07.png "Menu collaborateurs"%}

{% image /assets/images/documentation/fr/image16.png "Invitation session vidéo"%}

En complément du menu Collaborateurs, chaque fois qu’un nom d’utilisateur apparaît en bleu dans l’application, cliquez dessus et un menu de conversation contextualisé avec le nom de l’espace de travail et le nom de l’élément concerné apparaît. Ce contexte est indiqué dans le titre de chaque fenêtre de conversation.

{% image /assets/images/documentation/2.0/fr/image29.png "Menu collaboratif contextuel"%}

# Gestion des contrôles d’accès

## Droits appliqués au niveau de l’espace de travail

### Gestion des accès utilisateurs

L’administrateur de l’espace de travail peut définir des droits par défaut aux utilisateurs. Un utilisateur peut avoir un accès complet en lecture/écriture, un accès en lecture seule, ou bien n’avoir aucun droit.

Il est également possible de désactiver un utilisateur, il ne pourra alors plus se connecter.

{% image /assets/images/documentation/fr/image44.png "Gestion des utilisateurs et des groupes "%}

Par ailleurs, les utilisateurs peuvent être répartis au sein de groupes qui porteront les droits.

Un utilisateur en accès complet peut :

* créer, modifier ou supprimer des documents et des articles,
* modifier la structure des dossiers dans la gestion des documents,
* déplacer des documents dans les dossiers,
* réserver des documents et articles.

Un utilisateur en lecture seule peut :

* accéder aux documents et articles en lecture,
* visualiser la structure des produits.

Un utilisateur désactivé ne peut accéder ni aux documents ni aux articles.

Pour changer les droits d’un utilisateur ou d’un groupe, il faut cliquer sur la case à cocher correspondante, puis cliquer sur un bouton d’action (supprimer, désactiver, activer, ...) en bas de la liste.

### Gestion des groupes

Pour gérer les utilisateurs d’un groupe, vous devez cliquer sur son nom. Vous pouvez alors ajouter ou enlever des utilisateurs au groupe sélectionné.

{% image /assets/images/documentation/fr/image33.png "Gestion des utilisateurs d’un groupe"%}

## Droits appliqués

### Au niveau des documents et des articles

A la création d’un document ou d’un article, les droits appliqués à ceux-ci sont par défaut ceux définis sur l’espace de travail. Pour redéfinir les droits de l’entité à créer, vous devez utiliser l’onglet “Droits”. Vous pouvez alors modifier les droits spécifiquement pour cette entité.

Vous pouvez ainsi donner des droits supplémentaires sur des entités ciblées aux utilisateurs en lecture seule au niveau de l’espace de travail, ou au contraire restreindre l’accès à des données à des utilisateurs en accès complet.

En choisissant “Interdit” pour un utilisateur sur une entité, celle-ci ne sera pas visible dans la liste qui lui est servie.

{% image /assets/images/documentation/2.0/fr/image01.png "Formulaire de création de document, onglet de gestion de droits d'accès "%}

Ces droits sont modifiables une fois le document créé, seuls l’administrateur de l’espace de travail et l’auteur du document ou de l’article peuvent le faire.

Une fois l’entité sélectionnée, l’icône suivante apparaît dans le bandeau du haut.

{% image /assets/images/documentation/fr/image13.png%}

Vous pouvez alors modifier les droits associés au document ou à l’article, ou bien choisir de les désactiver.

Quand des droits sont appliqués sur un élément, un cadenas est visible en fin de ligne. La couleur verte signifie que vous avez un accès complet sur l’entité, la couleur jaune signifie un accès en lecture seule.

{% image /assets/images/documentation/2.0/full_access.png "Accès complet"%}
{% image /assets/images/documentation/2.0/read_only.png "Lecture seule "%}

### Au niveau des modèles, des processus, des configurations et des exemplaires

Si vous êtes en accès complet sur un modèle (par exemple), vous pouvez modifier ses droits associés pour un utilisateur ou un groupe. Un utilisateur ou un groupe qui sera en lecture seule pourra uniquement utiliser ce modèle. En interdisant l'accès, l'utilisateur ou le groupe ne le verra jamais.

## Combinaison et priorité des droits

Notions importantes :

* Ordre de priorité des droits :
1. Droits utilisateur sur un document / article
2. Droits de groupe sur un document / article
3. Droits utilisateur sur l'espace de travail
4. Droits de groupe sur l'espace de travail
5. Droits du groupe le plus permissif
* Les droits ne s'appliquent pas aux utilisateurs désactivés dans un espace de travail.
* L’administrateur de l’espace de travail outrepasse ces droits.

Ci-après les tableaux récapitulatifs des combinaisons possibles.

### Utilisateur présent directement dans l’espace de travail ET dans un groupe

| Groupe        | Utilisateur       | Droits effectifs |
| ------------- | ----------------- | ---------------- |
| accès complet | lecture seule     | lecture seule    |
| accès complet | accès complet     | accès complet    |
| lecture seule | lecture seule     | lecture seule    |
| lecture seule | accès complet     | accès complet


### Utilisateur présent dans plusieurs groupes

| Groupe I       | Groupe II       | Droits effectifs |
| -------------- | --------------- | ---------------- |
| accès complet  | accès complet   | accès complet    |
| accès complet  | lecture seule   | accès complet    |
| accès complet  | désactivé       | accès complet    |
| lecture seule  | désactivé       | lecture seule    |
| lecture seule  | lecture seule   | lecture seule

### Droits définis au niveau entité (document/article) pour un utilisateur (présent directement dans l’espace de travail)

| Utilisateur    | Droit d’accès entité | Droits effectifs |
| -------------- | -------------------- | ---------------- |
| accès complet  | accès complet        | accès complet    |
| accès complet  | lecture seule        | lecture seule    |
| accès complet  | interdit             | interdit         |
| lecture seule  | accès complet        | accès complet    |
| lecture seule  | lecture seule        | lecture seule    |
| lecture seule  | interdit             | interdit

### Droits définis au niveau entité pour un groupe

| Groupe          | Droit d’accès entité  | Droits effectifs |
| --------------- | --------------------- | ---------------- |
| accès complet   | accès complet         | accès complet    |
| accès complet   | lecture seule         | lecture seule    |
| accès complet   | interdit              | interdit         |
| lecture seule   | accès complet         | accès complet    |
| lecture seule   | lecture seule         | lecture seule    |
| lecture seule   | interdit              | interdit

# Gestion des documents

DocDokuPLM offre une gestion complète de documents avec prise en compte des versions (révision, itération), partage et publication de documents, organisation arborescente et par libellés, configuration fine des droits d’accès.

Dans ce qui suit nous détaillons l’ensemble de ces fonctions.

{% image /assets/images/documentation/2.0/fr/image09.png "Menu de gestion de documents"%}

## Modèles de document

### Création d’un modèle de document

Vous pouvez créer des modèles de documents qui serviront à la création des documents. Au moment de la création d’un modèle, vous pouvez choisir de gérer la nomenclature des documents en déterminant un masque de saisie. Les caractères disponibles sont les suivants :

* alphanumériques,
* '#' pour tout chiffre valide,
* '*' pour n'importe quel caractère.

Cocher la génération de l’identifiant entraînera la création automatique d’identifiants pour les documents qui utiliseront ce modèle. Si votre masque contient des chiffres, ils seront automatiquement incrémentés pour chaque nouveau document créé.

{% image /assets/images/documentation/2.0/fr/image31.png "Formulaire de création d'un modèle de document"%}

### Ajout de processus

Un processus peut être associé au modèle depuis l'onglet Processus. Lors de la création d'un document avec ce modèle, le processus associé sera automatiquement présélectionné.

### Ajout de fichiers et d’attributs

Vous pouvez définir des types d’attributs au modèle et lui associer des fichiers. Tous les documents qui seront créés avec ce modèle auront :

* ses attributs - il faudra alors renseigner leur valeur,
* ses fichiers - qui pourront bien sûr évoluer, le fichier positionné au niveau du modèle n’étant qu’un squelette.

{% image /assets/images/documentation/2.0/fr/image41.png "Rattachement de fichiers au modèle"%}

## Création de document

Tout document doit appartenir à un dossier. Afin de créer un document dans un répertoire spécifique, il faut se placer dessus en cliquant sur son nom dans le menu de gauche.

{% image /assets/images/documentation/2.0/fr/image35.png "Formulaire de création d'un document"%}

Vous pouvez ajouter des attributs, spécifier un processus et définir des droits d’accès dès la création du document. Le chargement des fichiers et l’édition des liens vers d’autres documents ne pourra se faire qu’une fois le document créé.

Une fois créé, vous pourrez effectuer les actions suivantes :

* réservation / Annulation de la réservation / Libération,
* suppression,
* abonnement aux changements d’état du document. Dans ce cas l’utilisateur reçoit un mail à chaque fois qu’une modification est apportée sur le document par d'autres utilisateurs,
* abonnement aux changements d’itération du document. L’utilisateur reçoit également un mail de notification  en cas de nouvelle itération sur le document,
* ajout de libellés - par exemple classer un document comme important,
* gestion de ses droits d’accès,
* création d’une nouvelle version,
* publication du document en mode public ou privé.

## Déplacement d'un document

Vous pouvez déplacer un document vers un dossier grace à l'icône ci-dessous. Pour ce faire, il suffit de glisser-déposer le document depuis l'icône vers le dossier voulu.

{% image /assets/images/documentation/2.0/document_move.png "Bouton de déplacement"%}

## Modification d’un document

Pour modifier un document, il vous faut d'abord le réserver. Vous pouvez accéder à la fenêtre de modification en cliquant sur le titre d’un document de la liste.

Les flèches situées en bas à gauche servent à visualiser les différents changements apportés lors des itérations précédentes.

Pour accéder au dossier qui contient le document, cliquez sur le lien à droite de “Dossier”.

{% image /assets/images/documentation/2.0/fr/image28.png "Fenêtre d’informations relatives à un document"%}

### Onglet Fichiers

Cet onglet permet d'associer des fichiers au document.

{% image /assets/images/documentation/2.0/fr/image52.png "Vue Fichiers"%}

DocDokuPLM génère une version pdf des fichiers rattachés à un document. La majorité des formats utilisés avec les logiciels de traitement de texte est prise en charge.

Une fois généré, le pdf peut être visionné depuis le lien permanent. Une page de garde a été ajoutée contenant les informations suivantes :

{% image /assets/images/documentation/2.0/fr/image61.png "Page de garde auto-générée"%}

Voici la liste complète des formats supportés : odt, ods, odp, odg, odc, odf, odb, odi, odm, doc, docx, ppt, pps, txt, csv, xls, pdf, html, htm, xml, rtf, msg.

### Onglet Cas d'emploi

Cette vue liste tous les articles et documents qui utilisent le document en tant que lien.

{% image /assets/images/documentation/2.0/fr/image68.png "Vue Cas d'emploi"%}

## Liens Réservés et Tâches

Afin d’assurer un accès rapide aux documents qui concernent un utilisateur donné, vous trouverez deux liens dans le menu de gauche :

* réservés : ce lien affichera l’ensemble des documents réservés par l’utilisateur,
* tâches : ce lien sert à visualiser les différents documents sur lesquels l’utilisateur est directement impliqué via un processus.

# Gestion des produits

DocDokuPLM est donc un système de gestion collaborative de produits dont le but est d’aider les membres d’une même organisation à gérer et partager l'ensemble des actions et des itérations apportées à un produit tout au long de son cycle.

Vous retrouvez, entre autres, les fonctionnalités suivantes :

* gestion des versions successives d'un même produit (notion de ligne de base) permettant la prise en compte des demandes de modifications ou d’évolutions,
* recherche d'un produit,
* visualisation 3D d’un produit,
* partage de documents liés à des produits.

La création d’articles et de produits est expliquée dans le paragraphe qui suit.

## Article

Les composants d'un produit sont appelés articles, ou assemblages s'ils sont eux-mêmes composés d'articles. DocDokuPLM permet de créer des articles à partir de rien ou bien à partir de modèles existants.

### Création de modèle d’article

DocdokuPLM offre la possibilité de créer des modèles types d’article et de leur associer un processus, des attributs, des fichiers et un masque de saisie permettant de faciliter la gestion de nomenclature des articles qui auront ce modèle.
Cette opération permet par la suite de créer des articles reposant sur ces modèles.

### Création d’article

Lors de la création d’un article, vous pouvez donc renseigner un modèle d’article. L’article ainsi créé aura les mêmes propriétés que celles du modèle (processus, attributs, fichier CAO).

Vous pouvez tout aussi bien lui associer de façon individuelle :

* un processus, afin de gérer le cycle de vie de l’article et régir l'accès à cet article pour les autres collaborateurs de l’espace de travail,
* des attributs.

{% image /assets/images/documentation/2.0/fr/image05.png "Création d'un article"%}

L’article créé sera rajouté à la liste des articles déjà présents.

{% image /assets/images/documentation/2.0/fr/image19.png "Liste des articles"%}

En cliquant sur le numéro d’un article, une fenêtre affichera ses détails. Vous pouvez en modifier les éléments suivants : les attributs, le fichier CAO ou encore les liens vers des documents.

En sélectionnant un article, vous pouvez lui appliquer un ensemble d’actions à savoir :

* réservation / annulation de la réservation / libération,
* suppression,
* ajout de libellés - par exemple classer des articles comme importants,
* gestion de ses droits d’accès,
* création d'une nouvelle version,
* finalisation,
* statut obsolète pour figer un article en itération (l'article doit être finalisé).

{% image /assets/images/documentation/2.0/obsolete_icon.png "Icône obsolète"%}

### Fichiers

Cet onglet permet de joindre des fichiers et d'associer un fichier CAO à l'article. Si vous choisissez un fichier CAO alors qu'il y en a déjà un, ce dernier sera automatiquement remplacé.

{% image /assets/images/documentation/2.0/fr/image51.png "Vue Fichiers"%}

DocDokuPLM doit convertir les fichiers CAO au format obj pour permettre la visualisation 3D. Cette conversion se fait automatiquement à la suite de l'ajout d'un fichier CAO. Si elle échoue, vous pouvez la relancer manuellement en cliquant sur "Ré-essayer".

Voici la liste complète des formats supportés : dxf, obj, off, ply, stl, 3ds, wrl.

L'ajout de textures est également possible en ajoutant les fichiers correspondants au format jpg ou png. Les textures seront appliquées dans la vue 3D.

### Assemblage d’articles

Lors de la modification d’un article, vous pouvez définir son assemblage. Un assemblage est composé d'autres articles (sous-article).

{% image /assets/images/documentation/2.0/fr/image24.png "Assemblage d'articles"%}

Un sous-article peut être facultatif et avoir des variantes. Pour ajouter des variantes à un article, sélectionnez sa vue. De nouvelles actions apparaissent : créer un nouvel article comme variante ou ajouter un article existant.

{% image /assets/images/documentation/2.0/fr/image59.png "Ajouter une variante"%}

Une fois ajouté, la variante apparaît dans la vue du sous-article, tel que montré ci-dessous.

{% image /assets/images/documentation/2.0/fr/image60.png "Variante ajoutée"%}

### Notifications

Parfois un changement sur un sous-article peut impacter l'article parent. L'onglet Notifications affiche le journal des modifications des sous-composants pour vous aider à régler les impacts potentiels.

{% image /assets/images/documentation/2.0/fr/image66.png "Vue Notifications"%}

Un clic sur cette icône ouvre directement la fenêtre de détails d'un article à l'onglet Notifications.

{% image /assets/images/documentation/2.0/notifications_icon.png "Accès rapide aux Notifications"%}

Pour passer les notifications de modifications en mode résolu, il vous suffit de cliquer sur le lien "Marquer comme vérifié".

{% image /assets/images/documentation/2.0/fr/image67.png "Notification vérifiée"%}

Note : le seul moyen de vider la liste des notifications est de créer une nouvelle itération de l'article parent.

### Cas d'emploi

Cette vue liste :

* les assemblages qui utilisent l'article en tant que sous-composant (composant ou variante),
* les produits et exemplaires qui utilisent l'article en tant que sous-composant (tête, noeud ou feuille).

{% image /assets/images/documentation/2.0/fr/image69.png "Vue Cas d'emploi"%}

### Construire une requête

Pour choisir vous-même ce que vous voulez afficher dans la liste des articles, il vous faut construire une requête. Pour ce faire, cliquez sur le bouton suivant :

{% image /assets/images/documentation/2.0/query_builder.png "Bouton d'accès"%}

La vue qui s'affiche alors vous permet de :

* filtrer la liste d'articles par produit et / ou exemplaire,
* sélectionner les champs que vous voulez afficher (par exemple numéro d'article, nom, attributs...). * inclure ou exclure des articles avec des conditions
* ordonner et grouper les articles dans la liste de résultats.

{% image /assets/images/documentation/2.0/fr/image80.png "Construction d'un requête"%}

Si vous enregistrez la requête et que vous la sélectionnez, vous pourrez exporter les résultats dans un fichier Excel. Cette fonctionnalité peut s'avérer très utile pour obtenir la nomenclature d'un produit.

#### Filtres

Il y a deux sortes de filtres :

* filtres sur les articles,
* filtres sur les données d'exemplaires.

Les filtres sur les articles permettent d'ajouter des critères de recherche sur les champs liés aux révisions/itérations d'articles :

* numéro d'article,
* nom d'article,
* auteur,
* attributs d'itération,
* ainsi que d'autres critères liés aux articles.

Les filtres sur les données d'exemplaires apparaissent seulement quand un exemplaire est ajouté dans la zone "champs".

Ces derniers permettent de réduire la liste obtenue dans un contexte d'exemplaire produit selon les attributs des données d'exemplaire. Ils se comportent comme un second filtre à la suite du filtre des articles (condition "ET").

Note : ces filtres n'apparaissent que si des données d'exemplaires avec attributs existent.

Vous êtes autorisé à n'utiliser aucun filtre (renvoie toutes les données), ou bien seulement un des deux.

#### Opérateurs

Il y a différents opérateurs disponibles selon le type d'attribut que vous voulez utiliser en tant que filtre.

##### Attributs de type texte

Les attributs de type texte ont pour opérateurs :

* égal / non égal,
* contient / ne contient pas,
* commence par/ ne commence pas par,
* finit par / ne finit pas par.

##### Attributs de type nombre

Les attributs de type nombre ont pour opérateurs :

* égal / non égal,
* inférieur / inférieur ou égal,
* supérieur / supérieur ou égal,
* entre.

##### Attributs de type date

Les attributs de type date ont pour opérateurs :

* égal / non égal,
* inférieur / inférieur ou égal,
* supérieur / supérieur ou égal,
* entre.

##### Attributs de type texte long

Les attributs de type texte long ont pour opérateurs :

* égal / non égal,
* contient / ne contient pas,
* commence par/ ne commence pas par,
* finit par / ne finit pas par.

##### Attributs de type booléen

Les attributs de type booléen ont pour opérateurs :

* égal / non égal.

##### Attributs de type numéro d'article

Les attributs de type numéro d'article ont pour opérateurs :

* égal / non égal,
* contient / ne contient pas,
* commence par/ ne commence pas par,
* finit par / ne finit pas par.

##### Attributs de type liste de valeurs

Les attributs de type liste de valeurs ont pour opérateurs :

* égal / non égal.

##### Attributs de type URL

Les attributs de type URL ont pour opérateurs :

* égal / non égal,
* contient / ne contient pas,
* commence par/ ne commence pas par,
* finit par / ne finit pas par.

#### Utilisation avancée

Il est possible de combiner des critères, et d'ajouter des sous-règles pouvant elles-même être combinées.

Il n'y a pas de limite sur le nombre de combinaisons.

Pour chaque groupe de règle, il y a deux boutons disponibles

{% image /assets/images/documentation/2.5/fr/qb-buttons.png "Boutons d'ajout de règles "%}

Pour ajouter une règle dans un groupe de règles, cliquez sur le premier des deux boutons. Pour ajouter un groupe de règles dans un autre groupe de règles, cliquez sur le deuxième des deux boutons.

{% image /assets/images/documentation/2.5/fr/complex-query.png "Exemple de règles composées "%}

#### Sauvegarde et export

##### Sauvegarde de requêtes

Vous pouvez enregistrer la vue courante dans l'espace de travail en cliquant sur le bouton "Enregistrer". La requête ne sera pas sauvegardée si elle n'est pas valide. Une fois sauvegardée elle apparaitra aussi pour les autres utilisateurs de l'espace de travail.

Ces requêtes sauvegardées apparaissent dans un sélecteur en haut du constructeur de requêtes. Une fois sélectionnée, les champs sont mis à jour dans la vue courante.

Ces requêtes sauvegardées peuvent être effacées en cliquant sur le bouton "Supprimer de la liste des requêtes".

##### Export

Il est possible d'exporter soit la vue courante, soit une requête sauvegardée.

Pour exporter la vue courante, cliquez sur le bouton "Export Excel" qui se trouve au bas de la vue.

Pour exporter une requête sauvegardée, choisissez la requête depuis le menu déroulant, puis cliquez sur le bouton "Export Excel" se trouvant juste à coté du sélecteur.

Une fois un des deux boutons cliqué, un fichier Excel contenant les résultats de la requête est automatiquement téléchargé.

### Liens rapides

Vous trouverez un accès rapide à vos articles réservés dans le menu de gauche.

{% image /assets/images/documentation/2.0/fr/image50.png "Section des liens"%}

## Produit

###Création de produit

Au moment de la création d’un produit, l’identifiant du produit ainsi que le numéro de l’article sont obligatoires, la description est par contre optionnelle.

Le numéro d’article est l’élément de tête de votre produit. Celui-ci peut être un simple article ou un assemblage d’articles.

{% image /assets/images/documentation/2.0/fr/image12.png "Formulaire de création de produit"%}

Le produit créé sera rajouté à la liste des produits. En sélectionnant un produit dans la liste, les actions possibles sont sa suppression et la création d’une ligne de base.

### Configuration

Une configuration est une liste de choix d'assemblage pour un produit donné. En effet, on peut vouloir :

* choisir entre un article ou une de ses variantes,
* ne rien choisir, si un article est facultatif.

{% image /assets/images/documentation/2.0/fr/image64.png "Création d'une configuration"%}

Deux types de configuration sont proposés :

* derniers libérés, pour inclure les dernières itérations libérées de chaque article impliqué,
* derniers finalisés, pour inclure automatiquement les dernières versions finalisées de chaque article impliqué.

{% image /assets/images/documentation/2.0/fr/image65.png "Exemple de choix : Aucun"%}

### Ligne de base

La création d’une ligne de base (ou baseline) permet d’enregistrer à un instant donné une version du produit et donc de gérer différentes versions d’un même produit.

{% image /assets/images/documentation/2.0/fr/image02.png "Création d’une baseline"%}

Si le type de configuration choisi est "Derniers finalisés" et que des articles existent en plusieurs versions, alors l'onglet Versions permet de sélectionner une version plus ancienne.

{% image /assets/images/documentation/2.0/baseline_versions.png "Choix de version"%}

De plus, l'onglet Configuration permet de choisir une configuration spécifique ce qui préremplira pour vous tous les choix de configuration. Bien sûr, vous pourrez re-modifier ces choix depuis l'onglet Choix.

{% image /assets/images/documentation/2.0/fr/image58.png "Choix de configuration"%}

### Fonction utilisateur

Parfois, il peut être utile de lancer des calculs sur tous les articles d'un même produit ou d'une même ligne de base, pur déterminer par exemple son prix total. Cette fonctionnalité est disponible en cliquant sur ce bouton :

{% image /assets/images/documentation/2.0/user_function_button.png "Bouton Fonction utilisateur"%}

Le calcul peut être une somme ou une moyenne. Vous choisissez l'attribut à utiliser dans le calcul (ci-dessous le poids). Si l'attribut n'est pas défini pour un article, cet article est ignoré.

{% image /assets/images/documentation/2.0/fr/image78.png "Vue Fonction utilisateur"%}

### Exemplaire

Un exemplaire est une instance de produit basée sur une ligne de base et identifiée par un numéro de série.

Vous pouvez ajouter des attributs et définir des droits d’accès dès la création. Par contre le chargement des fichiers et l’édition des liens vers d’autres documents ne pourra se faire qu’une fois l'exemplaire créé.

{% image /assets/images/documentation/2.0/fr/image62.png "Création d'un exemplaire"%}

Pour conserver différentes versions d'un même exemplaire, vous devez créer des nouvelles itérations en cliquant sur le bouton "Rebaser". Ce bouton vous permet également de changer de ligne de base.

{% image /assets/images/documentation/2.0/fr/image63.png "Rebaser un exemplaire"%}

### Exporter les fichiers dans un zip

Pour partagaer des fichiers avec des personnes n'utilisant pas DocDokuPLM ou simplement pour conserver une copie sur votre disque, vous trouverez une fonctionnalité très utile sur chaque item d'une liste de produits / lignes de base / exemplaires.

{% image /assets/images/documentation/2.0/fr/image79.png "Exporter les fichiers"%}

Vous pouvez choisir :

* d'exporter uniquement les fichiers CAO,
* d'exporter uniquement les fichiers des documents liés,
* d'exporter tous les fichiers attachés aux articles et aux documents liés.

Si vous exportez les fichiers d'un produit, vous obtiendrez les fichiers joints à la dernière itération de chaque article et de chaque document. Sinon, vous obtiendrez les fichiers joints  the files attached to the baselined iterations.

## Explorateur de la structure d'un produit

Cliquez sur l'icône ci-dessous pour faire apparaître la structure d'un produit, d'une ligne de base ou d'un exemplaire.

{% image /assets/images/documentation/2.0/product_structure.png "Icône de structure produit"%}

La structure produit vous permet de voir l'organisation des composants d'un produit en arborescence et de localiser un article donné.

{% image /assets/images/documentation/2.0/tree_structure.png "Structure produit"%}

Chaque noeud représente un assemblage d'articles, il suffit de l'étendre pour voir de quels articles il est composé. Un clic sur l'article affiche ses sous-articles sous forme de liste et un clic sur l'icône à droite de l'article affiche ses propriétés.

Actions disponibles sur l'arborescence :

{% image /assets/images/documentation/2.0/refresh_tree.png "Rafraîchir l'arbre"%}
{% image /assets/images/documentation/2.0/toggle_comments.png "Afficher/masquer les commentaires"%}

Informations disponibles sur un article :

{% image /assets/images/documentation/2.0/optional.png "Est falcutatif"%}
{% image /assets/images/documentation/2.0/has_substitutes.png "Possède des variantes"%}
{% image /assets/images/documentation/2.0/is_substitute.png "Est une variante"%}

### Configuration du parcours de l'arborescence

Vous pouvez choisir comment explorer l'arborescence avec le menu en haut à gauche. Il existe 3 modes de parcours :

* "Dernières versions", pour afficher la structure du produit. Dans ce cas, le sous-menu vous permet de choisir entre différents statuts d'article (travail en cours, derniers libérés, derniers finalisés).

{% image /assets/images/documentation/2.0/fr/image70.png "Exemple avec le mode produit"%}

* "Baseline", pour afficher la structure d'une ligne de base. Dans ce cas, le sous-menu vous permet de choisir une baseline du produit.

{% image /assets/images/documentation/2.0/tree_conf_baseline.png "Exemple avec le mode baseline"%}

* "Numéro de série", pour afficher la structure d'un exemplaire. Dans ce cas, le sous-menu vous permet de choisir un exemplaire associé au produit.

{% image /assets/images/documentation/2.0/fr/image71.png "Exemple avec le mode exemplaire"%}

### Données de l'exemplaire

Vous pourriez avoir besoin d'associer des données spécifiques à un article d'un exemplaire (comme par exemple un numéro de série). Cette fonctionnalité est disponible et accessible depuis le mode exemplaire. Pour afficher les données d'un article dans un exemplaire, cliquez sur la checkbox de l'article concerné dans l'arborescence puis sur le bouton suivant :

{% image /assets/images/documentation/2.0/fr/image72.png "Bouton des données de l'exemplaire"%}

{% image /assets/images/documentation/2.0/fr/image73.png "Création de données d'exemplaire - Onglet Attributs"%}

Lors de l'édition de ces données, vous pouvez gérer des attributs, des fichiers et des liens de documents. De plus, il est possible de geler vos modifications si vous souhaitez conserver un historique des changements en cliquant sur le bouton "Figer l'itération en cours". Ceci figera l'itération et en créera une nouvelle qui sera éditable.

{% image /assets/images/documentation/2.0/fr/image74.png "Edition de données d'exemplaire - Figer l'itération"%}

Si un article possède des données d'exemplaire, l'icône suivant apparaîtra à sa droite dans l'arborescence :

{% image /assets/images/documentation/2.0/has_path_data.png "Possède des données d'exemplaire"%}

### Lien typé

Dans un produit, on a parfois besoin de lier certains articles entre eux de différentes façons. Das ce cas, vous pourrez utiliser les liens de chemin. Ces liens vous aident à définir de nouvelles structures pour un même produit, par exemple pour mettre en évidence des connexions électriques entre des articles.

Sélectionnez les 2 articles que vous voulez lier depuis la structure produit pour faire apparaître le bouton ci-dessous :

{% image /assets/images/documentation/2.0/fr/image75.png "Bouton Lien typé"%}

En cliquant sur ce bouton, vous pouvez ajouter un lien défini avec un type existant ou un nouveau type. Ce type sera utile par la suite pour afficher la nouvelle arborescence définie :

{% image /assets/images/documentation/2.0/fr/image76.png "Sélection du type"%}

Tout lien peut être modifié et supprimé.

### Barre de recherche d'article

Cependant, pour les produits complexes comprenant un très grand nombre d'articles, la tâche peut s'avérer fastidieuse. Prenez l'exemple du parcours de la structure produit représentée ci-dessus. Afin de faciliter l'opération, DocDokuPLM intègre une barre de recherche qui permet de trouver facilement un article à partir de son numéro ou de son nom. Le ou les réultat(s) de la recherche sont surlignés en jaune dans l'arbre.

{% image /assets/images/documentation/fr/image46.png "Barre de recherche"%}

Une alternative au moteur de recherche est la navigation dans le modèle géométrique 3D.

## Visualisation 3D d'un produit

Cliquez sur l'icône ci-dessous pour visualiser en 3D un produit, une ligne de base ou un exemplaire.

{% image /assets/images/documentation/2.0/3d_scene.png "Icône de visualisation 3D"%}

En cliquant sur une pièce, les résultats s’affichent sur la partie gauche de la page. L’article associé à cette pièce sera surligné en jaune ainsi que tous ses ascendants. Les informations relatives à cet article sont aussi affichées dans le menu de droite.

Cette solution peut s’avérer utile dans le cas où l’utilisateur ne connaît pas l’identifant de l’article.

{% image /assets/images/documentation/2.0/fr/image22.png "Navigation dans le modèle 3D"%}

En activant/désactivant le switch de l'article dans l'arborescence, vous affichez/cachez l'article correspondant dans la visualisation 3D.

{% image /assets/images/documentation/2.0/on_switch_button.png "Bouton switch - état activé"%}

Parmi les actions possibles dans le mode de visualisation en 3D, vous retrouverez :

* la création de marqueurs permettant par exemple de rapporter un dysfonctionnement d’une pièce sur le schéma 3D,
* la création de calques comportant plusieurs marqueurs,
* l'export d'un article pour produire le code html à intégrer dans d’autres pages web (comme YouTube ou Google Maps),
* la mesure de la distance entre 2 points.

# Gestion des processus

Un processus, ou flux des travaux, est la représentation des opérations affectées à un document ou un article. Ces opérations peuvent être effectuées par différents utilisateurs d’un même espace de travail.

## Les rôles

Pour créer un modèle de processus, il faut au préalable créer des rôles dans l’espace de travail.

{% image /assets/images/documentation/2.0/edit_roles.png "Bouton Rôles"%}

Ces rôles peuvent être assignés par défaut à un utilisateur ou à un groupe, mais ils peuvent être redéfinis lors de l'affectation du processus à la création d'un document ou d'un article.

{% image /assets/images/documentation/2.5/fr/image00.png "Création des rôles"%}

## Processus

### Modèle de processus

Un modèle de processus est composé d'un état initial, d'une série d'activités et d'un état final. Chaque activité contient un libellé définissant son état intermédiaire et une liste de tâches à effectuer. Ces tâches peuvent être effectuées en série ou en parallèle.

{% image /assets/images/documentation/2.0/add_workflow.png "Bouton Processus"%}

Pour une activité de type série, les tâches doivent être réalisées dans l'ordre. Le rejet d'une tâche entraîne l'arrêt de l'activité courante.

Pour une activité en parallèle, les tâches sont déroulées indépendamment de l'ordre dans lequel elles ont été créées. Il faut alors définir un nombre de tâche à compléter validant l’activité, variant de 1 au nombre total de tâches.

La validation d'une activité entraîne le démarrage de la suivante. Une activité invalidée entraînera la suspension du processus.

En cas d’invalidation, le processus reprendra à l’activité de relance si celle-ci a été préalablement définie.

Un modèle de processus peut être modifié n’importe quand. Cela n’entrainera en aucun cas la modification des processus instanciés depuis ce modèle.

{% image /assets/images/documentation/2.0/fr/image20.png "Création d'un modèle de processus"%}

Quand vous modifiez un processus, vous pouvez le dupliquer en cliquant sur ce bouton :

{% image /assets/images/documentation/2.0/duplicate_workflow.png "Dupliquer le processus"%}

Il suffit ensuite de renseigner un nom pour le nouveau processus copié.

{% image /assets/images/documentation/2.0/fr/image77.png "Copie d'un processus"%}

### Instance de processus

Chaque modèle de processus créé peut être instancié à la création d'un document ou d'un article. Les rôles peuvent être alors redéfinis.

{% image /assets/images/documentation/2.5/fr/image23.png "Définition des rôles à la création d’un document"%}

Une fois le document (ou l’article) créé, le processus démarre sur la première activité. Lorsqu'une tâche est ouverte, un mail est envoyé au responsable de la tâche en cours. Le responsable peut alors l'approuver ou la rejeter et signer. Si le responsable est un groupe, le mail est envoyé à tous les membres du groupe.

### Etat du cycle de vie

Une fois la première activité démarrée, les utilisateurs désignés reçoivent par mail un message contenant la description complète de leur(s) tâche(s) à effectuer.

{% image /assets/images/documentation/2.5/fr/image43.png "Processus instancié sur un document"%}

Une tâche peut être approuvée ou rejetée si :

* le responsable a téléchargé au moins une fois un fichier associé,
* le document ou l'article est libéré (pas réservé).

En cliquant sur le lien "Signature", vous aurez la possibilité d'ajouter une signature électronique.

Tous les utilisateurs abonnés aux changements d'état du processus en seront informés par mail.

C'est impossible de mettre à jour ou de redémarrer un processus arrêté. Le seul moyen de relancer un processus stoppé est de créer une nouvelle version de l'entité concernée et de lui assigner le même processus.

## Jalons

Les jalons permettent de définir des dates butoires pour vos projets et travaux en cours.

{% image /assets/images/documentation/2.0/fr/image81.png "Création d'un jalon"%}

## Anomalies

Cette page permet de rapporter des anomalies plus ou moins prioritaires sur vos projets et travaux en cours. Une correction d'anomalie peut :

* être affectée à un utilisateur,
* concerner des documents et / ou des articles que vous ajoutez dans l'onglet "Eléments affectés",
* appartenir à une catégorie.

Liste des catégories disponibles : adaptive, corrective, perfective, préventive.

{% image /assets/images/documentation/2.0/fr/image82.png "Création d'une anomalie"%}

## Demandes

Une demande de modification fonctionne de la même façon qu'une anomalie. On peut en outre y référencer des anomalies.

{% image /assets/images/documentation/2.0/fr/image83.png "Création d'une demande"%}

## Ordres

Un ordre fonctionne de la même façon qu'une anomalie. On peut en outre y référencer des demandes.

{% image /assets/images/documentation/2.0/fr/image84.png "Création d'un ordre"%}

# Réservation et libération

Vous pouvez réserver un document/article en le sélectionnant via sa case à cocher. Une nouvelle itération de l'élément sera créée. Vous pouvez sélectionner plusieurs éléments pour aller plus vite.

{% image /assets/images/documentation/image14.png "Boutons réserver / annuler la réservation / libérer"%}

Une fois réservé, l'élément ne sera pas éditable par les autres utilisateurs, il est vérouillé. Il vous faudra alors le libérer une fois les modifications effectuées, ou annuler la réservation si vous ne souhaitez pas enregistrer les changements apportés.

Si vous choisissez de libérer l'élément, une fenêtre vous proposera de saisir la note de révision. Cette information n’est pas obligatoire, vous pouvez passer cette étape en cliquant sur “Ignorer”.

{% image /assets/images/documentation/2.0/fr/image03.png "Fenêtre de note de révision"%}

Toutes ces actions sont également disponibles depuis l'onglet “Itération“ dans la fenêtre de détails de l'élément.

{% image /assets/images/documentation/2.0/fr/image49.png "Boutons Libérer et Annuler la réservation"%}

La date de révision indique la date de libération si l'élément est libéré ou la date de réservation si l'élément est réservé. Et la date de modification précise quand l'élément a été modifié pour la dernière fois (incluant la note de révision).

{% image /assets/images/documentation/2.0/status.png "Statuts réservé / vérouillé / libéré"%}

# Liste de valeurs

DocDokuPLM permet de prédéfinir des valeurs d'attributs, appelés liste de valeurs, que vous pourrez ensuite utiliser en tant qu'attribut pour un document, un article ou un modèle. Pour créer ou modifier des valeurs, cliquez sur l'icône suivante depuis la page des modèles :

{% image /assets/images/documentation/2.0/edit_lov.png "Bouton Listes de valeurs"%}

Par exemple, vous pouvez créer des valeurs d'attributs qui seront des couleurs.

{% image /assets/images/documentation/2.0/fr/image56.png "Fenêtre des listes de valeurs"%}

Une fois enregistrée, vous aurez accès à cette liste depuis l'onglet Attributs de la fenêtre de détail d'un modèle ou d'une entité. En attribuant une liste de valeurs à un modèle ou une entité, vous créez une nouvelle instance de cette liste.

{% image /assets/images/documentation/2.0/fr/image57.png "Choix d'une liste de valeurs"%}

Vous ne pouvez pas :

* supprimer une liste de valeurs qui a des instances,
* modifier une instance de liste de valeurs.

# Visualisation ou lien permanent

Pour chaque document/article, il est possible d’ouvrir un nouvel onglet dans le navigateur contenant les détails de sa dernière révision. Pour y accéder, il vous suffit de cliquer sur le titre de la fenêtre de détail.

{% image /assets/images/documentation/fr/image06.png %}

Vous pouvez visualiser les différentes propriétés de l'entité créée ainsi que les fichiers qui lui sont rattachés. La visionneuse prend en charge un nombre important de formats : pdf, jpg, mp4, doc… Les fichiers non supportés par la visionneuse seront automatiquement téléchargés.

{% image /assets/images/documentation/fr/image30.png "Visualisation d'un document"%}

# Gestion des fichiers

Un clic sur cette icône ouvre directement la fenêtre de détails d'un document/article ou d'un modèle à l'onglet Fichiers.

{% image /assets/images/documentation/2.0/file_icon.png "Accès rapide aux Fichiers"%}

Tout fichier - qu'il soit associé à une entité ou un modèle - peut être renommé en cliquant sur le petit crayon à droite du titre. Le nouveau titre sera enregistré seulement si vous cliquez sur le bouton valider.

{% image /assets/images/documentation/2.0/file_rename.png "Renommage du fichier"%}

Le téléchargement d'un fichier se lance en cliquant sur son nom et la suppression se fait en sélectionnant le fichier.

{% image /assets/images/documentation/2.0/file_delete.png "Suppression du fichier"%}

N'oubliez pas de cliquer sur le bouton Enregistrer de la fenêtre pour valider vos modifications.

# Gestion des liens vers des documents

Vous avez la possibilité d'ajouter des références vers des documents pendant l'édition d'un article/document. La gestion des liens se fait dans la fenêtre de modification d'une entité depuis l'onglet Liens.

{% image /assets/images/documentation/2.0/fr/image53.png "Gestion des liens"%}

Un lien de document se commente en cliquant sur le petit crayon à droite du titre. Le commentaire sera enregistré seulement si vous cliquez sur le bouton valider.

{% image /assets/images/documentation/2.0/fr/image54.png "Commenter un lien"%}

# Libellés

Vous pouvez associer des libellés à vos documents, articles, anomalies, demandes et ordres. En sélectionnant un ou des élément(s), l’icône suivante apparaît :

{% image /assets/images/documentation/fr/image26.png %}

Une fois cliquée, une fenêtre s’affiche et vous pouvez associer des libellés à ces éléments. Vous pouvez choisir parmi les libellés existants ou en créer de nouveaux.

{% image /assets/images/documentation/2.0/fr/image11.png "Fenêtre des libellés"%}

Pour afficher tous les éléments liés à un libellé, il vous suffit de sélectionner ce libellé dans le menu de gauche.

{% image /assets/images/documentation/fr/image34.png "Sélection d’un libellé"%}

Vous pouvez supprimer un libellé en cliquant sur la flèche dans la zone du libellé, puis sur “Supprimer”. Les éléments associés à ce libellé ne seront pas supprimés.

{% image /assets/images/documentation/fr/image38.png "Suppression d’un libellé"%}

# Recherche

Nous distinguons deux types de recherche : rapide et avancée.

## Recherche rapide

La barre de recherche rapide se présente au-dessus de la liste des documents/articles. Elle permet de trouver rapidement un élément à partir de son nom, son type, sa référence, sa version, son auteur, sa date de création, sa date de modification, ses attributs, le contenu des fichiers chargés.

{% image /assets/images/documentation/fr/image42.png "Barre de recherche rapide"%}

## Recherche avancée

Vous pouvez accéder à la recherche avancée de deux manières :

* en cliquant sur le lien “Rechercher“ présent dans le menu de gauche, seulement pour les documents,
* en cliquant sur la petite flèche dans la barre de “Recherche Rapide“.

Cette recherche avancée permet de trouver un élément à partir de plusieurs textes saisis concernant :

* son nom,
* son type,
* sa référence,
* sa version,
* son auteur,
* ses dates de création et de modification,
* ses attributs,
* le contenu des fichiers chargés.

{% image /assets/images/documentation/2.0/fr/image25.png "Recherche avancée"%}

# Options de partage et de publication

## Publication

Chaque document/article peut être publié. Pour cela il faut cliquer sur l’icône située à droite de la ligne correspondant à l'élément dans la liste.

{% image /assets/images/documentation/fr/publier.png %}

La fenêtre suivante apparaît :

{% image /assets/images/documentation/2.0/fr/image45.png "Fenêtre de publication d’un document"%}

Une fois l'élément publié en cliquant sur le bouton ON/OFF, il sera accessible depuis internet sans qu’une authentification soit nécessaire.

## Accès privé

Vous pouvez aussi protéger vos publications en utilisant l’accès privé. Vous pouvez choisir une date d’expiration et un mot de passe. Ces deux champs ne sont pas obligatoires, mais seront vérifiés à l’accès si vous les avez renseignés.

{% image /assets/images/documentation/fr/image40.png "Partage privé"%}

Ensuite vous devez cliquer sur “Partager” pour générer un lien. Ce lien est offusqué, il n’est pas devinable.

{% image /assets/images/documentation/fr/image48.png "Lien généré"%}
