# D\u0026D Assets Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licensesu0026logoColor=white)](https://hub.docker.com/r/tiation/dnd-assets)

## 🏰 About

An enterprise-grade Dungeons \u0026 Dragons assets management system designed to handle character sheets, campaigns, maps, and game resources with modern DevOps practices and striking, edgy design.

## 🎯 Mission

This project is developed in collaboration with **ChaseWhiteRabbit NGO**, supporting their mission to create accessible, ethical, and innovative gaming solutions for communities worldwide.

### ChaseWhiteRabbit NGO Partnership

- **Mission Alignment**: Supporting accessible gaming and community building
- **Ethical Development**: Following open-source principles and community-driven development
- **Social Impact**: Enabling inclusive D\u0026D experiences for diverse communities
- **Sustainability**: Built with long-term maintenance and scalability in mind

## ✨ Features

- 🎲 **Asset Management**: Comprehensive D\u0026D resource organization
- 🏗️ **Enterprise Architecture**: Scalable, maintainable codebase
- 🚀 **CI/CD Pipeline**: Automated testing, building, and deployment
- 🐳 **Containerized**: Docker-ready for any environment
- 📊 **Monitoring**: Integrated observability and health checks
- 🔒 **Security**: Enterprise-grade security practices
- 🎨 **Modern UI**: Striking, edgy design with accessibility focus

## 📁 Structure

```
portraits/
├── warrior/         # Warrior class portraits
├── mage/           # Mage class portraits
├── rogue/          # Rogue class portraits
├── cleric/         # Cleric class portraits
├── ranger/         # Ranger class portraits
├── paladin/        # Paladin class portraits
├── bard/           # Bard class portraits
├── druid/          # Druid class portraits
├── common/         # Common rarity portraits
├── rare/           # Rare rarity portraits
├── epic/           # Epic rarity portraits
└── legendary/      # Legendary rarity portraits
```

## 🎨 Art Styles

### Class-Specific Portraits
Each class directory contains portraits in the following variations:
- `base.gif` - Standard pose
- `action-1.gif` - Primary action animation
- `action-2.gif` - Secondary action animation
- `special.gif` - Special ability animation

### Rarity-Based Portraits
The rarity directories contain general-purpose portraits with increasing levels of visual effects:
- Common: Basic animations
- Rare: Enhanced effects
- Epic: Advanced particle effects
- Legendary: Ultimate visual effects

## 🛠 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/tiation/dnd-assets.git
   ```

2. Use the portraits in your application:
   ```typescript
   // Example usage in a Next.js component
   import Image from 'next/image'
   
   const CharacterPortrait = ({ class, rarity }) => {
     const portraitUrl = `https://raw.githubusercontent.com/tiation/dnd-assets/main/portraits/${class}/base.gif`
     
     return (
       <Image
         src={portraitUrl}
         alt={`${class} character portrait`}
         width={400}
         height={400}
         className="character-portrait"
       />
     )
   }
   ```

## 🎮 Animation Details

Each portrait is designed with the following specifications:
- Format: Animated GIF
- Dimensions: 400x400 pixels
- Frame Rate: 24fps
- Animation Length: 2-4 seconds
- Loop: Infinite
- Style: Dark neon fantasy with class-appropriate effects

## 🔄 Updates

The assets are regularly updated with:
- New character classes
- Additional animations
- Enhanced visual effects
- Improved quality versions

## 🎨 Art Style Guide

All portraits follow these style guidelines:
- Dark neon fantasy theme
- Cyan/magenta gradient effects
- Glowing magical elements
- Dynamic lighting
- Smooth animations
- Professional fantasy art style

## 📄 License

These assets are available under the MIT license. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

We welcome contributions! Please check our [contribution guidelines](CONTRIBUTING.md) for details on how to submit new portraits or improvements.
