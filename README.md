# Watchroom releases

Watchroom is an independent Windows video workspace for an administrator-approved creator catalog, personal queues, watch-together rooms and community discussions across YouTube, Kick, Rumble and original uploads.

- [Use Watchroom](https://twinyoumusic.xyz/watchroom/)
- [Windows downloads and release notes](https://github.com/pixelgraple/watchroom-releases/releases)
- [Help](https://twinyoumusic.xyz/watchroom/support.html)
- [Privacy and data](https://twinyoumusic.xyz/watchroom/privacy.html)

## Optional updates

Install beta35 or later once to get the native updater. Open **App updates** in Watchroom. Automatic updates start off. If enabled, newer signed releases are checked every 30 minutes, downloaded and installed on normal app exit. You can instead check and install manually. Interface refresh preferences are separate and wait for a safe idle state.

Microsoft Store installations use Store-managed binary updates. The Store version is being prepared and has not been certified or published yet. Locally signed test packages are not public installers.

Release metadata is signed with Ed25519. Clients verify the pinned public key and the complete installer SHA-256 before launching it. This repository's workflow verifies a release and updates `watchroom-updates/stable.json`; no private signing key is stored here. Direct EXE installers are not currently Authenticode signed.

This repository contains distribution artifacts, release metadata and notes, not the private application source. File public technical bugs in Issues; never include passwords, recovery codes, private-room messages or personal account details.

Watchroom is not affiliated with YouTube, Google, Kick, Rumble or featured creators. Source playback and extension compatibility limits still apply.
