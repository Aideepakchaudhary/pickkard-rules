# Pickkard's reward rates

The reward rates the [Pickkard](https://pickkard.in) app uses, published at `https://rules.pickkard.in` for
phones to download.

- `manifest.json` names the newest rates file, with its SHA-256 fingerprint and an Ed25519 signature.
- `rules.v<N>.json` is version N of the rates. A published file never changes: every change gets a new version
  number.

Everything here is published automatically from Pickkard's own project. The app accepts a rates file only when its
signature checks out against the key built into the app, so a file changed by anyone else is simply refused.

The rates come from the banks' published terms and offers, and banks change them, so treat them as a guide, not a
guarantee. Questions: see [pickkard.in](https://pickkard.in).
