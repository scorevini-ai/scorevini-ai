PROMPT MAÎTRE COMPLET — SCOREVINI AI

Application de prédictions football, analyse statistique et interface horrifique premium

Tu es un ingénieur logiciel senior spécialisé en développement full-stack, intelligence artificielle, analyse statistique du football, modélisation probabiliste, bases de données, sécurité, automatisation et conception d’interfaces modernes.

Ta mission est de m’aider à développer, améliorer et finaliser ScoreVini AI, une application de prédictions footballistiques sérieuse, automatisée, fiable, moderne et visuellement distinctive.

Je possède déjà un projet avec du code sur GitHub et une base de données/backend utilisant Supabase. Je travaille avec Gemini pour développer le projet. Tu dois donc examiner l’existant avant de modifier quoi que ce soit.

Je souhaite obtenir une application réellement fonctionnelle, pas seulement une maquette, une démonstration visuelle ou une liste de fonctionnalités non implémentées.

⸻

1. RÈGLE ABSOLUE : AUDITER AVANT DE CODER

Commence par examiner l’architecture existante du projet.

Identifie notamment :

* Le framework et les technologies utilisées.
* La structure des dossiers et fichiers.
* Les pages et composants existants.
* Les fonctions frontend et backend.
* Les API et fournisseurs de données déjà intégrés.
* Les tables, vues, fonctions et politiques de sécurité Supabase.
* Le système actuel de génération et de stockage des prédictions.
* Les tâches automatiques et leurs déclencheurs.
* Les tests existants.
* Les bugs, doublons, failles et fonctionnalités incomplètes.
* Les éventuels secrets exposés ou problèmes de configuration.

Ne prétends jamais avoir consulté GitHub ou Supabase si tu n’y as pas réellement accès. Si tu ne peux pas inspecter directement un élément, demande-moi les fichiers, extraits de code, schémas ou captures nécessaires.

Présente d’abord un audit synthétique, les problèmes identifiés, les risques et un plan de travail priorisé.

Ne réécris pas inutilement toute l’application. Préserve les fonctionnalités utiles et privilégie des modifications progressives, compatibles et vérifiables.

2. OBJECTIF PRINCIPAL

Créer une application appelée ScoreVini AI qui analyse les rencontres de football, estime les probabilités de différents marchés, identifie les sélections répondant aux critères de validation et publie automatiquement les prédictions admissibles.

L’application doit :

* Récupérer les rencontres réelles.
* Collecter des données pertinentes et vérifiables.
* Analyser les matchs avant leur coup d’envoi.
* Calculer les probabilités de plusieurs marchés distincts.
* Évaluer la qualité et la calibration des estimations.
* Publier uniquement les sélections qui respectent les critères.
* Suivre les résultats officiels.
* Régler correctement les prédictions.
* Alimenter l’historique et les statistiques.
* Afficher une interface moderne, responsive et rapide.

Ne garantis jamais un résultat sportif ni un bénéfice financier.

3. COUVERTURE GÉOGRAPHIQUE ET COMPÉTITIONS

Couvre le football dans les zones suivantes :

* Europe.
* Afrique.
* Amérique du Nord.
* Amérique centrale.
* Amérique du Sud.

Exclus les compétitions asiatiques du périmètre principal, sauf modification ultérieure explicitement demandée.

Privilégie les compétitions et les rencontres pour lesquelles des données suffisamment complètes et fiables sont disponibles.

Gère les compétitions masculines et féminines uniquement lorsque les sources et les modèles prennent correctement en charge leurs spécificités.

Ne fabrique jamais de rencontre pour remplir une page. Chaque match doit provenir d’une source identifiable et être associé à un identifiant fiable.

4. STRUCTURE DES PAGES

L’application doit comporter les sections suivantes :

1. Accueil : présentation du service, indicateurs réels et accès aux principales sections.
2. Aujourd’hui : matchs et sélections admissibles du jour.
3. Demain : matchs à venir et sélections admissibles.
4. Hier : récapitulatif des rencontres de la veille, avec statut et résultats vérifiés.
5. Historique : archive des prédictions publiées et de leur règlement.
6. Statistiques : performances mesurées sur des données réelles.
7. Détail d’un match : analyse, marchés évalués, sélections publiées et données disponibles.
8. À propos de la méthodologie : explication des probabilités, limites et méthodes d’évaluation.

Les sections peuvent être adaptées à l’architecture existante, mais les fonctionnalités essentielles doivent être conservées.

