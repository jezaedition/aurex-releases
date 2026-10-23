# Aurex 1.6.1 — Universal Public Preview

[Download Aurex for Mac](https://github.com/jezaedition/aurex-releases/raw/refs/heads/main/Aurex-1.6.1-Mac.zip)

For Mac mini, Mac Studio, MacBook and iMac running macOS 14.2 or later. Includes Intel x86_64 and Apple silicon arm64 builds. Live tested on the developer's current Apple silicon Mac; not every Mac/OS combination.

Extract the ZIP, move the complete Aurex folder to Applications or another permanent location, and open Aurex.app. See START HERE.txt for optional Chrome companion setup. No Python dependency.

**This is a development preview, not Apple Developer ID signed or notarized.** macOS may block it. Review [Apple's guidance](https://support.apple.com/102445) before deciding whether to allow software. This release does not disable Gatekeeper. An independent security audit has not been performed.

## Updates

Aurex checks the signed appcast while running and online. A published higher compatible build can be installed through the update prompt, replacing the existing app while preserving separately stored settings and shelf. The unpacked Chrome companion requires a separate extension reload/update; Sparkle does not update that extension.

## Features and limits

Music controls, file shelf, timer/alarm, camera mirror, focus timer, disk read/write test and drawn song-progress animals. Animal progress needs finite media duration. AirDrop success events cover sends initiated in Aurex; system-wide incoming AirDrop and Finder paste/move completion are not tracked. Disk results are brief throughput measurements, not codec certification. Some audio outputs do not expose software volume. Software permissions apply to the corresponding integrations.

The app archive and update feed use Sparkle Ed25519 signatures. These signatures authenticate Aurex updates; they are separate from Apple Developer ID signing and notarization.
