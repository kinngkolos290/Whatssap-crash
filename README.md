<p align="center">
  <img src="https://files.catbox.moe/j645mk.jpeg" width="200" alt="Logo du projet">
</p>

<h1 align="center">📛 WhatsApp Crash Tool</h1>

<p align="center">
  <b>À des fins éducatives uniquement.</b><br>
  L'utilisation abusive de cet outil peut enfreindre les conditions d'utilisation de WhatsApp.<br>
  Le développeur décline toute responsabilité en cas de mauvaise utilisation.
</p>

---

## 📌 Description

Ce projet démontre comment une séquence spécifique de caractères peut provoquer le crash de l'application WhatsApp sur certains appareils. Il est destiné à des fins de recherche et d'apprentissage sur les vulnérabilités des applications de messagerie.

## 🚀 Fonctionnalités

- Génération de messages contenant des séquences spéciales provoquant des crashs.
- Interface en ligne de commande simple.
- Compatible avec Termux et les distributions Linux.

## 🛠️ Installation

```bash
pkg update && pkg upgrade -y
pkg install git python -y
git clone https://github.com/kinngkolos290/Whatssap-crash.git
cd Whatssap-crash
pip install -r requirements.txt
```

## ⚙️ Utilisation

```bash
python3 crash.py
```

Suivez les instructions à l'écran pour générer et envoyer le message crashant.

## 📷 Exemple

```bash
$ python3 crash.py
Entrez le numéro de téléphone du destinataire : +509XXXXXXXX
Message crash généré et prêt à être envoyé.
```

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.

## 🤝 Contribuer

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.

---

**Note :** Ce projet est destiné à des fins éducatives et de recherche uniquement. L'utilisation de cet outil pour perturber ou endommager les services d'autrui est strictement interdite.