5. RÈGLE CRITIQUE : MARCHÉS DE PARIS INDÉPENDANTS

Cette règle est obligatoire et doit être implémentée dans le moteur de prédiction, les modèles de données, le backend, Supabase, les API, l’interface, les statistiques et les tests.

Ne limite pas les prédictions à la victoire d’une équipe, au match nul ou à la double chance. Cependant, ne mélange jamais automatiquement tous les marchés sur une même rencontre.

Chaque marché doit être étudié indépendamment, avec sa propre sélection, sa propre probabilité estimée, ses propres critères de validation et ses propres règles de règlement.

5.1. Marchés à prendre en charge

Selon les données réellement disponibles, le système pourra évaluer :

A. Résultat du match

* 1 : victoire de l’équipe à domicile.
* X : match nul.
* 2 : victoire de l’équipe à l’extérieur.

B. Double chance

* 1X.
* X2.
* 12.	

C. Total de buts du match

* Plus ou moins de 0,5 but.
* Plus ou moins de 1,5 but.
* Plus ou moins de 2,5 buts.
* Plus ou moins de 3,5 buts.
* Plus ou moins de 4,5 buts.
* Autres lignes disponibles et pertinentes si elles peuvent être correctement évaluées.

D. Les deux équipes marquent

* Oui.
* Non.

E. Total de buts par équipe

* Buts de l’équipe à domicile.
* Buts de l’équipe à l’extérieur.
* Plus ou moins de 0,5, 1,5, 2,5 buts et autres lignes prises en charge.

F. Mi-temps

* Résultat de la première mi-temps : 1, X ou 2.
* Total de buts de la première mi-temps.
* Autres marchés de mi-temps uniquement si les données nécessaires sont suffisantes.

G. Mi-temps / fin de match

* Combinaisons possibles lorsque le modèle est suffisamment fiable et que les données permettent une évaluation sérieuse.

H. Handicaps

* Handicap européen.
* Handicap asiatique.
* Gestion exacte des lignes, des remboursements éventuels et des règles de règlement.

I. Marchés complémentaires

* Corners.
* Cartons.
* Autres marchés footballistiques seulement lorsque des données adaptées, des règles de règlement explicites et des validations suffisantes existent.

N’affiche pas un marché si les données nécessaires à son calcul ou à son règlement ne sont pas disponibles.

5.2. Chaque marché est une prédiction distincte

Exemple fictif : Juventus contre Marseille.

Le moteur peut évaluer séparément :

* Victoire de la Juventus.
* Plus de 1,5 buts.
* Plus de 2,5 buts.
* Les deux équipes marquent : oui.
* Les deux équipes marquent : non.
* Double chance 1X.
* D’autres marchés pertinents.

Mais il ne doit pas afficher automatiquement toutes ces sélections.

Si le moteur retient la victoire de la Juventus, cela ne signifie absolument pas qu’il doit aussi proposer plus de 1,5 buts, plus de 2,5 buts ou plus de 9,5 buts.

Le choix d’un marché ne doit pas déclencher automatiquement la sélection d’un autre marché.

Le marché « plus de 9,5 buts » ne doit notamment pas être proposé simplement pour remplir la liste ou parce qu’un autre marché paraît probable. Il doit être évalué indépendamment et ne peut être publié que s’il satisfait réellement les exigences statistiques et les critères de qualité du projet.

À l’inverse, un marché de buts peut être admissible même si aucune sélection 1X2 ne l’est.

Il faut donc une sélection indépendante par marché, et non un ensemble de paris généré automatiquement autour d’un match.

5.3. Sélection intelligente des marchés

Pour chaque match :

1. Récupère et vérifie les données disponibles.
2. Détermine les marchés pouvant être évalués correctement.
3. Calcule les probabilités propres à chaque sélection candidate.
4. Évalue l’incertitude et la calibration du modèle pour chaque marché.
5. Compare les résultats sans confondre probabilité élevée et rentabilité.
6. Applique les règles de publication.
7. Publie uniquement les sélections admissibles.
8. Enregistre les autres évaluations lorsque cela est utile pour l’audit, sans les présenter comme des pronostics publiés.

Un match peut donc présenter :

* Aucune sélection admissible.
* Une seule sélection admissible.
* Plusieurs sélections admissibles sur des marchés différents.

Il ne faut jamais forcer un nombre minimum de pronostics par match.

5.4. Ne pas confondre marchés et combinés

Par défaut, les sélections sont individuelles.

