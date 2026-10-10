# BUSINESS ANALYSIS — ERP SÉCURITÉ PRIVÉE
**Version :** 1.0  
**Méthodologie :** BMAD — Phase Business Analysis  
**Statut :** Draft consolidé — validation métier requise

---

## 1. Executive Summary

Le projet vise à créer une plateforme opérationnelle spécialisée pour les entreprises de sécurité privée, centrée sur la gestion des plannings, des ressources humaines opérationnelles et de la continuité des prestations.

Il ne s'agit pas de développer un ERP administratif généraliste. Le produit doit prioritairement répondre aux difficultés rencontrées quotidiennement par les exploitants dans la gestion des affectations et des changements de planning.

L'analyse métier a identifié une problématique centrale : **les absences et indisponibilités des agents perturbent les prestations, tandis que le manque de visibilité globale sur les ressources rend difficile l'identification rapide d'un remplaçant éligible.**

Le produit devra apporter une valeur mesurable en réduisant le temps nécessaire pour identifier un premier agent compatible avec une vacation à couvrir.

Cette orientation constitue la priorité métier initiale. Elle ne préjuge pas des fonctionnalités qui seront retenues ultérieurement.

## 2. Contexte et opportunité

### 2.1 Contexte métier

Les entreprises de sécurité privée organisent des prestations sur différents sites, avec des agents affectés à des postes et des horaires définis.

Leur activité peut combiner :

- Des prestations permanentes de gardiennage et de surveillance.
- Des missions ponctuelles ou événementielles.
- Des interventions sur plusieurs sites.
- Des organisations réparties entre plusieurs secteurs d'exploitation.

Les plannings reposent principalement sur une base récurrente, ajustée en fonction des absences, des besoins clients et des contraintes opérationnelles.

### 2.2 Problématique des outils existants

Les documents de vision initiaux présentent les solutions administratives existantes, notamment Comète, comme relativement développées sur les aspects administratifs, de paie et de facturation, mais moins adaptées à certaines difficultés quotidiennes de l'exploitation.

Ce constat constitue une appréciation issue du cadrage initial. Il reste à confronter aux pratiques et outils réellement utilisés par les entreprises ciblées.

### 2.3 Opportunité métier

L'opportunité consiste à mieux répondre aux besoins des exploitants confrontés à des changements fréquents, dans un contexte où les décisions doivent tenir compte simultanément des ressources disponibles, des exigences des postes, des règles applicables et des responsabilités organisationnelles.

## 3. Problème métier prioritaire

### 3.1 Problem Statement

Les exploitants des entreprises de sécurité privée doivent maintenir la couverture de prestations récurrentes malgré les absences et indisponibilités des agents.

Lorsqu'un remplacement devient nécessaire, ils rencontrent des difficultés pour identifier rapidement les agents éligibles à la vacation concernée.

Le manque de visibilité globale sur les ressources, les affectations et les contraintes associées est identifié comme la principale cause de cette difficulté.

Cette situation peut multiplier les vérifications, ralentir la recherche de remplaçants et augmenter le risque de non-couverture.

**Le problème prioritaire est de réduire le temps et l'incertitude nécessaires pour identifier un premier candidat éligible, sans compromettre les autres prestations.**

### 3.2 Chaîne causale retenue

1. Une absence ou une indisponibilité perturbe une vacation.
2. L'exploitant doit identifier un agent susceptible d'assurer le remplacement.
3. Les informations nécessaires à cette identification manquent de visibilité globale.
4. La recherche nécessite potentiellement plusieurs vérifications et recoupements.
5. Le délai d'identification peut retarder les démarches de remplacement.
6. Le risque de non-couverture augmente lorsque le temps disponible diminue.

Cette chaîne causale est retenue comme hypothèse centrale du Business Analysis. Elle devra être vérifiée à partir de situations réelles.

### 3.3 Conséquences métier potentielles

**Opérationnelles :**
- Retard dans l'identification d'un remplaçant.
- Vacation partiellement ou totalement non couverte.
- Réaffectations successives.
- Fragilisation d'autres prestations.

**Organisationnelles :**
- Sollicitations répétées des agents.
- Coordination entre plusieurs exploitants.
- Mobilisation de la direction pour les situations non résolues.
- Charge supplémentaire pour les responsables opérationnels.

