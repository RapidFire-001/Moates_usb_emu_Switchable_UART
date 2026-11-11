# Moates USB EMU Switchable UART

Community source snapshot of a modified OneROM USB system plugin, shared by Rapidfire. Features in the supplied source include Ostrich-compatible serial access, selectable UART/ALDL profiles and address tracing.

**Unofficial compatibility project. Not an official Moates product, endorsement, or Moates firmware release.** This is OneROM plugin source, not firmware for flashing an original Moates Ostrich device.

## Download and build status

> **Microsoft Edge download notice.** SmartScreen may warn that a file isn’t commonly downloaded when it has limited download history. If Edge or your antivirus shows a malware warning, please send the exact message and the file name or release version so I can investigate. If the GitHub page is unavailable in Edge, you can also view it in Firefox or Chrome. See [Microsoft’s SmartScreen guidance](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

Use GitHub's **Code → Download ZIP** for the full repository, or download the source snapshot from Releases. The plugin directory is named `Moates_usb_emu_Switchable_UART`.

This publication preserves the supplied plugin v0.2.0 source. It is **not** the separately migrated OneROM v0.8.0 package. No compiled firmware or Windows application is supplied here. This snapshot has not been rebuilt or tested on hardware as part of publication.

The Makefile expects an enclosing OneROM source tree with the older `sdrr` layout, generated headers, an ARM toolchain and dependencies. It is not a standalone build. See the original README and BUILD_OPTIONS.md inside the plugin directory. Dependency references are recorded in DEPENDENCIES.md; the exact enclosing OneROM revision was not established from this folder.

## Credits and thanks

- **Piers Finlayson**: original OneROM USB plugin, picobootx and pico-sdkless; named in the retained source copyright notices.
- **Ha Thach and TinyUSB contributors**: USB stack and descriptor code; retained notices and licence text apply.
- **TXRX**: the supplied Ostrich extension contains `Copyright 2026 TXRX`. That marker is preserved. The identity behind it and the complete modification history have not been independently established.
- **Martin Strand / ostrich2**: referenced in the supplied Ostrich protocol implementation as a protocol reference; this does not establish authorship of this plugin.

Thank you to the original authors and contributors for making this work available. Rapidfire hosts this snapshot and prepared its publication documentation; no claim is made to sole authorship or ownership of the underlying code.

Original code, source headers, build scripts, changelog and documentation are retained without code changes. Publication changes add this README, attribution/licence documentation, dependency references and checksums, and prefix the distribution folder with “Moates”. Local AI configuration, dependency Git histories, empty output directories and build directories are omitted.

## Licence

The supplied plugin source identifies itself as MIT-licensed. Existing copyright notices remain with their respective holders. See LICENSE, ATTRIBUTION.md and licenses/ for the terms and dependency notices. No exclusive or proprietary ownership claim is added by this publication.

## Support

For help with this software, email [Rapid Fire Software Support](mailto:support@rapidfiresoftware.net). Include the software version, what you were trying to do, and any error message you saw.