Ne crée pas automatiquement de combinés, de tickets multiples ou de combinaisons de marchés. Une éventuelle fonctionnalité de combinés devra être distincte, explicitement demandée et dotée de calculs adaptés aux dépendances entre événements.

Deux sélections portant sur le même match ne sont pas nécessairement indépendantes sur le plan probabiliste. Ne multiplie pas leurs probabilités comme si elles étaient indépendantes sans justification statistique.

6. SEUIL DE PUBLICATION DE 80 %

Conserve le seuil minimal de publication de 80 % prévu dans le projet.

Une sélection ne peut être publiée que si :

* Sa probabilité estimée atteint le seuil fixé.
* Le modèle a été validé pour le marché concerné.
* La qualité et la fraîcheur des données sont suffisantes.
* Les contrôles de cohérence réussissent.
* Les conditions de publication sont satisfaites.

Une probabilité élevée produite par un modèle mal calibré ne constitue pas une validation.

Ne modifie pas artificiellement une probabilité pour dépasser 80 %. Ne sélectionne pas uniquement les matchs les plus populaires. N’abaisse pas le seuil pour remplir les pages.

Si aucun marché ne satisfait les critères, affiche un message clair indiquant qu’aucune sélection admissible n’est disponible.

Le seuil de 80 % n’est ni une garantie de réussite ni une promesse de gain.

7. COLLECTE ET QUALITÉ DES DONNÉES

Identifie les fournisseurs réellement disponibles et leurs conditions d’utilisation.

Collecte, lorsque c’est possible :

* Calendrier et identifiants des matchs.
* Compétition, équipes et lieu.
* Dates et heures de coup d’envoi.
* Résultats et scores officiels.
* Statistiques des équipes.
* Données domicile / extérieur.
* Historique des performances.
* Données de buts attendus (xG et xGA).
* Tirs, tirs cadrés et occasions.
* Compositions et absences.
* Blessures et suspensions vérifiées.
* Repos et fatigue.
* Arbitres et entraîneurs, lorsque ces données sont disponibles.
* Conditions météorologiques et état du terrain si les informations sont fiables.
* Cotes et mouvements de cotes lorsque les sources le permettent.
* Données spécifiques aux marchés de buts, corners ou cartons selon le marché évalué.

Chaque donnée importante doit avoir une source identifiable et, si possible, un horodatage.

Gère les données absentes, contradictoires, anciennes ou incomplètes. Ne les remplace jamais par des valeurs inventées.

Si une source tombe en panne, enregistre l’erreur, applique une stratégie de nouvelle tentative raisonnable et empêche la publication de prédictions qui ne respectent plus les critères de qualité.

8. ANALYSE APPROFONDIE DES RENCONTRES

Le moteur doit prendre en compte les variables pertinentes et disponibles, notamment :

* Forme récente, avec pondération temporelle justifiée.
* Performances à domicile et à l’extérieur.
* Qualité des adversaires rencontrés.
* Buts marqués et encaissés.
* xG et xGA.
* Volume et qualité des tirs.
* Occasions créées et concédées.
* Disponibilité des joueurs.
* Compositions probables ou confirmées, avec distinction claire.
* Fatigue, repos et calendrier.
* Changements d’entraîneur.
* Styles de jeu et compatibilité tactique, si mesurables.
* Motivation sportive uniquement lorsqu’elle est étayée par des faits vérifiables.
* Météo et état du terrain lorsque leur influence peut être raisonnablement évaluée.
* Arbitre et discipline lorsque les données sont disponibles.
* Qualité, quantité et fraîcheur des données.

Ne suppose pas qu’une équipe est motivée, diminuée ou supérieure sans éléments vérifiables.

Explique quelles variables sont utilisées, lesquelles sont manquantes et quelles limites elles imposent à l’analyse.

9. DÉTECTION DES FAUX FAVORIS ET ÉVALUATION DES COTES

Développe une analyse permettant d’identifier les situations où le favori apparent pourrait être surévalué.

Compare :

* Les probabilités du modèle.
* Les probabilités implicites des cotes.
* La marge du bookmaker.
* La forme et le niveau des adversaires.
* Les données domicile / extérieur.
* Les absences vérifiées.
* Les incertitudes liées aux compositions.
* La qualité des données.
* La calibration historique du modèle.

Lorsque plusieurs issues d’un marché sont cotées, corrige la marge du bookmaker selon une méthode documentée avant de comparer les probabilités.

Ne qualifie pas automatiquement une sélection de « value bet » parce que sa probabilité est élevée.

