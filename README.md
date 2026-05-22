# Analyse comparative du risque : Actions vs Cryptomonnaies

> **Les cryptomonnaies sont-elles réellement plus risquées que les actifs traditionnels ?**  
> Cette étude applique plusieurs outils de finance quantitative et de gestion des risques afin de comparer le comportement des actions et des cryptomonnaies.

---

## 🎯 Objectifs

- Comparer empiriquement le profil de risque des actions et des cryptomonnaies
- Étudier les distributions de rendements et les événements extrêmes
- Implémenter plusieurs mesures de risque :
  - Volatilité
  - Value-at-Risk (VaR)
  - Expected Shortfall (ES)
- Analyser les corrélations entre actifs
- Étudier l’impact des cryptomonnaies dans un portefeuille diversifié

---

## 📈 Résultats clés

✅ **Volatilité** : Les cryptomonnaies présentent une volatilité largement supérieure aux actifs actions traditionnels  

✅ **Risque extrême** : VaR et Expected Shortfall montrent des pertes potentielles beaucoup plus importantes sur Bitcoin et Ethereum  

✅ **Distributions non gaussiennes** : Les rendements crypto présentent des queues épaisses et des événements extrêmes plus fréquents qu’une loi normale classique  

✅ **Corrélations** : Les cryptomonnaies restent partiellement corrélées aux marchés traditionnels mais conservent un certain potentiel de diversification  

✅ **Portefeuille** : Une exposition modérée aux cryptomonnaies augmente le rendement moyen du portefeuille tout en conservant un effet de diversification partiel  

---

## 🛠️ Stack technique

- **Python**
- **pandas**
- **numpy**
- **matplotlib**
- **scipy**
- **yfinance**

---

## 📊 Visualisations clés

### 1. Évolution normalisée des actifs (base 100)

![Évolution normalisée](normalized_prices.png)

---

### 2. Distributions des rendements et approximations gaussiennes

#### Actions

![Distributions actions](stock_distributions.png)

#### Cryptomonnaies

![Distributions cryptos](crypto_distributions.png)

> Observation : les distributions présentent des queues épaisses, particulièrement sur les cryptomonnaies, ce qui limite la pertinence de l’hypothèse gaussienne.

---

### 3. Matrice de corrélation

![Matrice de corrélation](correlation_matrix.png)

> Les cryptomonnaies restent positivement corrélées aux marchés actions, mais avec une intensité plus faible que les corrélations observées entre actions traditionnelles.

---

## 📚 Ce que ce projet met en évidence

- Les cryptomonnaies présentent un niveau de risque significativement supérieur aux actifs actions traditionnels
- Les distributions de rendements financiers s’écartent souvent d’une loi normale classique, en particulier sur les actifs très volatils
- Les mesures de risque extrême comme la Value-at-Risk et l’Expected Shortfall sont essentielles pour analyser les événements rares mais sévères
- Les corrélations entre actifs jouent un rôle central dans la diversification d’un portefeuille
- Un actif risqué peut malgré tout contribuer à la diversification lorsqu’il est intégré de manière contrôlée

---

## 👤 Auteur

**Nadim Coindet**  
Master 1 Mathématiques — Sorbonne Université  
Projet personnel en finance quantitative et gestion des risques
