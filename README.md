# CP2 Ads

Static image hosting for the Club Penguin 2 VRChat world.

## Live ad image URLs

- https://timingplanet.github.io/cp2-ads/ads/courtyard-north.png (1600×900)
- https://timingplanet.github.io/cp2-ads/ads/courtyard-south.png (1600×900)
- https://timingplanet.github.io/cp2-ads/ads/queue-wide.png (1600×900)
- https://timingplanet.github.io/cp2-ads/ads/queue-tall.png (1080×1440)

All images use the original YOUR AD HERE placeholder artwork. The three wide slots use the landscape poster, and the tall slot uses the portrait poster.

The original vector designs are in `source/`. The GitHub Actions workflow builds and commits the four PNGs into `ads/` from those originals.

## Pages configuration

Use **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

The empty `.nojekyll` file prevents Jekyll processing.
