> *The following text is extracted and transformed from the smapi.io privacy policy that was archived on 2019-08-25. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20190825213127id_/https%3A//smapi.io/privacy) for the most accurate reproduction.*

# SMAPI privacy notes - SMAPI.io

← [back to SMAPI page](https://smapi.io/)

SMAPI is an [open-source](https://github.com/Pathoschild/SMAPI) and non-profit project. Your privacy is important, so this page explains what information SMAPI uses and transmits. **This page is informational only, it's not a legal document.**

## Principles

  1. SMAPI collects the minimum information needed to enable its features (see below).
  2. SMAPI does not collect telemetry, analytics, etc.
  3. SMAPI will never sell your information.



## Data collected and transmitted

### Web logging

This website and SMAPI's web API are hosted by Amazon Web Services. Their servers may automatically collect diagnostics like your IP address, but this information is not visible to SMAPI's web application or developers. For more information, see the [Amazon Privacy Notice](https://aws.amazon.com/privacy/).

### Update checks

SMAPI notifies you when there's a new version of SMAPI or your mods available. To do so, it sends your SMAPI and mod versions to its web API. No personal information is stored by the web application, but see _web logging_.

You can disable update checks, and no information will be transmitted to the web API. To do so:

  1. [find your game folder](https://stardewvalleywiki.com/Modding:Game_folder);
  2. open the `smapi-internal/config.json` file in a text editor;
  3. change `"CheckForUpdates": true` to `"CheckForUpdates": false`.



### Log parser

The [log parser page](https://log.smapi.io/) lets you store a log file for analysis and sharing. The log data is stored indefinitely in an obfuscated form as unlisted pastes in [Pastebin](https://pastebin.com/). No personal information is stored by the log parser beyond what you choose to upload, but see _web logging_ and the [Pastebin Privacy Statement](https://pastebin.com/doc_privacy_statement).

### Multiplayer sync

As part of its multiplayer API, SMAPI transmits basic context to players you connect to (mainly your OS, SMAPI version, game version, and installed mods). This is used to enable multiplayer features like inter-mod messages, compatibility checks, etc. Although this information is normally hidden from players, it may be visible due to mods or configuration changes.

### Custom mods

**Mods may collect and transmit any information. Mods (except those provided as part of the SMAPI download) are not covered by this page. Install third-party mods at your own risk.**
