# Abatab Privacy Policy

Last updated: October 28, 2026

Abatab is a browser extension developed by SaurusLex. It counts open tabs and windows, shows tab counts grouped by website, and lets you customize the toolbar counter.

## Information processed on your device

Abatab queries Chrome's tab and window metadata to calculate tab and window counts and identify which tabs belong to each window. It uses the URLs of open tabs to extract website domains for the Stats view. Chrome's tab metadata can also contain information such as page titles; Abatab does not use titles in its statistics or save them.

These calculations take place locally in your browser. Domain statistics are recalculated from the open tabs when the popup loads or you change the Stats scope. URLs and domain statistics are not written to persistent storage. Abatab does not read Chrome's history database or build a record of past website visits.

Abatab does not read webpage bodies, forms, passwords, cookies, or personal messages. It does not inject content scripts into websites.

## Settings stored locally

Abatab uses Chrome's extension-specific local storage (`chrome.storage.local`) to remember only these preferences:

- Whether the toolbar badge counts tabs in the current window or all windows.
- Whether the Stats view includes the current window or all windows.
- The selected badge color.

The extension does not use `chrome.storage.sync` to synchronize these settings between devices.

## How information is used

Tab and window metadata is used only to provide the counts, domain grouping, and toolbar badge that you see in Abatab. Saved preferences are used only to apply your selected options.

Abatab does not use this information for advertising, profiling, credit decisions, or unrelated purposes.

## Transmission, sharing, and analytics

The extension does not send tab URLs, domain statistics, counts, or preferences to the developer or to third parties. It contains no analytics, advertising, or telemetry services and does not require an Abatab account.

Abatab does not sell or transfer the information it processes. It does not load or execute remotely hosted code. This policy describes the extension itself; Chrome, Chrome Web Store, and any third-party website you choose to open operate under their own privacy policies.

## Permissions

- **tabs:** provides access to tab URLs so Abatab can group open tabs by domain in the Stats view. Abatab also uses Chrome's tab and window APIs to calculate counts and update the toolbar badge as tabs and windows change.
- **storage:** saves the three local preferences described above.

## Retention and removal

Abatab does not persist tab URLs, domain statistics, or a browsing history. Its saved preferences remain in the extension's local browser storage until that storage is cleared or the extension is removed. Closing the popup, restarting Chrome, or disabling Abatab does not by itself delete those preferences. Removing the extension clears its Chrome local storage.

You can change the preferences in Abatab's popup. Disabling or removing the extension stops its processing while it is disabled or removed. Because the extension does not transmit this information to the developer, there is no developer-held copy of your tab data to delete.

## Contact

For questions about Abatab's privacy practices, contact SaurusLex at [costinalex12@gmail.com](mailto:costinalex12@gmail.com).

If you choose to email the developer, your email address, message, and any information you voluntarily provide will be received through the developer's email service and used to respond to your request. This correspondence is separate from the extension's local storage; sending an email does not give the developer access to your open tabs or saved preferences.
