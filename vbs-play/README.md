# VBS Play COMPLETE³

A clean, touch-first launcher containing:

- VBS Retro: local ROM preflight and EmulatorJS launch
- VBS Poker: playable Hold'em trainer
- VBS Infinity: playable survival prototype
- Diagnostics: device/browser capability checks

## Local test

Serve the repository root with any static server and open `/vbs-play/`.

## Cloudflare target

Deploy the repository as static assets and expose `/vbs-play/`. Preserve the existing `/vbs-retro/` address as a redirect to `/vbs-play/#retro` or the future separated `/vbs-play/apps/retro/` route.

## Boundary

No commercial ROMs are included. ROMs selected by the user stay local to the browser session.

## COMPLETE³ scope

1. One-page launcher and setup surface.
2. Playable Retro, Poker and Infinity modes.
3. Device diagnostics.
4. Downloadable modular package is also preserved separately as `VBS_Play_COMPLETE3.zip` in the build handoff.
5. Cloudflare production promotion remains gated until the Cloudflare account connector is available or the branch is merged and connected in the Cloudflare dashboard.
