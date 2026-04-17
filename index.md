# Privacy Policy — Fake Book Index
*Last updated: April 2026*

## Data collection
Fake Book Index does not collect, store, or transmit any personal data. The app has no user accounts, no analytics, and no advertising.

## Local storage
The app stores data locally on your device only:
- The jazz standards index (included in the app, updated automatically)
- Your filter preferences
- Your custom book indexes
- Your language preference

This data never leaves your device.

## Internet connection
The app works fully offline once installed. It includes an initial copy of the index and does not require any network access to function.

To keep the index up to date without requiring an app store update, the app performs an automatic background check at most once every 24 hours. This check consists of:

1. A request to `arm3l.github.io/fbi-data/manifest.json` to see if a newer version of the index is available.
2. If yes, a request to `arm3l.github.io/fbi-data/fbi_index.json` to download the updated index.

No personal data is sent during these requests. The server (GitHub Pages) receives standard HTTP metadata such as your IP address and the app version, which are handled according to [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

If your device is offline, the app continues to work with the locally stored index.

## Third party data
- The index is curated and maintained by the developer, and hosted on GitHub Pages.
- It was initially built from [milnak/FakeBookIndex](https://github.com/milnak/FakeBookIndex), distributed under CC0 license (public domain), and has since been extended with additional books and metadata.

## Contact
Questions? armel.courree@gmail.com
