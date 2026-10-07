<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: flutter-agent-plugins-dart-generate-test-mocks
description: "Define and generate mock objects for external dependencies with package:mockito and build_runner —..."
---

# Generate Mockito mocks for Dart tests with build_runner

Curated by Skill Harbor — @flutter's skill for generating Mockito mocks in Dart tests with `build_runner`: design classes for testability (inject external services through constructors, represent URLs as `Uri.parse()`), configure `pubspec.yaml` (`dart pub add dev:test dev:mockito dev:build_runner`), annotate the test file with `@GenerateNiceMocks([MockSpec<Dependency>()])` (preferred over `@GenerateMocks` to avoid missing-stub exceptions), import the generated `.mocks.dart` file, run `dart run build_runner build`. Stubbing rules: `when(mock.method()).thenReturn(value)` for sync methods, but **always** `thenAnswer((_) async => value)` for methods returning Future or Stream — never `thenReturn` on async. Verify interactions with `verify(mock.method()).called(n)` and argument matchers (`any`, `anyNamed`, `captureAny`). Includes a 10-step creating-and-running workflow with checklist and a feedback loop for the classic failures (unexpected-null mock errors → use `@GenerateNiceMocks`; async `ArgumentError` → switch to `thenAnswer`; build_runner failures → check the `.mocks.dart` import matches the file name exactly). Honest caveats: methodology only — you need the Dart SDK and classes designed with constructor injection; the companion skill dart-add-unit-test (same repo) covers the test-writing side; note a similar listing `dart-lang-skills-dart-generate-test-mocks` from a different repo also exists on Skill Harbor — this one is the flutter/agent-plugins version. BSD-3-Clause...

- Listing: https://theskillharbor.com/products/flutter-agent-plugins-dart-generate-test-mocks
- Fiche en français: https://theskillharbor.com/fr/products/flutter-agent-plugins-dart-generate-test-mocks
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/flutter/agent-plugins/blob/main/skills/dart-generate-test-mocks/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
