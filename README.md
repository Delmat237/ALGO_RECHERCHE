
# Dijkstra, A* & Alpha-Bêta Visualizer

Ce projet est un simulateur interactif de graphes développé pour aider à la compréhension des algorithmes de recherche de chemin et d'élagage. Il permet de construire visuellement un graphe, d'assigner des poids et des heuristiques, et d'observer l'exécution pas à pas.

## 🚀 Fonctionnalités

### 1. Gestion du Graphe
* **Sommets** : Créez des sommets par simple clic. Modifiez le nom et l'heuristique ($h$) via un double-clic.
* **Arêtes** : Reliez les sommets en définissant un poids. Les arêtes de poids 0 ne voient pas leur étiquette affichée pour alléger le rendu visuel.
* **Manipulation** : Déplacez les sommets par glisser-déposer ou ajustez la vue avec le zoom (molette) et le déplacement du canvas (clic droit).

### 2. Algorithmes Supportés
* **Dijkstra** : Trouve le chemin le plus court en se basant sur le coût réel ($g$).
* **A* (A-Star)** : Utilise une heuristique pour guider la recherche ($f = g + h$).
* **Alpha-Bêta Pruning** : Permet de visualiser les valeurs $\alpha$, $\beta$ et $V$ pour les arbres de décision. La police des valeurs $\alpha$ et $\beta$ a été agrandie pour une meilleure lisibilité lors des démonstrations.

### 3. Contrôle de la Simulation
* **Exécution Pas à Pas** : Boutons "Suivant" et "Retour" pour naviguer dans l'historique des états de l'algorithme.
* **Console de Log** : Suivez les détails techniques (relâchement d'arêtes, nœuds visités) en temps réel.

## 🛠️ Installation

1.  Téléchargez le fichier `ALGO_RECH.html`.
2.  Ouvrez-le simplement dans un navigateur web moderne (Chrome, Firefox, Edge).
3.  Aucune installation de serveur n'est requise (fonctionne en local via CDN p5.js et Lucide).

## 📝 Mode d'emploi (Alpha-Bêta)
1.  Sélectionnez **Alpha-Bêta Pruning** dans le menu déroulant.
2.  Double-cliquez sur un nœud pour saisir manuellement les valeurs $\alpha$, $\beta$ ou la valeur finale $V$.
3.  Les valeurs s'afficheront dynamiquement au-dessus et en dessous du sommet avec une police optimisée.

## 🎓 Contexte
Ce projet a été optimisé pour les besoins académiques de l'**ENSPY** (École Nationale Supérieure Polytechnique de Yaoundé), particulièrement pour les modules de Génie Informatique.

*** *Développé avec p5.js*.
