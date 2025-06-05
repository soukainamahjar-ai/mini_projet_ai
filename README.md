#  Projet : Bras Robotique pour Empilage de Cubes Colorés (Unity + ML-Agents)

##  Objectif
Créer un agent intelligent capable de contrôler un bras robotique dans Unity pour empiler des cubes selon leur couleur à l’aide de l’algorithme PPO de ML-Agents.

##  Outils et Technologies
- Unity 2021.3.XX
- ML-Agents Toolkit (vX.X.X)
- C#

##  Algorithme utilisé
- **PPO (Proximal Policy Optimization)** via ML-Agents.
- L’agent observe la position des cubes via une caméra montée sur le bras.

##  Architecture
- `Assets/Scenes/`: Contient la scène avec le bras et les cubes.
- `Assets/Scripts/`: Scripts pour le contrôle du bras.
- `config/`: Fichier YAML de configuration pour PPO.
- `models/`: Sauvegarde du modèle entraîné (non fonctionnel pour l’instant).

## L' État actuel du projet
 Le projet n’est **pas encore fonctionnel**.

###  Réalisé :
- Environnement Unity avec bras et cubes
- Script de l’agent ML-Agents
- Début de la configuration du modèle PPO

###  Non fonctionnel :
- L’agent ne parvient pas à détecter les cubes
- Aucun comportement d’empilage appris malgré entraînement

##  Captures d'écran
> *(Ajouter ici une image de l’environnement dans Unity)*


##  Prochaines étapes
- Corriger les observations
- Affiner les récompenses pour motiver le comportement d’empilage

##  Remarque
Même si l’agent ne fonctionne pas encore, ce projet a permis de mieux comprendre :
- L'intégration de ML-Agents dans Unity
- La modélisation d’un bras robotique
- Les étapes de configuration d’un entraînement par renforcement



