# SpaceNamer releases

Public host for the SpaceNamer update feed and builds. Served by GitHub Pages
at <https://updates.spacenamer.app>.

- `appcast.xml` — the Sparkle feed every installed copy polls
- `releases/` — the notarized DMGs

Nothing here is edited by hand. `scripts/release.sh` in the app repo builds,
notarizes, regenerates the appcast and pushes.

The app source lives in a private repo: publishing it would expose the Ed25519
license-signing key held in its history.
