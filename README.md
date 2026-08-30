# Catdress Web

A free, browser-based preview of [Catdress](https://apps.apple.com/app/id6775200511) — dress your cat in AI-generated outfits, right from a link, no app install required.

**Live site:** https://anranmg.github.io/catdress/

## What this is

This repo hosts the static build output for Catdress's web discovery funnel: a minimal, free-tier slice of the full app (20 curated outfits, a limited number of free AI generations) meant to give people a taste and drive them to download the real iOS app for the full 181-outfit catalog and unlimited generations.

## Updating this site

From the main app repo:

```bash
flutter build web --release --base-href /

Then copy build/web/* into this repo, commit, and push to main — GitHub Pages picks up the change automatically within a minute or two.

Get the full app

📱 Download Catdress on the App Store (https://apps.apple.com/app/id6775200511)
