# ASL-Sign-Language-Recognition
# 🤟 Sign Language Recognition – MNIST

Ce projet implémente un modèle de **Deep Learning** pour la reconnaissance des lettres du langage des signes (ASL)
à partir du dataset **Sign Language MNIST**, en utilisant **TensorFlow / Keras**.

---

## 🎯 Objectif du projet

- Charger et préparer le dataset Sign Language MNIST
- Entraîner un modèle de classification multi-classes
- Reconnaître automatiquement les lettres du langage des signes
- Évaluer les performances du modèle

---

## 🧠 Dataset

- **Sign Language MNIST**
- Images en niveaux de gris de taille **28×28**
- 25 classes (lettres A–Z sauf J)
- Format CSV :
  - `sign_mnist_train.csv`
  - `sign_mnist_test.csv`

Chaque image est aplatie en un vecteur de **784 pixels**.

---

## 🛠️ Technologies utilisées

- Python 3
- NumPy
- Pandas
- TensorFlow / Keras
- Jupyter Notebook / Google Colab

---

## ⚙️ Installation & exécution

### 🔹 Option recommandée : Google Colab
Aucune installation requise.

1. Ouvrir https://colab.research.google.com
2. Créer un nouveau notebook
3. Importer les fichiers :
   - `sign_mnist_train.csv`
   - `sign_mnist_test.csv`
4. Exécuter le notebook

### 🔹 Installation locale
```bash
pip install numpy pandas tensorflow
