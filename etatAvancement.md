# État d’avancement de l’enquête  
**Usages du numérique dans la recherche de logement des étudiants et jeunes actifs en Seine-Saint-Denis**

Ce document présente l’état d’avancement de l’enquête menée dans le cadre du projet DMA4EDD2.  
L’enquête combine un questionnaire et des entretiens qualitatifs pour comprendre les usages du numérique dans la recherche de logement.

---

## Diagramme de Gantt de l’enquête

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       État d’avancement de l'enquête DMA4EDD2
    excludes    weekends

    section Questionnaire
    Élaboration du questionnaire             :done, q1, 2025-01-05, 15d
    Diffusion (résidence, Facebook, WhatsApp):active, q2, after q1, 21d
    Distribution photocopies à connaissances :active, q3, after q2, 5d
    Saisie sur LimeSurvey                     :todo, q4, after q3, 10d

    section Entretiens
    Premiers entretiens étudiants            :active, e1, 2025-01-22, 20d
    Entretiens programmés jeunes actifs      :todo, e2, after e1, 25d
    Entretiens supplémentaires résidence     :todo, e3, after e2, 15d
    Enregistrements audio/vidéo              :todo, e4, after e3, 15d

    section Analyse
    Analyse préliminaire questionnaire       :todo, a1, after q4, 15d
    Analyse des entretiens et verbatims      :todo, a2, after e4, 15d
    Croisement des données                   :todo, a3, after a2, 7d
    Rédaction de la synthèse finale          :todo, a4, after a3, 10d

    section Clôture
    Fin de l’enquête                          :milestone, end, after a4, 0d
