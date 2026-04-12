---
layout: default
title: Support
description: Support, FAQs, and contact information for the Core ML Models iOS app.
permalink: /support.html
---

# Support

Thanks for using **Core ML Models**. If something isn't working or you have a question, this page should help.

## Contact

- **Email:** [rockyshikoku@gmail.com](mailto:rockyshikoku@gmail.com)
- **GitHub Issues (public):** [github.com/john-rocky/CoreML-Models/issues](https://github.com/john-rocky/CoreML-Models/issues)

When reporting a problem, please include:

1. Device model (e.g., iPhone 15 Pro, iPad M2)
2. iOS / iPadOS version
3. App version (Settings → About in the app)
4. The model you were running
5. A short description of what you expected vs. what happened

---

## Frequently asked questions

### What is this app?

A model zoo. You browse a catalog of open-source AI models that have been converted to Apple's Core ML format, download the ones you're interested in, and run them on your device.

### Does it need an internet connection?

Only to fetch the catalog and to download model files the first time. Once a model is installed, it runs **fully offline**.

### Why is a model so large / why is the download slow?

Modern AI models are big. A small language model is typically 1–3 GB; an image generator can be 2–5 GB. Download speed depends on the remote host and your network — most files are served from Hugging Face.

### The app says "not enough memory" or crashes during inference.

Some models (large language models, diffusion models, Swin-based transformers) need **≥ 6 GB of device RAM**. On older iPhones and iPads these models may fail to load or run. Try a smaller model from the catalog, close other apps, or restart the device.

### The Neural Engine seems slow on my device.

A few models are intentionally configured to run on **CPU only** or **CPU + GPU** because of known issues with the Neural Engine (e.g., MPS slice bugs on singleton dimensions, or FP16 attention overflow on Swin / DiT architectures). This is a correctness trade-off, not a bug.

### Where are the models stored?

Under the app's own **Application Support** directory. Uninstalling the app removes everything. You can also delete individual models from the app's settings screen.

### Is my data sent anywhere?

No. All inference runs on-device. See the [Privacy Policy](./privacy.html) for details.

### Can I use the outputs commercially?

That depends on the **license of each model**. Every model's detail screen links to the original repository and license. It is your responsibility to comply with them.

### Can you add model X?

Open a GitHub issue with a link to the upstream repository. Conversion scripts are public — pull requests are welcome.

### Is there an Android / macOS version?

The app targets iPhone and iPad. macOS compatibility via "Designed for iPad" may work but is not officially supported. Android is not on the roadmap.

---

## Reporting a bug or vulnerability

For security-sensitive reports, please email us directly rather than filing a public issue.

---

[← Back to home](./)
