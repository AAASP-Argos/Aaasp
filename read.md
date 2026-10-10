# Compléter le brainstorming avant la modélisation

**Source :** [Contexte métier](docs/00_bizness/context.md).  
**Objectif :** Compléter les informations métier nécessaires pour passer à `docs/01_model/`, sans refaire la découverte déjà documentée ni choisir une solution technique.  
**Statut :** Liste de clarifications à traiter, pas de nouvelles règles validées.

Ce support sert d’abord à rassembler les informations que tu possèdes déjà. Pour chaque point, ajouter ta réponse ou la référence du document qui la contient. Interroger le client uniquement sur ce qui reste inconnu ou contradictoire. Les réponses ci-dessous ne deviennent pas automatiquement la source de vérité : leur intégration dans `docs/` reste soumise à validation humaine.

## Ce qu’il n’est pas nécessaire de redemander

Le positionnement, le problème prioritaire, le principe du secteur principal, les autorisations de renfort, les responsabilités et la définition de l’arrivée du KPI-01 sont déjà documentés. S’appuyer sur le registre DEC-01 à DEC-17 plutôt que reprendre un questionnaire général sur ces choix.

## Points à compléter pour décrire le fonctionnement métier

Les questions ci-dessous précisent les notions, relations et comportements encore peu détaillés dans le contexte. Elles ne présupposent ni les futures entités ni leur organisation technique.

### 1. Vocabulaire et structure des prestations

- Que désignent exactement « prestation », « mission », « site », « poste », « vacation », « affectation » et « secteur » dans ton fonctionnement ? Quels termes sont synonymes et lesquels doivent rester distincts ?
- Comment ces notions se rattachent-elles entre elles ? Par exemple, un poste peut-il nécessiter plusieurs agents sur la même plage horaire ? Décrire les possibilités réellement utilisées, sans retenir cet exemple comme une règle.
- Quelles informations minimales décrivent une vacation et permettent de la distinguer d’une autre ? Comment représentes-tu métier une vacation qui traverse minuit ?

**À apporter :** un exemple réel de prestation, décomposé avec tes propres termes, et les variantes qui changent cette structure.

### 2. Planning récurrent et affectations

- Comment un planning récurrent devient-il un ensemble de vacations concrètes ? Sur quelle période travailles-tu ?
- Quand une vacation ou une affectation est-elle considérée comme prévue, communiquée, confirmée, modifiée ou annulée ? Quels termes utilises-tu réellement pour ces situations ?
- Lorsqu’une occurrence change, faut-il modifier uniquement cette occurrence ou aussi la récurrence ? Qui en décide et quelles conséquences faut-il conserver ?

**À apporter :** un planning récurrent avec une exception et le déroulement de sa modification.

### 3. Absence et besoin de remplacement

- Qui signale une absence ou une indisponibilité, et quelles informations sont nécessaires pour la prendre en compte ? Quelle différence fais-tu entre ces deux notions ?
- Une absence peut-elle toucher plusieurs vacations ou seulement une partie d’une vacation ? Comment détermine-t-on ce qui reste à couvrir ?
- Que se passe-t-il si l’absence est corrigée ou annulée après le début de la recherche ou après la confirmation d’un remplaçant ?

**À apporter :** un cas simple et un cas avec plusieurs vacations ou une couverture partielle, s’ils existent dans ton activité.

### 4. Critères d’éligibilité

- Quelle est la liste exacte des critères obligatoires pour chaque type de poste ? Lesquels sont des préférences ?
- Quelles informations de l’agent et de la vacation permettent de vérifier chaque critère ? Comment traite-t-on les informations manquantes ou expirées ?
- Qu’est-ce qu’un conflit d’affectation dans les cas réels : chevauchement, trajet, repos ou autre contrainte ? Quelles règles et quels seuils sont documentés, et lesquels doivent encore être validés par un référent ?

**À apporter :** un tableau « critère / condition d’éligibilité / information nécessaire / source / validation restante », avec un exemple accepté et un exemple refusé. Référence : HYP-32.

### 5. Recherche et confirmation du remplacement

