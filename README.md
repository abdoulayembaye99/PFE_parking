# 🚗 Opti'Flux - Détection de Places Libres de Parking

Bienvenue dans **Opti'Flux**, un projet de fin d'études (PFE) dédié à la détection automatique de places de parking libres à l'aide d'un modèle YOLO.

## 📌 Présentation

Ce projet vise à faciliter la gestion du stationnement en détectant en temps réel les places libres à partir de vidéos. Pour cela, nous utilisons un modèle d'intelligence artificielle entraîné sur des images annotées.

## 📁 Structure du Projet

```
📂 Opti'Flux
│-- trainyolo11n.py               # Entraînement du modèle YOLO
│-- extraction_frame.py           # Extraction des frames depuis une vidéo test
│-- inférence.py                  # Exécution du modèle sur une vidéo test
│-- log_config.py                 # Configuration des logs d'inférence
│-- transformation_annotation/    # Scripts pour créer ou modifier les annotations des frames
│-- yolo11nano/                   # Modèle YOLO pré-entraîné
```

    
## 🚀 Installation

1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/ton_repo/OptiFlux.git
   cd OptiFlux
   ```
2. **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Logs

Les logs générés par **log\_config.py** permettent de suivre les performances du modèle en temps réel.

## ✏️ Annotations

Le dossier **transformation\_annotation/** contient les scripts nécessaires à la création et transformation des annotations des images utilisées pour l'entraînement du modèle.

##############################################

📂 PARK-BOOKING-MAIN (Opti'Flux Application)
.bolt
hooks
node_modules
│-- src
  │-- assets
  │-- map.html
  │-- parkingData.json
│-- components
  │-- HomeScreen.tsx          # Composant principal affichant la vue d'ensemble des parkings
  │-- MainStack.tsx           # Main
  │-- MapScreen.tsx           # Écran affichant la carte interactive des parkings.
  │-- ZoneDetailsScreen.tsx   # Écran détaillé pour une zone de parking spécifique
│-- app.css
│-- app.ts
│-- NavigationParamList.ts
...

## 🚀 Installation

1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/ton_repo/OptiFlux.git
   park-booking-main > cd .\park-booking-main\
   ```
2. **Installer les dépendances**
   ```bash
   npm install
   npm install -g expo-cli
   ```

3. **Visualisation de l'application**
   ```bash
   installation nativeScript sur téléphone puis scanner code QR sur visual studio
   ```

## 👥 Équipe

Projet développé par **Opti'Flux**, un groupe d'ingénieurs passionnés par l'IA et la vision par ordinateur.

---

💡 **Idée d'amélioration future** :

- Ajouter une interface web pour visualiser les résultats en direct !
- Envoyer automatiquement les fichiers JSON créés via l'inférence à l'application Opti'Flux.

📧 Pour toute question ou suggestion, n'hésitez pas à nous contacter :
- **pfeoptiflux@gmail.com** 🚀

