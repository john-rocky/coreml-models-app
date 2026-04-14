---
layout: default
title: Privacy Policy
description: Privacy Policy for the Model Zoo iOS app.
permalink: /privacy.html
---

# Privacy Policy

_Last updated: April 14, 2026_

This Privacy Policy describes how the **Model Zoo** iOS app ("the App", "we", "us") handles information when you use it. The App is developed and maintained by Daisuke Majima.

## Summary

- The App **does not collect, transmit, or share any personal data.**
- All model inference runs **locally on your device**.
- The App downloads model files anonymously over HTTPS from public storage.
- There are no analytics SDKs, no advertising SDKs, and no user accounts.

## 1. Information We Do Not Collect

We do not collect, store, or transmit any of the following:

- Personal identifiers (name, email, phone number, device ID, advertising ID)
- Location data
- Contacts, calendars, or health data
- Usage analytics, crash reports, or telemetry
- The content of any prompt, image, video, or audio you provide to a model

## 2. Data Processed On-Device Only

The App lets you run machine-learning models on data you provide (text, photos, audio, video). All of this processing happens **on your device**. Inputs and outputs are never sent to us or to any third party.

## 3. Camera, Microphone, and Photo Library Access

Some model demos require access to the camera, microphone, or photo library. These permissions are:

- **Requested only when you activate a demo that needs them.**
- **Used solely to supply input to an on-device model.**
- **Never uploaded, shared, or stored outside your device** by the App. (Photos and videos you export to your Photo Library are saved only at your explicit request.)

You can revoke any of these permissions at any time in iOS Settings → Privacy & Security.

## 4. Network Requests

The App makes network requests only to:

- Fetch the public **model catalog** (a JSON manifest listing available models).
- **Download model weights** (`.mlpackage` archives) you explicitly choose to install.

These requests are anonymous HTTPS requests. The remote hosts (Hugging Face, GitHub, Google Drive, etc.) may log standard request metadata (IP address, User-Agent) as part of normal web-server operation. We do not operate these servers and do not receive those logs.

## 5. Third-Party Models and Licenses

Each model in the catalog is an open-source release governed by its own license (Apache 2.0, MIT, CC-BY, etc.). Links to the original repositories and licenses are shown inside the App on each model's detail screen. You are responsible for complying with a model's license when you use its outputs.

## 6. Children's Privacy

The App is rated 4+ and does not knowingly collect data from anyone, including children.

## 7. Changes to This Policy

If this policy changes, the updated version will be published at this URL with a new "Last updated" date. Material changes will also be noted in the App's release notes.

## 8. Contact

For privacy questions or requests, please contact:

- Email: [rockyshikoku@gmail.com](mailto:rockyshikoku@gmail.com)
- GitHub Issues: [github.com/john-rocky/CoreML-Models/issues](https://github.com/john-rocky/CoreML-Models/issues)

---

[← Back to home](./)
