<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-react-native-patterns
description: "Production React Native and Expo for Muse: Expo Router navigation, state separation, TanStack Query..."
---

# React Native Patterns

Curated by Skill Harbor: practical patterns for building production React Native apps with Expo, so Muse writes mobile code that respects the platform instead of porting web habits. Assumes the managed Expo workflow (Expo Router, EAS, expo modules) on the New Architecture. Covers file-based routing under app/ with thin route files that validate deep-link params with Zod before use, state separation by concern (server state in TanStack Query or SWR, client UI state in Zustand or Jotai, route state in router params, form state in a form library, secrets in expo-secure-store, never AsyncStorage for tokens), data fetching with a server-cache library plus Zod validation at the boundary with explicit loading, error and empty states, list virtualization (FlatList, FlashList for large lists, memoized renderItem, stable keyExtractor, never map a big array inside a ScrollView), one consistent styling system (NativeWind or StyleSheet.create, never inline style objects on hot paths), and native APIs wrapped in use* hooks with cleanup (location, camera, notifications). Includes a catalog of mobile anti-patterns (duplicating server data into a client store, trusting deep-link params, shipping real secrets in the bundle) and best practices (thin routes, validate every external input, reanimated for UI-thread animation, safe areas and accessibility from the start). Library names are illustrative, the patterns matter more than the package. Use when building or editing Expo screens...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-react-native-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-react-native-patterns
- Category: Mobile
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/react-native-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