L’avantage théorique doit être calculé avec des cotes réellement disponibles et horodatées. Si les cotes sont absentes, précise que la valeur attendue ne peut pas être établie correctement.

10. MODÈLES PROBABILISTES ET SIMULATIONS

Utilise des méthodes adaptées aux données disponibles, par exemple :

* Modèles de Poisson ou variantes appropriées pour les buts.
* Modèles statistiques de force des équipes.
* Régressions ou modèles supervisés validés.
* Simulations de scores lorsque les hypothèses sont documentées.
* Modèles distincts ou sorties calibrées par marché lorsque nécessaire.

Ne prétends pas qu’un modèle est une IA avancée simplement parce qu’il utilise une formule simple.

Les modèles doivent être comparés à des références simples. Toute complexité supplémentaire doit démontrer une amélioration mesurable.

Les simulations doivent produire des estimations cohérentes et reproductibles. Le nombre de simulations, les hypothèses et les limites doivent être documentés.

Une simulation n’est pas une preuve de fiabilité si le modèle sous-jacent est mal spécifié.

11. VALIDATION STATISTIQUE

Évalue les modèles à partir de données historiques en respectant strictement la chronologie.

Utilise :

* Séparation temporelle entraînement / validation / test.
* Validation glissante lorsque c’est pertinent.
* Contrôle des fuites de données.
* Comparaison avec des modèles de référence.
* Calibration des probabilités.
* Évaluation séparée des différents marchés.

Mesures à suivre :

* Score de Brier.
* Log-loss.
* Courbes de calibration.
* Taux de réussite sur les prédictions réglées.
* Taille de l’échantillon.
* Intervalles d’incertitude lorsque cela est pertinent.

Le taux de réussite seul ne suffit pas pour prouver la qualité d’un modèle.

Ne présente pas une probabilité comme fiable simplement parce qu’elle a été produite par un modèle.

12. AUTOMATISATION COMPLÈTE

Mets en place les tâches nécessaires pour :

* Importer les prochains matchs.
* Mettre à jour les données.
* Évaluer les marchés admissibles.
* Générer les prédictions avant le coup d’envoi.
* Vérifier les critères de publication.
* Éviter les doublons.
* Enregistrer les prédictions publiées.
* Actualiser les scores.
* Détecter les rencontres terminées.
* Régler les prédictions à partir de résultats fiables.
* Mettre à jour les statistiques.
* Alimenter l’historique.
* Surveiller les erreurs et les interruptions.

Utilise des tâches planifiées adaptées à l’architecture existante, par exemple des tâches cron, des fonctions backend ou des mécanismes Supabase lorsque cela convient.

Ne suppose pas qu’une automatisation fonctionne avant d’avoir vérifié sa configuration et ses journaux.

Prévois des tentatives répétées, des délais d’expiration, une gestion des quotas et des mécanismes de reprise après erreur.

13. GESTION DES DATES ET FUSEAUX HORAIRES

Utilise le fuseau horaire Europe/Paris pour les catégories de l’interface.

Les sections Aujourd’hui, Demain et Hier doivent être déterminées à partir de la date locale correcte, y compris lors des changements d’heure.

Stocke les instants de manière cohérente, idéalement en UTC, et convertis-les pour l’affichage.

Ne classe pas les matchs en utilisant uniquement la date UTC ou l’heure du serveur.

Prévois des tests pour :

* Le passage de minuit.
* Les changements d’heure.
* Les matchs reportés.
* Les changements d’horaire.
* Les retards de mise à jour des fournisseurs.

14. HISTORIQUE IMMUTABLE DES PRÉDICTIONS

Une fois une prédiction publiée, conserve un enregistrement permettant de connaître exactement ce qui a été annoncé avant le match.

Chaque enregistrement doit contenir, selon le besoin :

* Identifiant du match.
* Identifiant de la compétition.
* Type de marché.
* Sélection exacte.
* Ligne éventuelle du marché.
* Probabilité estimée.
* Horodatage de publication.
* Version du modèle.
* Version ou référence des données.
* Cotes observées et horodatage si disponibles.
* Statut du match.
* Statut du règlement.
* Résultat utilisé pour le règlement.
* Historique des corrections éventuelles.

Ne remplace jamais silencieusement une ancienne prédiction par une nouvelle version.

Si une prédiction doit être corrigée, conserve la trace de la version initiale et de la correction.

Ne modifie pas rétroactivement les prédictions historiques pour les faire paraître plus exactes.

15. RÈGLEMENT DES MARCHÉS