**Économiques et contractuelles :**
- Coûts supplémentaires liés aux remplacements.
- Risque de non-respect des engagements contractuels.
- Dégradation possible de la relation client.

Ces conséquences restent à qualifier et à quantifier.

## 4. Vision et proposition de valeur

### 4.1 Vision produit

Développer une plateforme opérationnelle spécialisée permettant aux entreprises de sécurité privée de mieux organiser leurs prestations, de coordonner leurs ressources et d'absorber les changements quotidiens de planning.

### 4.2 Positionnement

Le produit est positionné comme une **plateforme métier dédiée à l'exploitation de la sécurité privée**, et non comme un ERP administratif complet.

Son périmètre initial privilégie la planification et la gestion des perturbations opérationnelles.

L'intégration éventuelle avec des outils administratifs existants reste une possibilité future, sans engagement fonctionnel à ce stade.

### 4.3 Proposition de valeur

Permettre aux exploitants d'identifier plus rapidement les agents éligibles à une vacation, afin de réduire l'effort de recherche et de faciliter la continuité des prestations dans les organisations multisites et multisecteurs.

### 4.4 Différenciation envisagée

La différenciation potentielle repose sur :

- Une approche centrée sur les contraintes quotidiennes des exploitants.
- La prise en compte des organisations hybrides et multisecteurs.
- L'importance accordée aux absences et aux changements de planning.
- La compréhension des exigences propres aux prestations de sécurité privée.

Cette différenciation n'est pas encore démontrée par une étude comparative des solutions du marché.

## 5. Parties prenantes et utilisateurs

### 5.1 Exploitant / chef de secteur

**Persona opérationnel prioritaire, à confirmer.**

Responsabilités envisagées :
- Organiser les affectations.
- Gérer les absences et les changements.
- Rechercher des remplaçants.
- Coordonner les ressources de son secteur.
- Signaler les risques sérieux de non-couverture.

Difficulté principale retenue : identifier rapidement les agents éligibles lorsque la situation opérationnelle change.

### 5.2 Direction d'exploitation

Responsabilités validées :
- Arbitrer les demandes de renfort entre secteurs lorsque nécessaire.
- Décider de la conduite à tenir lorsqu'une vacation ne peut pas être couverte.
- Être informée dès qu'un risque sérieux de non-couverture est identifié.

Les décisions d'arbitrage restent soumises aux obligations légales et réglementaires.

### 5.3 Agents de sécurité

Parties prenantes directement concernées par les affectations, les changements de planning et les sollicitations de remplacement.

Leurs attentes, contraintes et pratiques de disponibilité restent à approfondir.

### 5.4 Direction d'entreprise

Partie prenante potentiellement intéressée par la continuité des prestations, la maîtrise des coûts et la performance opérationnelle.

Son rôle exact dans les décisions d'achat et d'adoption reste à valider.

### 5.5 Autres acteurs

Les responsables de planification dédiés, les fonctions RH et les clients peuvent intervenir selon l'organisation des entreprises.

Leur rôle n'est pas encore suffisamment documenté pour être stabilisé.

## 6. Organisation et responsabilités métier

### 6.1 Organisation hybride

Les agents sont rattachés à un secteur principal, mais peuvent intervenir temporairement sur d'autres secteurs.

Plusieurs exploitants peuvent coordonner leurs ressources.

### 6.2 Renfort intersectoriel

La mobilisation d'un agent par un autre secteur nécessite une autorisation préalable du responsable de son secteur principal.

En cas de refus, la direction d'exploitation peut arbitrer. Sa décision est définitive sur le plan organisationnel, sous réserve des contraintes applicables.

En situation urgente, lorsque le responsable principal est indisponible, une personne dûment habilitée peut autoriser le renfort.

### 6.3 Responsabilité opérationnelle

Lorsqu'un agent rattaché au secteur A intervient temporairement sur le secteur B, le secteur B assume la responsabilité opérationnelle de cette mission.

Le rattachement principal de l'agent demeure inchangé.

Les conséquences administratives et RH de cette organisation restent à préciser.

### 6.4 Risque de non-couverture

L'exploitant recherche une solution de remplacement.

Dès qu'un risque sérieux de non-couverture est identifié, il informe la direction d'exploitation, même si la recherche se poursuit.

Lorsque la vacation ne peut pas être couverte, la direction décide de la conduite à tenir.

