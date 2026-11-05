# flutter_sound-v2-compat

This is a minimal compatibility fork of upstream `flutter_sound 9.30.0`.

## Patch scope

- Removes only the obsolete, commented-out Android v1 `PluginRegistry.Registrar` import and `registerWith` example from `FlutterSound.java`.
- Leaves the active Flutter v2 `FlutterPlugin` and `ActivityAware` implementation unchanged.
- Does not change Dart APIs, playback, recording, codecs, or platform channel behaviour.

The upstream package is licensed under MPL-2.0. The modified source remains under MPL-2.0; see the upstream LICENSE and notices in the source tree.

Upstream: https://github.com/Canardoux/flutter_sound
Pinned package version: 9.30.0
