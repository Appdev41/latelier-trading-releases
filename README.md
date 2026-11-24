# l'Atelier Trading — Releases

Ce dépôt **public** ne contient **aucun code source**.

Il sert uniquement à héberger :
- les installateurs Windows (`.exe`)
- les installateurs macOS (`.zip` → `.app` ; `.dmg` quand buildé sur Mac)
- les métadonnées d'auto-update (`latest.yml`, `latest-mac.yml`)

L'application installée vérifie ces Releases pour proposer les mises à jour.

## Téléchargement

Voir [Releases](https://github.com/Appdev41/latelier-trading-releases/releases) — tag **v1.0.1** :

- **Windows** : `lAtelierTrading-Setup-1.0.1.exe`
- **macOS Apple Silicon** : `lAtelierTrading-1.0.1-mac-arm64.zip`
- **macOS Intel** : `lAtelierTrading-1.0.1-mac-x64.zip`

### macOS — installation (petit cercle)

1. Télécharge le `.zip` (arm64 pour M1/M2/M3, x64 pour Intel)
2. Ouvre → glisse `lAtelierTrading.app` dans **Applications**
3. Si Gatekeeper bloque : clic droit → **Ouvrir**, ou  
   `xattr -cr /Applications/lAtelierTrading.app`

Stripe / paiements : mêmes clés que le build Windows (embarquées, pas de code source).
