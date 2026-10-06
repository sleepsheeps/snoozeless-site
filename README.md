# Snoozeless site

Support page and privacy policy for the Snoozeless: Alarm Clock iOS app, served with GitHub Pages at
https://sleepsheeps.github.io/snoozeless-site/

App Store Connect has them as the support URL and the privacy policy URL, and the app links both from
Settings and the paywall (Guideline 3.1.2). `privacy.html` must resolve, or App Store review stops on it.

The privacy policy describes what the app actually does: no data collected, everything on the device,
the only network connection is the App Store for Snoozeless Pro. Permissions: Alarms, Camera (scan and
photo missions), Microphone (the sleep report, only between Start sleeping and the next alarm),
Motion & Fitness (steps), Notifications (bedtime reminder), Photos add-only (Save Image). If the app ever starts using the network, a new permission or a third-party SDK, update
`privacy.html` (and the App Store privacy label) in the same change.

Images come from the app's `scripts/make-icons.mjs` output: `apple-touch-icon.png` and `favicon.png`
are the app icon, `mark.png` is Bell from the splash image.