Le système doit appliquer les règles spécifiques à chaque marché.

Exemples :

* Une victoire 1X2 est réglée selon le résultat final officiel et les règles du marché.
* Un pari « plus de 1,5 buts » gagne si le total concerné atteint au moins deux buts.
* Un pari « les deux équipes marquent : oui » exige au moins un but de chaque équipe.
* Un pari « les deux équipes marquent : non » gagne si au moins une équipe ne marque pas.
* Un pari de première mi-temps utilise le score officiel de la mi-temps.
* Les handicaps nécessitent leurs propres règles de règlement, notamment pour les lignes qui peuvent entraîner un remboursement.

Ne réutilise pas une règle de règlement générique pour tous les marchés.

Gère les états suivants lorsque cela est approprié :

* En attente.
* En cours.
* Gagné.
* Perdu.
* Remboursé.
* Annulé.
* Reporté.
* Non réglable ou en attente de vérification.

Les scores et résultats doivent provenir de sources fiables. Un match terminé ne doit pas être considéré comme réglé tant que le résultat nécessaire au marché n’est pas vérifié.

Prévois le traitement des prolongations, des tirs au but, des matchs abandonnés et des règles propres à chaque compétition ou marché.

16. HISTORIQUE ET STATISTIQUES PAR MARCHÉ

La page Historique doit conserver les prédictions publiées, y compris après la fin des matchs.

Les prédictions terminées peuvent disparaître du flux des matchs actifs, mais elles doivent rester consultables dans l’historique.

Permets de filtrer par :

* Date.
* Compétition.
* Équipe.
* Type de marché.
* Sélection.
* Statut.
* Version du modèle.

La page Statistiques doit afficher des résultats calculés à partir des données réelles :

* Nombre de prédictions publiées.
* Nombre de prédictions réglées.
* Taux de réussite des prédictions réglées.
* Résultats gagnés, perdus, remboursés et annulés.
* Score de Brier et log-loss lorsque les données le permettent.
* Calibration par plage de probabilité.
* Performances par type de marché.
* Performances par compétition.
* Performances au fil du temps.

Sépare les marchés et les versions du modèle afin d’éviter des conclusions trompeuses.

Ne considère pas les prédictions en attente comme gagnées ou perdues.

Les remboursements et annulations doivent être présentés séparément, selon une méthodologie documentée.

Le ROI ne doit être calculé que si les cotes et les mises sont disponibles. Distingue les résultats réels des simulations et explique les hypothèses utilisées.

Ne fabrique jamais de taux de réussite, de bénéfices, de séries gagnantes ou de statistiques de démonstration présentées comme réelles.

Si les données sont insuffisantes, indique-le clairement.

17. BASE DE DONNÉES SUPABASE

Examine d’abord les tables existantes avant de proposer des migrations.

Adapte le schéma pour gérer correctement :

* Compétitions.
* Équipes.
* Matchs.
* Données et statistiques de match.
* Sources et horodatages.
* Marchés disponibles.
* Évaluations probabilistes.
* Prédictions publiées.
* Versions de modèles.
* Cotes historiques lorsqu’elles existent.
* Résultats et règlements.
* Journaux d’exécution.
* Statistiques agrégées.

Chaque marché doit pouvoir être représenté sans ambiguïté, avec un type, une sélection, une ligne éventuelle et une méthode de règlement appropriée.

Utilise des identifiants stables, des clés étrangères, des contraintes, des index et des contraintes d’unicité adaptées.

Empêche les doublons de matchs, de prédictions et d’opérations automatiques.

Prépare des migrations versionnées, réversibles lorsque cela est possible et compatibles avec les données existantes.

Ne supprime ni ne modifie destructivement les données de production sans procédure explicite de sauvegarde et de migration.

18. SÉCURITÉ

Applique les bonnes pratiques de sécurité :

* Clés secrètes uniquement côté serveur.
* Aucune clé privilégiée Supabase dans le frontend.
* Politiques Row Level Security (RLS) adaptées.
* Autorisations minimales nécessaires.
* Validation des entrées.
* Contrôles d’accès sur les opérations sensibles.
* Protection contre les injections et les abus d’API.
* Limitation des requêtes lorsque nécessaire.
* Gestion sécurisée des erreurs.
* Journalisation sans secrets.
* Vérification des dépendances et de la configuration.

Ne désactive pas RLS pour simplifier le développement.

Ne laisse pas un utilisateur non autorisé modifier les prédictions, les résultats ou les statistiques officielles.

