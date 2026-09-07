# Sirocco — downloads

System monitor and task manager for macOS (Apple Silicon, macOS 14+). *Your Mac is getting hot: know why, stop it.*

Download the latest `Sirocco-x.y.z.dmg` from **Releases**, open it and drag Sirocco onto Applications. The app updates itself from then on (Sparkle).

Builds are not notarized yet, so macOS refuses the first launch. Clear the quarantine flag once:

```bash
xattr -dr com.apple.quarantine /Applications/Sirocco.app
```

14-day free trial from first launch. Source: https://github.com/simiriva95/sirocco
