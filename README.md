# Sirocco — downloads

System monitor and task manager for macOS (Apple Silicon, macOS 14+). *Your Mac is getting hot: know why, stop it.*

Download the latest `Sirocco.zip` from **Releases**, unzip, move `Sirocco.app` to `/Applications`.

Builds are not notarized yet, so macOS refuses the first launch. Clear the quarantine flag once:

```bash
xattr -dr com.apple.quarantine /Applications/Sirocco.app
```

14-day free trial from first launch. The source code is private during the beta.
