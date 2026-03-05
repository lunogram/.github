<br />
<div align="center">
  <a href="https://lunogram.com" target="_blank">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://lunogram.com/logos/logo-white-512.png">
        <img src="https://lunogram.com/logos/logo-dark-512.png" width="360" alt="Lunogram"/>
    </picture>
  </a>
</div>

<h3 align="center">Multi-Channel Communication Automation Platform</h3>

<p align="center">Engage your customers through effortless communication.</p>

<p align="center">
  <a href="https://lunogram.com">Website</a> &bull;
  <a href="https://docs.lunogram.com">Documentation</a> &bull;
  <a href="https://github.com/lunogram/platform/discussions">Discussions</a>
</p>

---

### What is Lunogram?

Lunogram is an open-source multi-channel outreach platform that lets you send data-driven emails, SMS, push notifications, and more. Build complex user journeys, create dynamic segments, and connect to your applications using our SDKs and APIs.

### Key Features

- **Cross-Channel Messaging** &mdash; Emails, push notifications, and text messages driven by your data
- **Journeys** &mdash; Drag-and-drop builder for scheduling, triggering, and segmenting users
- **Segmentation** &mdash; Dynamic lists targeting users by event or profile criteria in real time
- **Campaigns** &mdash; Target specific user lists at pre-defined times
- **Integrations** &mdash; SDKs and APIs to connect Lunogram to your stack
- **Secure by Default** &mdash; SSO (SAML/OpenID) out of the box
- **Self-Hostable** &mdash; Run it in your own cloud with Docker

### Quick Start

```bash
git clone https://github.com/lunogram/platform.git
cd platform
docker compose up -d
```

Then visit `http://localhost:8080` to get started. See the **[full documentation](https://docs.lunogram.com)** for deployment guides and configuration options.

### Repositories

| Repository | Description |
|---|---|
| [platform](https://github.com/lunogram/platform) | Core platform &mdash; API, web UI, workers |
| [js-sdk](https://github.com/lunogram/js-sdk) | JavaScript/TypeScript SDK for client integration |
| [website](https://github.com/lunogram/website) | lunogram.com website |

### Contributing

We welcome contributions! Check out the [Contributing Guide](https://github.com/lunogram/platform/blob/main/CONTRIBUTING.md) and join our [GitHub Discussions](https://github.com/lunogram/platform/discussions) to connect with the community.

### Acknowledgments

Lunogram is a fork of [Parcelvoy](https://github.com/parcelvoy/platform), an open-source customer engagement platform. We're grateful to the Parcelvoy team for their foundational work and are committed to continuing the project's development.
