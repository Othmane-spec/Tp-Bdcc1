# TP : IA Agentique 🤖
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/Othmane-spec/Tp-Bdcc1)

## 📝 Description
Ce projet s'inscrit dans le cadre du module **BDCC1**. L'objectif de ce TP est d'explorer et de mettre en œuvre des concepts d'**IA Agentique**, en développant des agents capables de raisonner, d'utiliser des outils et d'interagir de manière autonome pour résoudre des tâches complexes.

## 🎯 Objectifs du TP
- Comprendre le fonctionnement des agents LLM (Large Language Models).
- Implémenter des boucles de raisonnement (ex: ReAct, Chain-of-Thought).
- Intégrer des outils externes (API, recherche web, exécution de code).
- Gérer la mémoire et l'état d'un agent sur plusieurs étapes.

## 🛠️ Stack Technique
- **Langage :** Python 3.14+
- **Gestionnaire de paquets :** `uv`
- **Bibliothèques Clés :**
    - `tiktoken` pour la tokenisation optimisée pour les modèles OpenAI.
    - `ipykernel` pour le support des notebooks Jupyter.

## 🚀 Installation et Lancement

### 1. Prérequis
Assurez-vous d'avoir `uv` installé sur votre machine.

### 2. Installation du projet
Clonez le dépôt et naviguez dans le répertoire :
```bash
git clone https://github.com/othmane-spec/tp-bdcc1.git
cd tp-bdcc1
```

### 3. Configuration de l'environnement
Créez un environnement virtuel, activez-le, et installez les dépendances du projet en une seule fois.
```bash
# Initialiser l'environnement virtuel
uv venv

# Activer l'environnement
# Sur macOS/Linux :
source .venv/bin/activate
# Sur Windows :
.venv\Scripts\activate

# Synchroniser les dépendances
uv sync
```

## 🧑‍💻 Utilisation
Ce dépôt contient les éléments suivants pour démarrer :

- **`main.py`** : Un script simple pour vérifier que votre environnement est correctement configuré. Exécutez-le avec `python main.py`.
- **`prompt.ipynb`** : Un notebook Jupyter qui fournit un exemple concret d'utilisation de `tiktoken` pour encoder un *system message* pour le modèle `gpt-4o`. C'est un excellent point de départ pour comprendre la préparation des prompts avant leur envoi à une API de modèle de langage.
- **`pyproject.toml`** : Le fichier de configuration du projet qui définit ses métadonnées et ses dépendances directes.