La définition opérationnelle d'un « risque sérieux » reste ouverte.

## 7. Success Criteria

### 7.1 Indicateur principal — KPI-01

**Nom :** Temps d'identification du premier agent éligible.

**Objectif métier :** Réduire le temps nécessaire à l'exploitant pour identifier un premier candidat compatible avec une vacation à couvrir.

**Point de départ proposé :** Début effectif de la recherche d'un remplaçant pour une vacation déterminée.

**Point d'arrivée validé :** Identification du premier agent éligible au regard des affectations connues, des qualifications et des contraintes applicables.

La disponibilité effective, l'acceptation de l'agent, les autorisations intersectorielles et la confirmation définitive du remplacement ne sont pas exigées pour arrêter cette mesure.

**Unité :** Minutes.

**Valeur de référence :** Non disponible — à mesurer.

**Valeur cible :** Non définie — à fixer après observation.

**Méthode d'analyse proposée :** Médiane et 90e percentile, avec suivi séparé des recherches sans candidat identifié.

### 7.2 Indicateurs complémentaires proposés

| Référence | Indicateur | Finalité |
|---|---|---|
| KPI-02 | Délai total de confirmation d'un remplacement | Évaluer la résolution opérationnelle |
| KPI-03 | Nombre de candidats examinés | Évaluer l'effort de recherche |
| KPI-04 | Proportion des recherches sans candidat éligible | Identifier les situations sans solution potentielle |
| KPI-05 | Taux de couverture des vacations affectées par une absence | Évaluer la continuité de service |
| KPI-06 | Conflits d'affectation provoqués par des remplacements | Vérifier la stabilité des autres prestations |

Ces indicateurs complémentaires restent proposés et nécessitent une validation métier.

### 7.3 Conditions de réussite

Le produit pourra être considéré comme apportant une valeur métier sur le problème prioritaire si :

1. Le temps d'identification diminue de manière mesurable par rapport à une référence fiable.
2. Les candidats identifiés satisfont réellement aux critères d'éligibilité définis.
3. L'amélioration ne se traduit pas par davantage de conflits d'affectation.
4. Le gain d'identification contribue à améliorer les conditions de résolution des absences.
5. Les résultats sont reproductibles dans des situations opérationnelles représentatives.

Les seuils quantitatifs restent à déterminer.

## 8. Données terrain à collecter

Pour établir les valeurs de référence, il est proposé d'observer des remplacements réels.

Informations à recueillir :

- Nature du poste et de la prestation.
- Délai entre le signalement de l'absence et la prise de poste prévue.
- Début de la recherche.
- Identification du premier candidat éligible.
- Nombre de candidats examinés.
- Résultat de la recherche, y compris les échecs.
- Confirmation éventuelle du remplacement.
- Nombre de secteurs impliqués.
- Couverture finale de la vacation.

L'observation devra inclure différents contextes : missions permanentes, prestations ponctuelles, horaires variés et absences de différents niveaux d'urgence.

Le protocole d'observation et la taille de l'échantillon restent à définir.

## 9. Hypothèses à valider

| Référence | Hypothèse | Validation recherchée |
|---|---|---|
| HYP-31 | Le manque de visibilité est le facteur dominant du délai de recherche | Observation de remplacements réels |
| HYP-32 | L'éligibilité d'un agent peut être définie sans ambiguïté | Validation des critères avec l'expert métier |
| HYP-33 | Le temps d'identification peut être mesuré de manière fiable | Test du protocole de mesure |
| HYP-34 | Une identification plus rapide améliore la résolution opérationnelle | Comparaison entre délai d'identification et délai de confirmation |
| HYP-35 | Le manque de visibilité concerne aussi les ressources intersectorielles | Entretiens avec plusieurs exploitants |
| HYP-36 | La difficulté est suffisamment fréquente et coûteuse pour justifier l'adoption du produit | Données terrain et entretiens auprès des entreprises ciblées |

Ces hypothèses n'ont pas encore été démontrées.

## 10. Périmètre métier

### 10.1 Priorité initiale

La priorité porte sur les problèmes opérationnels de planification, particulièrement la gestion des absences et l'identification de remplaçants éligibles.

### 10.2 Contexte métier à conserver