- Quel événement ouvre une recherche et quand la considère-t-on terminée ? Peut-on la suspendre ou la reprendre ?
- Comment passe-t-on d’un candidat éligible à un remplacement confirmé ? Qui contacte, accepte, autorise et confirme, et dans quel ordre réel ?
- Plusieurs personnes peuvent-elles rechercher ou solliciter des candidats pour la même vacation ? Que fait-on si plusieurs agents acceptent ou si le remplaçant se désiste ?
- Que conserve-t-on lorsqu’aucun candidat n’est trouvé ou qu’une recherche est abandonnée ?

**À apporter :** la succession des actions, décisions et changements de situation, du signalement à la confirmation ou à l’échec. Garder distincts l’identification du premier candidat et la confirmation du remplacement, conformément au KPI-01.

### 6. Renfort intersectoriel et escalade

- Comment sait-on qui est habilité à autoriser un renfort, notamment en urgence ? Comment l’accord, le refus et l’arbitrage sont-ils constatés ?
- Que fait-on en cas de demande sans réponse, de demandes concurrentes ou de retrait d’une autorisation ?
- Quels faits déclenchent concrètement l’alerte de risque sérieux de non-couverture ? Qui reçoit l’alerte et quelles suites doit-on suivre ?
- Quelles conséquences administratives ou RH du renfort doivent être connues pour comprendre le processus initial, et lesquelles peuvent rester hors périmètre ?

**À apporter :** les cas limites et les précisions d’application. Ne pas rouvrir les responsabilités déjà actées en DEC-05 à DEC-10, sauf contradiction constatée.

### 7. Responsabilités, visibilité et historique

- Pour chaque action du processus, qui peut consulter, proposer, modifier, autoriser ou annuler ? Comment cela varie-t-il selon le secteur et la personne qui assure le relais ?
- Quelles informations font foi pour les affectations et les qualifications ? Qui est responsable de leur mise à jour ?
- Quels changements doivent rester consultables : auteur, date, motif, ancienne situation, décision ? Quelles informations ne doivent pas être visibles par tous ?

**À apporter :** une liste des actions avec leurs responsables, leurs limites et les traces métier nécessaires. Décrire les besoins sans choisir de mécanisme technique de gestion des droits.

## Délimiter ce que le premier modèle doit couvrir

À partir des réponses précédentes, préciser :

- Le scénario traité de bout en bout dans le premier modèle.
- Les variantes indispensables, et celles explicitement reportées.
- Les informations externes nécessaires au fonctionnement, sans décider maintenant d’une intégration.
- Les règles certaines, les propositions et les points qui nécessitent encore une validation compétente.

La cible chiffrée du KPI-01, le protocole d’observation complet et les informations d’achat restent des sujets de découverte à suivre. Leur absence ne doit pas empêcher de préparer un modèle métier provisoire lorsque les concepts et processus concernés sont suffisamment décrits.

## Vérifier que le brainstorming permet de commencer le modèle

- [ ] Les termes métier importants sont définis sans ambiguïté majeure.
- [ ] Les informations nécessaires et les liens entre notions sont illustrés par des cas réels.
- [ ] Un scénario nominal est décrit de bout en bout avec les acteurs responsables.
- [ ] Les principales exceptions et les changements de situation sont explicités.
- [ ] Les critères d’éligibilité et les règles connues sont séparés des préférences et des inconnues.
- [ ] Les faits métier à conserver et leurs conséquences sont identifiés.
- [ ] Le périmètre initial et les questions ouvertes sont explicites.

Cette liste évalue la préparation du modèle ; elle ne vaut pas approbation. Une question ouverte doit bloquer uniquement la partie qui dépend de sa réponse. Les entités, agrégats et choix de conception seront proposés pendant la modélisation, à partir du brainstorming consolidé.

## Format simple pour compléter les réponses

Pour chaque thème :

- **Informations déjà disponibles :** réponse ou lien vers tes notes existantes.
- **Exemple concret :** situation réelle et résultat attendu.
- **Reste à clarifier :** question précise, sans reprendre les éléments déjà connus.
- **Validation nécessaire :** personne ou document à consulter, si applicable.

Une fois les réponses réunies, préparer leur intégration dans la source de vérité `docs/` pour validation, puis utiliser cette version consolidée comme base du modèle.