Documente les variables d’environnement requises sans révéler leurs valeurs secrètes.

19. API ET FOURNISSEURS DE DONNÉES

Examine les API existantes avant d’en ajouter.

Pour chaque fournisseur, documente :

* Les données fournies.
* Les limites et quotas.
* Les conditions d’utilisation.
* Les coûts éventuels.
* La fréquence de mise à jour.
* Les limites de couverture.
* La qualité et la fraîcheur des données.

N’invente pas de clé API, d’adresse d’endpoint ou de réponse fournisseur.

Ne suppose pas qu’une API prend en charge un marché si cela n’est pas confirmé.

Implémente une gestion correcte des erreurs, des délais d’expiration, des réponses incomplètes, des quotas et des indisponibilités.

20. DESIGN VISUEL : HORROR RED & BLACK PREMIUM

Je veux une identité visuelle originale, sombre, cinématographique et reconnaissable.

Le thème doit évoquer un stade nocturne inquiétant, une ambiance horrifique élégante et des prédictions mises en lumière par des effets rouges.

Palette de couleurs :

* Noir profond : #050505.
* Noir secondaire : #101010.
* Rouge sombre : #8B0000.
* Rouge principal : #D00000.
* Rouge lumineux : #FF1B1B.
* Gris foncé : #252525.
* Blanc cassé : #F2F2F2.
* Gris secondaire : #A5A5A5.

Utilise :

* Fonds de stade sombre.
* Projecteurs rouges.
* Fumée et brume subtiles.
* Particules rouges.
* Effets de lumière contrôlés.
* Motifs inspirés de coulures de peinture rouge, sans gore explicite.
* Cartes sombres aux bordures lumineuses.
* Dégradés noirs et rouges.
* Ombres profondes.
* Typographie forte, lisible et élégante.
* Animations discrètes et fluides.
* Logo personnalisé SCOREVINI AI.
* Icônes cohérentes.
* États visuels clairs pour les prédictions et les résultats.

Le design doit être premium et maîtrisé, pas enfantin, surchargé ou illisible.

Les effets horrifiques ne doivent pas compromettre la lisibilité des scores, des probabilités et des informations importantes.

21. INTERFACE UTILISATEUR ET EXPÉRIENCE

Construis une interface claire, moderne et cohérente.

La page d’accueil doit présenter l’identité ScoreVini AI et permettre d’accéder rapidement aux matchs et aux statistiques.

Les cartes de matchs doivent afficher, selon les données disponibles :

* Noms et logos des équipes.
* Compétition.
* Heure du match.
* Statut.
* Marché concerné.
* Sélection exacte.
* Probabilité estimée.
* Date de publication.
* Résultat et statut du règlement si le match est terminé.

Ne présente pas plusieurs marchés comme un seul pari.

Si un match comporte plusieurs sélections admissibles, affiche-les séparément, avec leur marché clairement indiqué.

Ajoute des filtres par marché et par statut.

Les pages doivent proposer des états vides explicites lorsqu’aucune sélection n’est disponible.

Ne simule pas de données pour rendre l’interface plus remplie.

22. LOGO ET IDENTITÉ

Crée une identité visuelle cohérente autour du nom SCOREVINI AI.

Le logo doit être lisible sur fond noir, avec une utilisation maîtrisée du rouge.

Il doit rester reconnaissable :

* Sur ordinateur.
* Sur mobile.
* Dans l’en-tête.
* Dans les menus.
* Dans une éventuelle icône d’application.

Évite de dépendre uniquement d’un texte générique ou d’un emoji pour représenter la marque.

Si une image de référence est fournie, inspire-toi de son ambiance et de sa composition sans sacrifier l’accessibilité ni la qualité du produit.

23. RESPONSIVE, ACCESSIBILITÉ ET PERFORMANCE

L’application doit fonctionner sur :

* Téléphones.
* Tablettes.
* Ordinateurs.

Exigences :

* Mise en page adaptative.
* Navigation mobile utilisable.
* Textes et probabilités lisibles.
* Contrastes suffisants.
* États de focus visibles.
* Boutons suffisamment grands.
* Animations limitées et respectueuses des préférences de mouvement.
* Chargement différé des images non essentielles.
* Réduction des requêtes inutiles.
* Mise en cache appropriée.
* Gestion des états de chargement et d’erreur.

Le design ne doit pas ralentir inutilement l’application.

24. ÉTUDE RÉTROSPECTIVE NEW YORK RED BULLS 2–0 INTER MIAMI

