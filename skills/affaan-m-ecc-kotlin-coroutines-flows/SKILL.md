<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-kotlin-coroutines-flows
description: "Structured concurrency with Muse for Android and KMP: scopes, StateFlow and SharedFlow patterns..."
---

# Kotlin Coroutines and Flows

Curated by Skill Harbor: a structured-concurrency guide that makes Muse write Kotlin coroutines and Flows correctly on Android and Kotlin Multiplatform. It starts with the scope hierarchy (viewModelScope, coroutineScope, never GlobalScope) and parallel decomposition with async/await, plus supervisorScope for independent children. Flow patterns cover cold flows, StateFlow for UI state with SharingStarted.WhileSubscribed, combining multiple flows into one UI state, and operators like debounce, distinctUntilChanged, flatMapLatest, catch and retryWith exponential backoff. SharedFlow is presented for one-time events like snackbars and navigation, with a sealed Effect interface collected in a composable. Dispatchers get the CPU versus IO versus Main rules with the KMP caveat that Dispatchers.IO is JVM and Android only. Cancellation covers cooperative ensureActive checks and try/finally cleanup, testing covers Turbine assertions on StateFlow and TestDispatcher with advanceUntilIdle, and the skill closes with the anti-patterns to avoid (GlobalScope, catching CancellationException, mutable collections in StateFlow). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: examples assume Android ViewModel and Compose conventions; KMP projects need dispatcher injection for non-JVM targets; it teaches patterns, it does not debug your race conditions for you. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-kotlin-coroutines-flows
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-kotlin-coroutines-flows
- Category: Kotlin
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/kotlin-coroutines-flows/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
