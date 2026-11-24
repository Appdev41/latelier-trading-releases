# l'Atelier Trading — Releases

Ce dépôt **public** ne contient **aucun code source**.

Il sert uniquement à héberger :
- les installateurs Windows (`.exe`)
- les installateurs macOS (`.dmg`)
- les métadonnées d'auto-update (`latest.yml`, `latest-mac.yml`)

L'application installée vérifie ces Releases pour proposer les mises à jour.

## Téléchargement

Voir [Releases](https://github.com/Appdev41/latelier-trading-releases/releases).

- **Windows** : `lAtelierTrading-Setup-x.y.z.exe`
- **macOS Apple Silicon** : `lAtelierTrading-x.y.z-mac-arm64.dmg`
- **macOS Intel** : `lAtelierTrading-x.y.z-mac-x64.dmg`

### macOS — premier lancement

L’app n’est pas notariée Apple (distribution petit cercle). Si Gatekeeper bloque :

1. Clic droit sur l’app → **Ouvrir** → confirmer  
2. Ou en Terminal : `xattr -cr /Applications/lAtelierTrading.app`
