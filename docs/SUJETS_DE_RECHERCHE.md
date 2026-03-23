# 🔬 Sujets de Recherche & Missions : Codes Convolutifs
> **Pôle :** NTI Lab  
> **Axe :** Communications Numériques & Analyse de Signaux

Bienvenue dans l'espace d'expérimentation du **NTI Lab**. Nous proposons aux étudiants (Master, École d'Ingénieurs) des missions concrètes pour explorer la fiabilité des transmissions de données.

---

## 🟢 Niveau Initial : Simulation & Analyse Fondamentale
*Objectif : Comprendre l'impact du bruit sur la transmission.*

### Mission A : Analyse du Taux d'Erreur Binaire (BER)
* **Description :** Implémenter une chaîne de transmission complète en Python ou MATLAB.
* **Livrables :** Script de simulation et tracé de la courbe du BER en fonction du rapport $E_b/N_0$ sur canal AWGN.
* **Compétences :** Python (NumPy/Matplotlib), Théorie de l'information.

### Mission B : Comparaison Hard vs Soft Decision
* **Description :** Modifier le décodeur de Viterbi pour accepter des entrées quantifiées (Soft Decision).
* **Livrables :** Étude comparative montrant le gain de codage (en dB) apporté par la décision souple.
* **Compétences :** Traitement du signal, Algorithmique.

---

## 🟡 Niveau Intermédiaire : Optimisation & Performance
*Objectif : Rendre les algorithmes utilisables dans des systèmes réels.*

### Mission C : Optimisation du Treillis de Viterbi en C++
* **Description :** Développer une implémentation C++ optimisée pour réduire la consommation CPU lors du parcours du treillis.
* **Livrables :** Code source documenté et benchmark de performance (temps de traitement par bit).
* **Compétences :** C++, Structure de données, Complexité algorithmique.

### Mission D : Implémentation du Poinçonnage (Puncturing)
* **Description :** Ajouter un module permettant de modifier dynamiquement le rendement du code (ex: passer de 1/2 à 3/4).
* **Livrables :** Module de poinçonnage/dépontage et analyse de la dégradation de performance vs gain de débit.
* **Compétences :** Télécoms, Codage de canal.

---

## 🔴 Niveau Avancé : Innovation & IA (Expert)
*Objectif : Explorer les technologies de rupture.*

### Mission E : Décodage par Réseaux de Neurones (Deep Learning)
* **Description :** Remplacer le décodeur classique par un modèle RNN ou GRU entraîné à corriger les erreurs.
* **Livrables :** Modèle entraîné et comparaison des performances face à l'algorithme de Viterbi traditionnel.
* **Compétences :** Deep Learning (PyTorch/TensorFlow), IA appliquée au signal.

### Mission F : Robustesse en milieu mobile (Canal de Rayleigh)
* **Description :** Simuler une transmission en environnement urbain (Fading) et implémenter un entrelaceur (Interleaver).
* **Livrables :** Rapport d'expérimentation sur la lutte contre les paquets d'erreurs (Burst errors).
* **Compétences :** Modélisation de canaux radio, Statistiques.

---

## 📩 Comment postuler ou contribuer ?
Si l'un de ces sujets vous intéresse dans le cadre d'un stage, d'un projet tutoré ou d'une contribution libre :
1.  **Forkez** le dépôt.
2.  Créez une **Issue** pour annoncer le sujet sur lequel vous travaillez.
3.  Soumettez vos résultats via une **Pull Request**.

> *Le NTI Lab encourage l'expérimentation audacieuse et le partage de connaissances.*
