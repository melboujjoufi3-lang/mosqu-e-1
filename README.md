# Schéma des acteurs – Permis d’urbanisme (Bruxelles)

```mermaid
%%{init: {'flowchart': {'useMaxWidth': false}, 'theme': 'default'}}%%
flowchart TD
    A["Centre Culturel d’Averroes Jettois ASBL<br/>(Demandeur)"] -->|Soumet via MyPermit| M["MyPermit<br/>(Plateforme numérique)"]
    M -->|Transmet, ARC en 45 jours| B["Urban.brussels<br/>(Service Public Régional)"]
    B -->|Coordonne, transmet| C["Fonctionnaire délégué<br/>(Décision en 160 jours max après ARC)"]
    B -->|Organise enquête publique<br/>(15-30 jours)| D["Commune de Jette<br/>(CBE, avis en 45 jours post-enquête)"]
    B -->|Demande d'avis| E["Commission de Concertation<br/>(Avis après enquête)"]
    B -->|Avis obligatoire<br/>(30 jours)| F["SIAMU<br/>(Service d’Incendie)"]
    B -->|Avis consultatifs<br/>(30-45 jours)| G["Autres instances"]
    G --> H["Service de Sécurité ASTRID<br/>(Avis en 30-45 jours)"]
    G --> I["VIVAQUA<br/>(Avis en 30-45 jours)"]
    G --> J["AccessAndGo<br/>(Avis en 30-45 jours)"]
    G --> K["CRMS<br/>(Avis en 30-45 jours)"]
    D -->|Avis| C
    D -->|Collecte observations<br/>(15-30 jours)| L["Participants à l’enquête publique"]
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


