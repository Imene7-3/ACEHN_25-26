```mermaid
gantt
    title Etat d'avancement de l'enquete DMA4EDD2
    dateFormat  YYYY-MM-DD

    section Travaux preliminaires
    Lecture protocole et choix reference       :done, t1, 2025-10-16, 1d
    Activite 5W+1 reflexion problemes         :done, t2, 2025-10-16, 2d
    Recherche documentaire initiale           :done, t3, 2025-10-16, 5d
    Prise de note collaborative               :done, t4, 2025-10-20, 3d
    Identification du terrain                 :done, t5, 2025-10-25, 5d
    Journal de bord structure                 :done, t6, 2025-11-06, 1d

    section Questionnaire
    Elaboration questionnaire                 :done, q1, 2025-11-06, 10d
    Diffusion questionnaire residence_FB_WA   :active, q2, after q1, 7d
    Distribution photocopies                   :done, q3, after q2, 3d
    Saisie sur LimeSurvey                       :todo, q4, after q2, 10d

    section Entretiens
    Premiers entretiens etudiants             :done, e1, after q2, 5d
    Entretiens jeunes actifs                   :todo, e2, after e1, 7d
    Entretiens supplementaires residence      :todo, e3, after e2, 10d
    Enregistrements audio_video                :todo, e4, after e3, 5d
    Temoignage personnel                        :todo, e5, after e4, 5d

    section Analyse
    Analyse preliminaire questionnaire        :todo, a1, after q4, 5d
    Analyse entretiens et verbatims           :todo, a2, after e5, 7d
    Croisement des donnees                     :todo, a3, after a2, 3d
    Redaction synthese finale                  :todo, a4, after a3, 5d

    section Cloture
    Fin de l'enquete                           :2025-02-28, 0d
