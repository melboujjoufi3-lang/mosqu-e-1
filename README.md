graph TD
    A[Centre Culturel d’Averroes Jettois ASBL<br>(Demandeur)] -->|Introduit la demande via| M[MyPermit<br>(Plateforme en ligne)]
    M -->|Transmet| B[Urban.brussels<br>(Service Public Régional)]
    B -->|Coordonne et transmet| C[Fonctionnaire délégué]
    B -->|Organise l'enquête publique| D[Commune de Jette<br>(Collège des Bourgmestre et Échevins)]
    B -->|Demande d'avis| E[Commission de Concertation]
    B -->|Demande d'avis obligatoire| F[SIAMU<br>(Service d’Incendie)]
    B -->|Demande d'avis techniques| G[Autres instances]
    G --> H[Service de Sécurité ASTRID]
    G --> I[VIVAQUA<br>(Eau/Assainissement)]
    G --> J[AccessAndGo<br>(Accessibilité PMR)]
    G --> K[CRMS<br>(Patrimoine)]
    D -->|Avis| C
    D -->|Observations| L[Participants à l’enquête publique]
    E -->|Avis consultatif| C
    F -->|Avis obligatoire| C
    H -->|Avis| C
    I -->|Avis| C
    J -->|Avis| C
    K -->|Avis| C
    L -->|Observations| E
    C -->|Décision finale| A

    classDef acteur fill:#f9f,stroke:#333,stroke-width:2px;
    class A,B,C,D,E,F,G,H,I,J,K,L,M acteur;

Légende

Centre Culturel d’Averroes Jettois ASBL : Soumet la demande via MyPermit et exécute les travaux après approbation.
MyPermit (Plateforme en ligne) : Interface numérique utilisée par le demandeur pour soumettre la demande et par Urban.brussels pour gérer le dossier.
Urban.brussels : Coordonne le processus administratif, reçoit la demande via MyPermit, et relaie au fonctionnaire délégué.
Fonctionnaire délégué : Décide de l’octroi ou du refus du permis après réception des avis.
Commune de Jette : Organise l’enquête publique et donne un avis via le Collège des Bourgmestre et Échevins.
Commission de Concertation : Évalue le projet et émet un avis consultatif.
SIAMU : Vérifie la sécurité incendie (avis obligatoire).
Service de Sécurité ASTRID : Fournit un avis sur la sécurité, si pertinent.
VIVAQUA : Évalue les aspects eau/assainissement.
AccessAndGo : Vérifie l’accessibilité pour les personnes à mobilité réduite.
CRMS : Évalue les impacts patrimoniaux, si applicable.
Participants à l’enquête publique : Soumettent des observations influençant l’avis de la Commission de Concertation.

