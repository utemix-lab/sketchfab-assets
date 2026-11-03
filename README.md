# Sketchfab assets

This is the working checkout of the public repository
[`utemix-lab/sketchfab-assets`](https://github.com/utemix-lab/sketchfab-assets).
It publishes selected portfolio images for links in Sketchfab annotations.

It is deliberately not part of the private `vovaipetrova` Git repository.
Add new approved images here, then commit and push **from this folder**:

```powershell
git add .
git commit -m "assets: add Sketchfab images"
git push
```

The parent repository ignores this exact folder, so normal V&P commits never
pick up these files. This does not automatically publish a new image: publishing
remains an explicit commit and push to the public repository.
