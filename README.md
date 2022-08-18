# No Show Appointment
Dans ce projet, nous analyserons les données concernant des rendez-vous de patients dans des centres hospitaliers au Brésil.

Chaque observation (ou ligne) nous donne les détails sur un rendez-vous en particulier. Pour chaque rendez-vous, des atributs spécifiques sont répertoriés.

Le projet a été réalisé sur jupyter notebook. Les librairies utilisées sont:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Le but étant de comprendre les facteurs contribuant au fait que des patients manquent leur rendez-vous à l'hopital.

Après l'exploration et la visualisation des données précédentes, les observations suivantes ont été faites.

### Par rapport à l'âge des patients:

Les groupes de patients de 10-20 ans et 20-30 ans sont ceux avec les plus grandes proportions de rendez-vous manqués avec:

10-20 ans: 25.3% de rendez-vous manqués
20-30 ans: 24.6% de rendez-vous manqués
### En ce qui concerne les localisations des hopitaux:

Les 5 localisations avec le plus grand pourcentage de rendez-vous manqués sont:

SANTOS DUMONT: 28.9% de rdv manqués
SANTA CECÍLIA : 27.5%
SANTA CLARA: 26.5%
ITARARÉ: 26.3%
JESUS DE NAZARETH: 24.4%
### Par rapport aux jours de la semaine:
La journée du samedi est celle avec le plus grand pourcentage de rendez-vous manqués (23%). Mais les autres jours ont des pourcentages qui ne sont pas vraiment éloignés. Comme par exemple vendredi (21%) et lundi (20%).

### Par rapport aux heures de la semaine:

On observe un pic en terme de pourcentage de rendez-vous manqués pour ceux de 20h et 21h (30 et 33% respectivement)
Les plus faibles pourcentages de rendez-vous manqués concernent les heures très matinales (entre 6h et 9h)
Concernant les messages reçus par les patients:

Il se pourrait que les messages aient un impact sur le fait de se présenter ou pas au rendez-vous. En effet, ceux qui viennent au rendez-vous sans messages représentent un plus grand pourcentage que ce qui viennent au rendez-vous avec messages (83% contre 72%). Il s'agit d'une observation, qui nécessitera des investigations futures.

Pour tirer des conclusions, il sera question d'effectuer des tests statistiques. Ceci fera certainement l'objet d'un prochain rapport.