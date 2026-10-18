# Bk Web Studios

Digital business card and lead-gen page for freelance web design.

**Live:** https://burukyimesgen.com/card/
**Role:** Designer & developer (solo)
**Stack:** Hand-written HTML/CSS/JS, no build step — static and fast

## What it is

A single-page digital business card for a web design freelance business serving small businesses, churches, and community groups. The page replaces a paper card: one tap to message on Messenger, tap-to-copy contact info, and a one-button "copy my info to share" action for passing the whole card along by text.

## Design approach

Built around Apple's fluid-interface principles translated to the web: instant press feedback (never waiting for a release event), spring-based easing instead of flat durations, and glass/gloss materials (gradient fills, inset highlights, soft layered shadows) used only where something is meant to feel elevated — the primary call-to-action and the project photo. Typography uses size-specific tracking (tight negative letter-spacing on the big display name, near-zero on body copy) rather than one fixed value throughout.

Respects `prefers-color-scheme` for dark mode and `prefers-reduced-motion` for anyone who needs motion dialed back.

## Highlights

- Tap-to-copy contact fields (phone, email, site) with a visible-selection fallback when clipboard access isn't available
- Recent work shown inline: [Always with Compassion](https://alwayswithcompassion.com/) (senior care family home) and [Blue Touch](https://buruky.github.io/BlueTouchAFH/) (adult family home)
- Pricing and process laid out as a simple three-step flow (call → draft → live)
- Zero dependencies beyond a Google Font — no framework, no build tooling
