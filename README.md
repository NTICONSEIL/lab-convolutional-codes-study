# lab-convolutional-codes-study
📡 R&amp;D : Étude et implémentation d'algorithmes de codage et décodage convolutif (Viterbi) pour la fiabilisation des transmissions numériques.

# 📡 Étude des Codes Convolutifs & Algorithme de Viterbi

> **Pôle : NTI Lab** | Axe : Communications Numériques & Signaux

Ce projet de recherche explore l'efficacité des codes correcteurs d'erreurs dans des environnements de transmission bruités (AWGN).

## 🔬 Objectifs du Lab
* Implémentation d'encodeurs convolutifs (Constraint Length K=7, Rate 1/2).
* Développement d'un décodeur de Viterbi (Hard & Soft decision).
* Analyse du Taux d'Erreur Binaire (BER) en fonction du rapport Signal/Bruit (Eb/N0).

## 🎓 Opportunités pour les Étudiants
Nous proposons d'étendre ces travaux sur les thématiques suivantes :
1. **Poinçonnage (Puncturing)** : Optimisation du débit binaire.
2. **Turbo-Codes** : Étude comparative avec les codes convolutifs classiques.
3. **Optimisation C/C++** : Implémentation temps-réel pour processeurs DSP.

## 📑 Fondements Théoriques

L'objectif de ce projet est l'étude des codes convolutifs de rendement $R = k/n$. Un codeur convolutif transforme une séquence d'entrée d'information en une séquence codée en utilisant des registres à décalage.

### 1. Polynômes Générateurs
Le codeur est défini par ses polynômes générateurs $G_i(D)$. Pour un code de rendement $R=1/2$, la sortie est le résultat de la convolution de l'entrée avec ces polynômes :

$$y^{(1)} = x * g^{(1)} \quad \text{et} \quad y^{(2)} = x * g^{(2)}$$

Dans le domaine de la transformée en $D$ (Delay operator), cela s'exprime par :
$$Y_i(D) = X(D) \cdot G_i(D)$$

### 2. Algorithme de Viterbi (Décodage)
Le décodage repose sur la recherche du chemin de distance de Hamming minimale dans le treillis du code (Maximum Likelihood Decoding). La métrique de branche $\mu$ à l'instant $t$ pour un état donné est calculée par :

$$\mu_t = \sum_{i=1}^{n} |y_{t,i} - \hat{y}_{t,i}|^2$$

L'objectif du lab est d'optimiser la survie des chemins dans le treillis pour minimiser le **BER** (Bit Error Rate) en fonction du rapport signal sur bruit :
$$\frac{E_b}{N_0} \text{ (en dB)}$$

---

## 🚀 Rejoindre la recherche au NTI Lab
Nous proposons des sujets d'expérimentation concrets pour les étudiants en Master et Écoles d'Ingénieurs. 

> [!TIP]
> **Sujets disponibles :** Optimisation C++, Décodage par IA, Simulation de canaux bruités.
> 
> 👉 [Consulter la liste détaillée des missions de recherche](./docs/SUJETS_DE_RECHERCHE.md)
