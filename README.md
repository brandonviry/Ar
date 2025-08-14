# 🎯 AR.js Web - Réalité Augmentée dans le Navigateur

[![Demo](https://img.shields.io/badge/Demo-Live-brightgreen)](https://ar-flax.vercel.app/)
[![Status](https://img.shields.io/badge/Status-Active-success)](https://ar-flax.vercel.app/)
[![Year](https://img.shields.io/badge/Created-2020-blue)]()
[![Updated](https://img.shields.io/badge/Updated-2024-orange)]()

## 🌐 Démo en ligne

**➡️ [https://ar-flax.vercel.app/](https://ar-flax.vercel.app/)**

## 👨‍💻 Auteur

**VIYR Brandon**
- Projet créé en 2020
- Mis à jour en 2024 pour mon portfolio

## 📝 Description

Application web de réalité augmentée utilisant AR.js et A-Frame. Permet d'afficher des objets 3D interactifs dans le monde réel via la caméra du navigateur, sans installation d'application.

## ✨ Fonctionnalités

- 🎮 **Réalité augmentée directement dans le navigateur**
- 📱 **Compatible mobile et desktop**
- 🎯 **Utilise le marqueur Hiro (standard AR.js)**
- 🎨 **Plusieurs démos d'objets 3D animés**
- ⚡ **Aucune installation requise**

## 🚀 Démos disponibles

### ✅ Démos fonctionnelles
- **Boîte Transparente** - Cube jaune semi-transparent
- **Test Debug** - Grande boîte rouge avec texte
- **Test Alternative** - Version alternative d'AR.js
- **Multi-Boîtes** - Plusieurs boîtes colorées
- **Icosphère** - Polyèdres animés
- **Sphère Simple** - Test de géométrie sphérique

### 🎪 Démo spectaculaire
- **Multi-Objets** - Scène complexe avec animations (cube, icosahedron, cylindre, cône, texte animé)

## 🛠️ Technologies utilisées

- **AR.js** - Framework de réalité augmentée pour le web
- **A-Frame** - Framework pour créer des expériences VR/AR
- **HTML5/CSS3** - Structure et style
- **JavaScript** - Logique et interactions
- **Vercel** - Hébergement et déploiement

## 📋 Prérequis techniques

- **Navigateur moderne** (Chrome, Firefox, Safari recommandés)
- **Caméra/Webcam** fonctionnelle
- **Connexion HTTPS** (requis pour l'accès caméra)
- **Marqueur Hiro** (disponible dans l'application)

## 💻 Installation locale

```bash
# Cloner le repository
git clone https://github.com/[votre-username]/Ar.git

# Aller dans le dossier
cd Ar

# Lancer un serveur local (avec Node.js)
npx http-server -p 8000

# Ou avec Python
python -m http.server 8000
```

Puis ouvrir : `http://localhost:8000`

## 🎯 Comment utiliser

1. **Ouvrir l'application** : [https://ar-flax.vercel.app/](https://ar-flax.vercel.app/)
2. **Obtenir le marqueur Hiro** depuis l'application (afficher sur téléphone ou imprimer)
3. **Autoriser l'accès à la caméra** quand demandé
4. **Pointer la caméra vers le marqueur**
5. **Les objets 3D apparaissent** sur le marqueur !

## 📁 Structure du projet

```
Ar/
├── index.html                    # Page d'accueil avec menu
├── marqueur-hiro.html           # Page du marqueur Hiro
├── hiro-marker.png              # Image du marqueur
├── demo-boite-transparente.html # Démo boîte
├── demo-sphere-bleue.html       # Démo sphère
├── demo-multi-marqueurs.html    # Démo multi-objets
├── demo-icosphere.html          # Démo polyèdres
├── test-*.html                  # Fichiers de test
└── README.md                    # Ce fichier
```

## 🔧 Résolution des problèmes

### L'objet 3D n'apparaît pas ?
- ✅ Vérifier que la caméra est autorisée
- ✅ Bien éclairer le marqueur
- ✅ Tenir le marqueur à 30-50cm de la caméra
- ✅ Le marqueur doit être complet et plat
- ✅ Éviter les reflets sur l'écran

### Problèmes de performance ?
- ✅ Fermer les autres onglets
- ✅ Utiliser Chrome ou Firefox
- ✅ Vérifier la connexion internet

## 🚀 Déploiement

Le projet est automatiquement déployé sur Vercel à chaque push sur la branche principale.

## 📜 Licence

**Aucune licence spécifique** - Projet personnel à but éducatif et portfolio.

## 🤝 Contribution

Projet personnel pour portfolio. Les suggestions sont les bienvenues via les issues GitHub.

## 📞 Contact

**VIYR Brandon**
- Projet créé pour démontrer les compétences en développement web AR
- Fait partie de mon portfolio de développeur

---

*Dernière mise à jour : Août 2024*
