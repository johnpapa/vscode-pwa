## VS Code Extension for PWA Tooling

<a name="0.1.0"></a>
# 0.1.0 (2017-06-14)

Bug Fixes
* Fixed typos in the tabs

<a name="0.0.5"></a>
# 0.0.5 (2017-06-13)

Features
* Added pwa-event-push
* Added pwa-event-sync
* Added pwa-event-notificationclick
* Added pwa-event-pushsubscriptionchange
* pwa-event-load
* pwa-event-activate
* pwa-event-install
* pwa-event-fetch

<a name="0.0.3"></a>
# 0.0.3 (2017-06-11)

Features
* Added pwa-manifest, to create a `manifest.json`
* Added pwa-apple-mobile-web-capable to add the meta tag for apple mobile web capable
* Added pwa-generate-service-worker to generate a service worker with a precache manifest
* pwa-register works for both TypeScript and JavaScript
* Renamed HTML snippet to create the link to the manifest.json to pwa-manifest-link
* Renamed pwa-service-worker to pwa-custom-service-worker

Bug Fixes
* pwa-register now has correct placeholder sequence

<a name="0.0.1"></a>
# 0.0.1 (2017-06-10)

* Initilizing the extension
* Added `manifest.json` schema
* Added javascript snippet for precache manifest from worbox-build
* Added javascript snippet to create a service worker ready to accept the precache list from workbox-build
* Added HTML snippet to create the link to the manifest.json
* Added TypeScript snippet to registers the service worker