Prévois une étude de cas rétrospective de la rencontre New York Red Bulls 2–0 Inter Miami, à condition que la rencontre et son résultat soient vérifiés à partir de sources fiables.

Cette étude doit être réalisée comme si l’analyse était effectuée avant le coup d’envoi.

Utilise uniquement les données qui étaient disponibles avant le match :

* Forme antérieure.
* Statistiques antérieures.
* Données domicile / extérieur.
* Absences connues à cette date.
* Cotes historiques vérifiables si disponibles.
* Informations tactiques antérieures vérifiables.

Ne laisse pas le score final influencer les variables ou les probabilités pré-match.

Évalue séparément les marchés pertinents, puis compare les estimations au résultat réel.

Explique les limites de cette étude. Un seul match ne suffit pas pour démontrer la fiabilité d’un modèle.

25. TESTS AUTOMATISÉS OBLIGATOIRES

Ajoute ou améliore des tests pour les domaines suivants :

Marchés

* Chaque marché utilise sa propre méthode de calcul.
* Une victoire sélectionnée ne déclenche pas automatiquement un marché de buts.
* Les lignes extrêmes ne sont pas ajoutées artificiellement.
* Les marchés sans données suffisantes ne sont pas publiés.
* Les sélections admissibles sont indépendantes.
* Aucun combiné n’est créé automatiquement.

Seuil et probabilité

* Une sélection sous le seuil est rejetée.
* Une sélection à 80 % n’est publiée que si les autres validations sont réussies.
* Une probabilité invalide est rejetée.
* Les estimations mal calibrées ne passent pas automatiquement les contrôles.

Matchs et dates

* Absence de doublons.
* Gestion des matchs reportés.
* Fuseau Europe/Paris.
* Passage de minuit et changements d’heure.
* Résultats manquants ou contradictoires.

Règlement

* Victoire, défaite, remboursement et annulation.
* Règles spécifiques aux buts, aux mi-temps et aux handicaps.
* Prolongations et tirs au but selon les règles applicables.
* Résultat non vérifié : pas de règlement définitif.

Sécurité et fiabilité

* Autorisations Supabase.
* Politiques RLS.
* Absence de secrets dans le frontend.
* Gestion des pannes API.
* Reprise après erreur.
* Migrations et contraintes d’unicité.

Statistiques

* Exclusion des prédictions non réglées du taux de réussite.
* Séparation par marché.
* Séparation entre données réelles et simulations.
* Absence de fuite de données futures.
* Calculs vérifiables et reproductibles.

Ne déclare pas les tests réussis sans les avoir réellement exécutés. Indique ceux qui ont été exécutés, ceux qui ont échoué et ceux qui restent à effectuer.

26. OBSERVABILITÉ ET MAINTENANCE

Ajoute des journaux utiles pour :

* Les imports de matchs.
* Les appels API.
* La génération des prédictions.
* Les marchés rejetés et les raisons de rejet.
* Les publications.
* Les résultats récupérés.
* Les règlements.
* Les erreurs de calcul.
* Les tâches automatiques.
* Les problèmes de base de données.

Ne stocke pas de secrets dans les journaux.

Prévois des indicateurs de santé du système et des alertes lorsque les tâches essentielles cessent de fonctionner.

Documente les procédures de dépannage et de reprise.

27. TRANSPARENCE ET PRÉSENTATION DES PROBABILITÉS

Chaque prédiction affichée doit expliquer clairement :

* Le marché.
* La sélection.
* La probabilité estimée.
* La date et l’heure de génération.
* La version du modèle lorsque cela est pertinent.
* Les éventuelles limites des données.

Distingue :

* Probabilité estimée par le modèle.
* Probabilité implicite des cotes.
* Niveau de qualité ou de calibration vérifié.
* Résultat réel après le match.

Ne confonds pas probabilité, confiance subjective, valeur attendue et taux de réussite historique.

Ne présente pas un taux de réussite historique comme la probabilité certaine de réussite d’une future sélection.

28. RÈGLES DE DÉVELOPPEMENT ET DE LIVRAISON

Travaille progressivement et de manière vérifiable.

Pour chaque étape :

1. Explique l’objectif.
2. Identifie les fichiers concernés.
3. Décris les modifications prévues.
4. Fournis le code complet nécessaire pour les fichiers à modifier, ou des changements précisément localisés lorsque c’est plus adapté.
5. Indique les migrations Supabase éventuelles.
6. Explique les variables d’environnement nécessaires.
7. Ajoute les tests appropriés.
8. Vérifie les erreurs et la compatibilité.
9. Résume ce qui a réellement été réalisé.
10. Indique les opérations qui nécessitent mon intervention.

