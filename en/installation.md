# Install and connect

## Install the app

[**Install the PostNL app for Homey (test version)**](https://homey.app/a/nl.lrvdlinden.postnl/test/)

This link installs the test version, which may be newer than the regular App Store release.

## Requirements

- A compatible Homey running version 12.3.0 or later. The app targets the local Homey platform.
- A PostNL account with mail and/or parcels available.
- Chrome with the PostNL Chrome Login Helper to capture the sign-in callback. Download the helper below. Additional setup instructions are available in the community topic.

## Download the Login Helper

[**Download the PostNL Homey Login Helper here**](https://lrvdlinden.app/Extentions/PostNL-Homey-Login-Helper.zip)

Extract the ZIP file before installing the extension in Chrome.

## Add an account

1. [Install the PostNL test version](https://homey.app/a/nl.lrvdlinden.postnl/test/) on your Homey.
2. In Homey, choose **Add Device → PostNL → My PostNL**.
3. Copy or open the PostNL sign-in URL shown in the pairing screen.
4. Open this URL in Chrome and sign in to PostNL.
5. Use the Chrome Login Helper to copy the full callback URL, starting with `postnl://login?code=…`.
6. Paste it into **Callback URL** and complete account pairing.
7. Wait for the first synchronization and check the device.

Use the sign-in URL from the same pairing session. Start again if the authorization code has expired.

## Multiple accounts and reconnecting

Accounts are managed per device. Add another My PostNL device for another account. Use **Repair** on the affected device when its sign-in expires. General app settings point you to this device-specific process.

The first successful synchronization establishes a baseline: existing mail and parcels are not all announced as new.

[Homey App Store](https://homey.app/nl-nl/app/nl.lrvdlinden.postnl/PostNL/) · [Login Helper & support](https://community.homey.app/t/app-pro-postnl-for-homey/159674)
