# Bridge Comparison Screen

This repository contains the frontend implementation for the Bridge Compatibility Comparison screen, built with **React Native (Expo)** and styled using **NativeWind (Tailwind CSS)**. 

## Preview

Check out precisely how the design translates from the Figma mockups using exact styling specifications:

![Compatibility Screen Preview](https://files.catbox.moe/qk7t2c.png)

## Overview

The comparison screen allows users to quickly view their compatibility percentage and compare alignment across multiple areas.

### Key Features
*   **Design Accuracy:** Beautiful glassmorphism, exact `Outfit` typography, precise padding, layout sizing, and exact colors matching the design spec.
*   **Ready-to-Use Local Context:** All mock data is contained in `CompatibilityContext.tsx` and dynamically fed, supporting both static network URIs and standard arrays for tags.
*   **Cross-Platform Fidelity:** Developed to render pixel-perfect matches across iOS, Android, and Expo Web.

## Setup Instructions

1. **Install Dependencies:**
   ```bash
   npm install --legacy-peer-deps
   ```
2. **Run the Project:**
   ```bash
   npx expo start
   ```
   *Press `i` for iOS, `a` for Android, or `w` for Web.*

## Future Backend Integration
All images are currently served via hosted unplash/catbox network urls inside `CompatibilityContext.tsx` making the component fully ready to accept remote profiles fetched from an API endpoint.
