# Chrome Web Store Listing

## Name

Focused Mail

## Summary

A calmer inbox list for Gmail™, with minimalist styling and hover-to-act shortcuts.

## Description

Focused Mail makes the Gmail™ inbox list quieter and easier to scan. It restyles the
message list in place with cleaner spacing, softer label pills, date sections, and
a small unread accent.

Inspired by the calm, text-first feel of Notion Mail, Focused Mail keeps that
minimal inbox experience inside Gmail: no new mail client, no migration, no server.

Hover a row and press a shortcut to archive, delete, mark read or unread, star,
snooze, or select that message. The extension clicks Gmail's own visible controls,
so archive and delete still use Gmail's normal undo flow.

Focused Mail is CSS-first, has no build step, makes no network requests, and stores
only your shortcut and display settings in `chrome.storage.sync`.

Focused Mail is not affiliated with, endorsed by, or sponsored by Google. Gmail is
a trademark of Google LLC. Use of this trademark is subject to Google Permissions.
Notion Mail is a product of Notion Labs, Inc. Focused Mail is not affiliated with,
endorsed by, or sponsored by Notion.

## Category

Productivity

## Single Purpose

Focused Mail restyles the Gmail™ inbox list and adds local hover-to-act keyboard
shortcuts for that list.

## Permission Justification

`storage`: saves shortcut mappings and display toggles in `chrome.storage.sync`.

## Host Permission Justification

`https://mail.google.com/*`: required to apply the list styling and local keyboard
shortcuts inside Gmail™.

## Privacy Practices

Data collection: none.

The extension observes Gmail™ page content locally only to render its UI changes and
trigger Gmail controls selected by the user. It does not collect, transmit, sell,
share, or use this data for analytics, advertising, or profiling.

## Screenshot Data

Store screenshots in `store-assets/screenshots/` are generated from synthetic data
only. They are not captured from a real Gmail account.

## Package

Submit `focused-mail-0.10.0-webstore.zip`, generated from:

```sh
zip -q focused-mail-0.10.0-webstore.zip manifest.json content.css content.js options.html options.js icons/icon16.png icons/icon48.png icons/icon128.png LICENSE PRIVACY.md
```
