# Cyberarm's W3D Hub Linux Launcher (flatpak)

## Development
>[!NOTE]
> An active network connection is required to github.com and rubygems.org to download dependencies.

```
flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install build-dir dev.cyberarm.w3d.launcher.stable.yml
```

```
flatpak run dev.cyberarm.w3d.launcher.stable
```
