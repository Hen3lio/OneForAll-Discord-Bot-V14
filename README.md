<div align="center">
  <img src="https://i.imgur.com/your-image-url.png" alt="OneForAll Bot" width="200" height="200" style="border-radius: 50%;">
  
  # OneForAll Discord Bot V14
  
  [![Discord.js](https://img.shields.io/badge/Discord.js-14.22.1-blue.svg)](https://discord.js.org/)
  [![Sequelize](https://img.shields.io/badge/Sequelize-6.x-green.svg)](https://sequelize.org/)
  [![SQLite3](https://img.shields.io/badge/SQLite3-5.x-lightblue.svg)](https://sqlite.org/)
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Node.js](https://img.shields.io/badge/Node.js-16.x+-brightgreen.svg)](https://nodejs.org/)
  
  **Un bot Discord moderne et puissant avec un système de permissions avancé, antiraid, et bien plus encore !**
  
  [![Discord](https://img.shields.io/discord/your-server-id?color=5865F2&logo=discord&logoColor=white)](https://discord.gg/your-invite)
  [![GitHub stars](https://img.shields.io/github/stars/Hen3lio/OneForAll-Discord-Bot-V14?style=social)](https://github.com/Hen3lio/OneForAll-Discord-Bot-V14)
  [![GitHub forks](https://img.shields.io/github/forks/Hen3lio/OneForAll-Discord-Bot-V14?style=social)](https://github.com/Hen3lio/OneForAll-Discord-Bot-V14)
</div>

---

## 🚀 Fonctionnalités

### 🔧 **Modération Avancée**
- **Système de sanctions** : Ban, Kick, Mute, Unrank
- **Antiraid intelligent** : Protection contre les raids automatiques
- **Système de permissions** : Contrôle granulaire des accès
- **Logs complets** : Traçabilité de toutes les actions

### 🛡️ **Sécurité & Protection**
- **Anti-spam** : Détection et prévention du spam
- **Anti-lien** : Filtrage des liens suspects
- **Anti-mention** : Protection contre les mentions massives
- **Anti-token** : Détection des tentatives de token grab

### 🎯 **Gestion de Serveur**
- **Système de rôles** : Attribution automatique et manuelle
- **Giveaways** : Organisation de concours intégrés
- **Tickets** : Système de support technique
- **Backup** : Sauvegarde automatique des configurations

### 📊 **Statistiques & Monitoring**
- **Tableau de bord** : Vue d'ensemble des métriques
- **Leaderboard** : Classements des membres
- **Statistiques vocales** : Monitoring des canaux vocaux
- **XP System** : Système d'expérience et de niveaux

---

## 📋 Prérequis

- **Node.js** 16.x ou supérieur
- **Discord.js** 14.22.1
- **Sequelize** 6.x
- **SQLite3** 5.x
- Un bot Discord avec les permissions appropriées

---

## ⚡ Installation Rapide

### 1. **Cloner le repository**
```bash
git clone https://github.com/Hen3lio/OneForAll-Discord-Bot-V14.git
cd OneForAll-Discord-Bot-V14
```

### 2. **Installer les dépendances**
```bash
npm install
```

### 3. **Configuration**
```bash
# Copier le fichier de configuration
cp config.example.js config.js

# Éditer la configuration
nano config.js
```

### 4. **Configuration de la base de données**
```bash
# La base de données SQLite sera créée automatiquement
# Aucune configuration supplémentaire requise
```

### 5. **Lancer le bot**
```bash
npm start
# ou
node index.js
```

---

## 🔧 Configuration

### **Fichier config.js**
```javascript
module.exports = {
    token: "VOTRE_TOKEN_BOT",
    owners: ["VOTRE_ID_DISCORD"],
    embedColor: "#36393E",
    // ... autres options
};
```

### **Permissions Discord requises**
- `SEND_MESSAGES`
- `EMBED_LINKS`
- `MANAGE_ROLES`
- `MANAGE_CHANNELS`
- `BAN_MEMBERS`
- `KICK_MEMBERS`
- `MANAGE_MESSAGES`
- `READ_MESSAGE_HISTORY`

---

## 📚 Commandes Disponibles

### **🔨 Modération**
- `/ban` - Bannir un utilisateur
- `/kick` - Expulser un utilisateur
- `/mute` - Rendre muet un utilisateur
- `/unban` - Débannir un utilisateur
- `/lock` - Verrouiller un canal
- `/renew` - Renouveler un canal

### **🛡️ Antiraid**
- `/antiraid config` - Configurer l'antiraid
- `/antiraid on/off` - Activer/désactiver l'antiraid

### **👥 Gestion**
- `/autorole` - Gestion des rôles automatiques
- `/massrole` - Attribution de rôles en masse
- `/backup` - Sauvegarde du serveur
- `/giveaway` - Créer un giveaway

### **📊 Utilitaires**
- `/help` - Aide et liste des commandes
- `/ping` - Latence du bot
- `/info` - Informations sur le serveur
- `/avatar` - Afficher l'avatar d'un utilisateur

---

## 🏗️ Architecture

```
OneForAll-Discord-Bot-V14/
├── src/
│   ├── commands/          # Commandes textuelles
│   ├── slashCommands/     # Commandes slash
│   ├── events/           # Événements Discord
│   ├── structures/       # Classes principales
│   ├── utils/           # Utilitaires
│   └── langs/           # Fichiers de langue
├── config.js            # Configuration
├── package.json         # Dépendances
└── README.md           # Documentation
```

---

## 🌍 Support Multilingue

- 🇫🇷 **Français** (par défaut)
- 🇺🇸 **Anglais**
- *Plus de langues à venir...*

---

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. **Fork** le projet
2. Créer une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. **Commit** vos changements (`git commit -m 'Add some AmazingFeature'`)
4. **Push** vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une **Pull Request**

---

## 📝 Changelog

### **Version 2.0.0** - *Discord.js V14*
- ✅ Migration vers Discord.js 14.22.1
- ✅ Nouveau système de permissions
- ✅ Interface utilisateur améliorée
- ✅ Performance optimisée
- ✅ Support des commandes slash modernes

### **Version 1.x.x** - *Legacy*
- Système de base avec Discord.js v13
- Fonctionnalités antiraid de base
- Système de permissions simple

---

## 🐛 Signaler un Bug

Si vous trouvez un bug, merci de créer une issue avec :
- Description détaillée du problème
- Étapes pour reproduire le bug
- Version de Node.js et Discord.js
- Logs d'erreur (si applicable)

---

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

```
MIT License

Copyright (c) 2025 Hen3lio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 👨‍💻 Auteur

**Hen3lio**
- GitHub: [@Hen3lio](https://github.com/Hen3lio)
- Discord: `Hen3lio#0000`

---

## 🙏 Remerciements

- [Discord.js](https://discord.js.org/) - API Discord pour Node.js
- [Sequelize](https://sequelize.org/) - ORM pour Node.js
- [SQLite](https://sqlite.org/) - Base de données légère
- Communauté Discord.js pour le support

---

<div align="center">
  
  **⭐ N'oubliez pas de mettre une étoile si ce projet vous a aidé ! ⭐**
  
  [![GitHub stars](https://img.shields.io/github/stars/Hen3lio/OneForAll-Discord-Bot-V14?style=for-the-badge)](https://github.com/Hen3lio/OneForAll-Discord-Bot-V14)
  
  *Développé avec ❤️ par Hen3lio*
  
</div>
