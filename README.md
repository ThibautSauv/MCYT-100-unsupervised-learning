# MCYT-100-unsupervised-learning

Ce projet est un projet de cours portant sur l'apprentissage non-supervisé dans le cadre du cursus ingénieur de Télécom SudParis. </br>
**Pour des raisons de confidentialité et de protection des données, les données utilisées dans ce projet ne sont pas fournies et leur tracé n'est pas affiché.**

Cette étude de cas concerne l’analyse d’une base de données de signatures manuscrites dites « en-ligne », acquises sur un dispositif numérique (tablette graphique). Ainsi, on peut étudier la dynamique du geste produit lors de la signature. La base de données utilisée est MCYT-100. Elle contient 100 sujets ayant chacun réalisé 25 signatures de référence. Ajoutées à ces signatures, nous est fourni la complexité des 2500 signatures (25 signatures authentiques des 100 personnes) qui a été calculée avec le modèle GMM couplé à la mesure d’entropie différentielle, et cela pour différents nombres de gaussiennes : $n \in {4,8,16}$

À terme, cette analyse permettra de faire de la classification de signature avec un traitement non-supervisé afin de détecter si une nouvelle signature appartient bien à son propriétaire ou si c’est une fraude.