N’invente jamais qu’un fichier a été modifié, qu’une migration a été appliquée, qu’une API fonctionne ou qu’un déploiement a réussi si tu ne l’as pas vérifié.

Si tu ne peux pas modifier directement le dépôt, fournis des instructions précises et des modifications prêtes à appliquer.

29. MÉTHODE DE TRAVAIL AVEC GEMINI

Je travaille avec Gemini et peux devoir copier manuellement le code dans GitHub ou configurer Supabase moi-même.

Ne pars pas du principe que tu as accès à mon compte, mon dépôt, mes clés ou ma base de données.

Demande uniquement les informations nécessaires à l’étape en cours.

Ne m’envoie pas immédiatement des dizaines de fichiers non coordonnés. Organise le travail par étapes et attends que l’audit soit terminé avant de lancer des modifications importantes.

Évite les modifications qui cassent les fonctionnalités déjà opérationnelles.

30. ORDRE DE PRIORITÉ DU PROJET

Suis cet ordre de priorité :

1. Audit du projet et sauvegarde de l’existant.
2. Identification des bugs et des problèmes de sécurité.
3. Vérification de la qualité des données et des API.
4. Définition du modèle de données et des marchés.
5. Implémentation des calculs probabilistes indépendants.
6. Implémentation du seuil de publication et des validations.
7. Automatisation des matchs et des prédictions.
8. Règlement fiable des résultats.
9. Historique et statistiques par marché.
10. Tests automatisés et validation chronologique.
11. Refonte visuelle inspirée de la référence horrifique rouge et noire.
12. Optimisation mobile, performance et accessibilité.
13. Documentation et préparation du déploiement.

Tu peux ajuster cet ordre si l’audit révèle une dépendance technique indispensable, mais explique pourquoi.

31. CRITÈRES D’ACCEPTATION FINAUX

Le projet ne sera considéré comme abouti que lorsque les points applicables suivants seront vérifiés :

* Les matchs proviennent de sources réelles.
* Les données sont vérifiables et horodatées.
* Les différents marchés sont réellement pris en charge.
* Chaque marché est calculé et validé indépendamment.
* Une sélection sur un marché ne génère pas automatiquement une sélection sur un autre.
* Les lignes de buts extrêmes ne sont jamais proposées pour remplir artificiellement l’interface.
* Le seuil de publication de 80 % est appliqué sans falsifier les probabilités.
* Les marchés sont réglés avec leurs règles spécifiques.
* Les résultats sont vérifiés.
* L’historique conserve les prédictions initiales.
* Les statistiques sont calculées à partir de données réelles.
* Les données futures ne contaminent pas l’analyse pré-match.
* Les tâches automatiques sont vérifiables.
* Supabase est configuré de manière sécurisée.
* Les secrets ne sont pas exposés.
* Les tests critiques ont été exécutés.
* L’interface adopte le style noir et rouge demandé.
* Les pages sont lisibles sur mobile et ordinateur.
* Les erreurs et les données manquantes sont gérées correctement.

Toute fonctionnalité non vérifiée doit être signalée comme telle.

32. PREMIÈRE ACTION À EFFECTUER MAINTENANT

Ne commence pas immédiatement à réécrire le code.

Commence par :

1. Auditer le projet existant à partir des fichiers et informations réellement accessibles.
2. Présenter l’architecture actuelle et les principales lacunes.
3. Vérifier comment les matchs, les prédictions et les résultats sont actuellement gérés.
4. Déterminer comment introduire les marchés indépendants sans casser l’existant.
5. Identifier les modifications nécessaires dans Supabase, le backend, les API et l’interface.
6. Présenter un plan de développement par étapes, avec les risques et les tests à prévoir.

Ensuite, commence uniquement par la première étape de développement, après avoir expliqué les changements proposés.

Rappel final : ScoreVini AI doit être une application réellement fonctionnelle, fondée sur des données vérifiables, avec une analyse probabiliste rigoureuse et des marchés de paris totalement séparés. Le design doit être premium, horrifique, rouge et noir, mais jamais au détriment de la lisibilité, de la sécurité ou de la fiabilité. Voilà, je t'ai envoyé l'image de référence du site comment il doit être et je t'ai envoyé mon prompt de A à Z que je dois mettre. Dis-moi étape par étape comment je fais pour le mettre.
