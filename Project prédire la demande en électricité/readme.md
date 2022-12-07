# Mise en situation
Vous êtes employé chez Enercoop, société coopérative qui s'est développée grâce à la libéralisation du marché de l’électricité en France. Elle est spécialisée dans les énergies renouvelables.

La plupart de ces énergies renouvelables est cependant intermittente, il est donc difficile de prévoir les capacités de production d'électricité. De plus, la demande en électricité des utilisateurs varie au cours du temps, et dépend de paramètres comme la météo (température, luminosité, etc.) Tout le challenge est de mettre en adéquation l'offre et la demande !

# Les données
Voici [les données](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DAN_V1_P9/data_conso.zip). Ce sont les données journalières et non mensuelles, donc vous les devrez recompiler en données mensuelles.

Pour les plus curieux et les plus motivés, [voici les données sources](https://www.rte-france.com/eco2mix/telecharger-les-indicateurs). Libre à vous de recompiler les données par vous même pour arriver aux données journalières. Attention toutefois, c’est un travail très formateur mais relativement long et complexe. Votre mentor dispose d’un notebook qu’il pourra mettre à votre disposition si besoin.

Voici également les [données météo](https://cegibat.grdf.fr/simulateur/calcul-dju) que vous utiliserez pour corriger les données de l'effet température.

# Votre mission
Vous vous concentrerez uniquement sur la prédiction de la demande en électricité.

1. Corrigez les données de consommation mensuelles de l'effet température (dues au chauffage électrique) en utilisant une régression linéaire.

2. Effectuez une désaisonnalisation de la consommation que vous aurez obtenue après correction, grâce aux moyennes mobiles.
3. Effectuez une prévision de la consommation (corrigée de l'effet température) sur un an, en utilisant la méthode de Holt Winters (lissage exponentiel) puis la méthode SARIMA sur la série temporelle.

Pour chaque traitement effectué (correction de l'effet température, désaisonnalisation, etc.), vous présenterez les 2 séries temporelles avant et après traitement, sur un graphique où les deux séries temporelles seront superposées
