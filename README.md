<div align="center">
  <img src="https://imgur.com/a/vC7HCbz" alt="OneForAll Bot" width="100" height="100" style="border-radius: 50%;">
  
  # OneForAll Discord Bot V14
  
  [![Discord.js](https://img.shields.io/badge/Discord.js-14.22.1-blue.svg)](https://discord.js.org/)
  [![Sequelize](https://img.shields.io/badge/Sequelize-6.x-green.svg)](https://sequelize.org/)
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
  **Bot Discord moderne avec système de permissions avancé et protection antiraid**
</div>

---

## ✨ Fonctionnalités

- 🔧 **Modération** : Ban, Kick, Mute, Lock, Antiraid
- 🛡️ **Sécurité** : Anti-spam, Anti-lien, Anti-mention
- 👥 **Gestion** : Rôles automatiques, Giveaways, Tickets
- 📊 **Stats** : Leaderboard, XP System, Monitoring

## 🚀 Installation

```bash
# Cloner le repo
git clone https://github.com/Hen3lio/OneForAll-Discord-Bot-V14.git
cd OneForAll-Discord-Bot-V14

# Installer les dépendances
npm install

# Configurer
cp config.example.js config.js
# Éditer config.js avec votre token

# Lancer
npm start
```

## 📋 Prérequis

- Node.js 16+
- Discord.js 14.22.1
- SQLite3 (inclus)

## 🔧 Configuration

```javascript
// config.js
module.exports = {
    token: "VOTRE_TOKEN_BOT",
    owners: ["VOTRE_ID_DISCORD"],
    embedColor: "#36393E"
};
```

## 📚 Commandes Principales

| Catégorie | Commandes |
|-----------|-----------|
| **Modération** | `/ban`, `/kick`, `/mute`, `/lock` |
| **Antiraid** | `/antiraid config`, `/antiraid on/off` |
| **Gestion** | `/autorole`, `/giveaway`, `/backup` |
| **Utilitaires** | `/help`, `/ping`, `/info` |

## 🏗️ Structure

```
src/
├── commands/          # Commandes textuelles
├── slashCommands/     # Commandes slash
├── events/           # Événements Discord
├── structures/       # Classes principales
└── utils/           # Utilitaires
```

## 🤝 Contribution

1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit (`git commit -m 'Add AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📄 Licence

MIT License - Voir [LICENSE](LICENSE) pour plus de détails.

---

<div align="center">
  
  **⭐ Star ce repo si ça vous aide ! ⭐**
  
  *Développé par [Hen3lio](https://github.com/Hen3lio)*
  
</div>