- Prestations permanentes et ponctuelles.
- Organisation multisites.
- Organisation multisecteurs.
- Contraintes professionnelles et réglementaires.
- Coordination des exploitants.
- Responsabilité de la direction en cas de non-couverture.

### 10.3 Domaines non prioritaires à ce stade

Les sujets suivants figurent dans les documents initiaux, mais ne sont pas retenus comme priorités du problème central :

- Recrutement et onboarding.
- Gestion administrative complète des agents.
- Paie et facturation.
- Représentation avancée des sites.
- Automatisation intelligente de la planification.
- Autres services périphériques.

Leur exclusion définitive n'est pas décidée. Leur éventuelle contribution au produit devra être évaluée ultérieurement.

## 11. Risques et contraintes métier

### 11.1 Contraintes réglementaires

Les règles de temps de travail, de repos, de qualification et d'habilitation devront être vérifiées auprès des référents compétents.

Les seuils évoqués dans les documents initiaux ne sont pas considérés comme juridiquement validés.

### 11.2 Disponibilité réelle des ressources

Une meilleure visibilité ne crée pas de nouveaux agents disponibles.

La valeur du produit dépendra notamment de la proportion de situations dans lesquelles des candidats éligibles existent, mais sont difficiles à identifier.

### 11.3 Qualité des informations

Une information incomplète ou obsolète peut fausser l'appréciation de l'éligibilité.

### 11.4 Variabilité des organisations

Les responsabilités et pratiques peuvent différer selon la taille de l'entreprise, le nombre de secteurs et le type de prestation.

### 11.5 Adoption

Les bénéfices attendus devront être suffisamment importants pour justifier un changement des pratiques opérationnelles existantes.

## 12. Points restant à approfondir

Avant validation finale du Business Analysis :

1. Définir le segment d'entreprises à cibler en priorité.
2. Confirmer les personas et les décideurs d'achat.
3. Observer des remplacements réels pour mesurer le KPI-01.
4. Valider les critères métier d'éligibilité.
5. Vérifier les causes du manque de visibilité.
6. Évaluer les alternatives actuellement utilisées.
7. Qualifier la fréquence et le coût des difficultés.
8. Fixer une cible de réussite réaliste.
9. Préciser les frontières du périmètre métier initial.

## 13. Registre des décisions validées

| Réf. | Décision |
|---|---|
| DEC-01 | Plateforme opérationnelle spécialisée, non ERP administratif généraliste |
| DEC-02 | Priorité à la complexité de la planification |
| DEC-03 | Prise en compte des prestations permanentes, ponctuelles et multisites |
| DEC-04 | Organisation hybride avec secteur principal et renforts possibles |
| DEC-05 | Autorisation préalable du responsable du secteur principal |
| DEC-06 | Arbitrage définitif de la direction d'exploitation en cas de refus |
| DEC-07 | Autorisation possible par un responsable habilité en situation urgente |
| DEC-08 | Responsabilité opérationnelle du secteur bénéficiaire du renfort |
| DEC-09 | Décision de la direction lorsqu'une vacation ne peut être couverte |
| DEC-10 | Information de la direction dès l'identification d'un risque sérieux |
| DEC-11 | Planning construit sur une base récurrente continuellement ajustée |
| DEC-12 | Changements quotidiens comme difficulté opérationnelle prioritaire |
| DEC-13 | Absences et indisponibilités comme principale perturbation |
| DEC-14 | Identification des agents mobilisables comme principal blocage |
| DEC-15 | Manque de visibilité globale comme cause principale retenue |
| DEC-16 | Réduction du temps d'identification comme indicateur principal |
| DEC-17 | KPI arrêté à l'identification du premier agent éligible |

## 14. Conclusion

Le Business Analysis a permis de faire émerger un problème métier prioritaire et de le relier à un critère de réussite mesurable.

Le projet ne se définit plus uniquement comme un outil de planification destiné aux entreprises de sécurité privée. Sa proposition de valeur initiale repose sur la capacité à réduire la difficulté et le temps nécessaires pour identifier des agents éligibles lors des perturbations de planning.

**Cette orientation constitue la base de référence pour poursuivre la découverte métier.**

La validation finale du Product Brief reste conditionnée à la confrontation des hypothèses avec les pratiques des exploitants, à la définition du segment cible et à la mesure des performances actuelles.

**Statut final : Business Analysis V1.0 — Consolidé, non encore validé terrain.**
