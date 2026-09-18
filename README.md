# Play Store Beta Converter

A clean and fast web tool to instantly convert standard Google Play Store links or Android package IDs into direct beta testing enrolment URLs.

---

## What It Does

When developers run open or closed beta tests on Google Play, users often need to visit the dedicated opt-in landing page (`https://play.google.com/apps/testing/<package_name>`) rather than the regular store listing.

This tool automatically detects and extracts the package name from any Play Store URL, market link, or package ID and generates the direct testing link in real time.

---

## Key Features

- **Instant Auto-Conversion**: Paste or type any link or package ID to immediately generate the beta enrolment URL—no form submissions or extra clicks required.
- **Flexible Input Support**: Recognizes various formats including:
  - Standard store URLs (`https://play.google.com/store/apps/details?id=...`)
  - Market intent links (`market://details?id=...`)
  - Direct reverse-domain package names (e.g., `com.google.android.youtube`)
- **One-Click Copy & Open**: Quickly copy the generated URL to your clipboard or open it directly in a new browser tab.
- **On-Screen QR Code**: Generates a custom QR code on demand, allowing you to scan and open the testing page directly with an Android camera or scanner.
- **Responsive Design**: Carefully calibrated layouts and typography tailored for both mobile devices and wide desktop displays.
- **Error Detection**: Validates inputs in real time and provides helpful guidance if an invalid URL or package ID is entered.

---

## How to Use

1. Paste a Google Play Store URL or type an Android package name into the input field.
2. The converted beta link appears instantly below.
3. Click **Copy Link** to save it, **Open** to visit the page, or **QR Code** to scan it from your mobile device.