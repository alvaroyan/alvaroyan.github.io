# Álvaro Yángüez — academic website

Personal academic website for research in quantum information theory, computational complexity, and quantum cryptography.

## Local development

The site uses Hugo Extended and the Hugo Blox module. The deployment configuration is pinned to Hugo `0.136.5`.

```powershell
hugo server
```

For a production build:

```powershell
hugo --gc --minify --cleanDestinationDir
```

Core content is stored in `content/`, homepage activity data in `data/home.yaml`, and the custom visual system in `assets/css/custom.css`.
