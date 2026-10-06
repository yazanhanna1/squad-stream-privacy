---
title: Squad Stream Privacy Policy
---

# Squad Stream privacy policy

Last updated: October 6, 2026.

Squad Stream lets you view and organize multiple Twitch broadcasts together. This policy describes the extension's behavior.

## Information used by the extension

The extension reads the current Twitch channel route and collaboration information to identify broadcasts and Stream Together participants. It processes channel names, participant names, and your selected lineup, channel order, chat selection and layout.

Starting with version 1.0.1, viewing preferences exist only in memory for the current viewer session. Each opening starts with the current broadcaster and any detected Stream Together participants. The extension does not save or restore lineups, channel order, chat selection, or layout across sessions, and separate viewers do not synchronize their settings.

## Requests to Twitch

To identify public collaboration participants, the extension sends the current broadcaster's login and channel ID to Twitch's HTTPS GraphQL service. These lookup requests omit cookies and authentication credentials.

Twitch provides the native player, embedded streams, and embedded chat. Loading them sends the requested channel and ordinary network information, such as your IP address, to Twitch. Twitch's website and embeds may use your existing Twitch session, cookies, and their own tracking technologies, subject to your browser settings and Twitch's policies. The extension does not read your password or authentication tokens.

## Developer collection and sharing

The extension has no developer-operated collection server, analytics SDK, or advertising SDK. It does not sell user information. It does not access browser history APIs or unrelated websites. Network requests described above are necessary to obtain Twitch's broadcasts, chat, and collaboration information.

## Retention and control

Current session settings are discarded when you close the viewer or leave the page. Version 1.0.0 stored preferences locally; version 1.0.1 does not access or restore those settings. Any legacy stored settings can be removed by clearing the extension's stored data or uninstalling it. Data handled by Twitch is governed by Twitch's own policies; uninstalling this extension does not delete information held by Twitch.

## Changes and contact

This policy should be updated when the extension's data practices change.

Publisher: **Yazan Builds**

Support: **yazanbuilds@gmail.com**
