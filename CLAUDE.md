# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Single static HTML file (`index.html`) — no build step, no dependencies. It is a branded landing page that deep-links users into the Farm Reports mobile app via Expo Go.

Clicking "Open Farm Reports" fires `exp://u.expo.dev/<projectId>?channel-name=preview`. If Expo Go isn't installed, a fallback UI appears after 2.5 seconds with App Store / Google Play download links.

## Key Values

- **Expo Project ID:** `bdb6a038-448e-4bd1-977a-b5da6a662739`
- **Expo channel:** `preview`
- **Brand colour:** `#2d6a4f` (matches the mobile app and dashboard)

## Deployment

Host `index.html` on any static file server. No build or compile step required.
