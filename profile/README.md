<p align="center">
  <a href="https://unlimitedmessaging.app?utm_source=github&utm_medium=readme&utm_campaign=org-profile"><img src="https://unlimitedmessaging.app/assets/favicon/android-chrome-512x512.png" width="72" height="72" alt="Unlimited Messaging logo"></a>
</p>

<h1 align="center">Unlimited Messaging</h1>

<p align="center">
  <b>WhatsApp, email and SMS from your own number, mailbox and Android phone, in one API request.</b><br>
  Free plan, unlimited messages, no per-message fees. EU-hosted.
</p>

<p align="center">
  <a href="https://unlimitedmessaging.app?utm_source=github&utm_medium=readme&utm_campaign=org-profile">Website</a> ·
  <a href="https://app.unlimitedmessaging.app?utm_source=github&utm_medium=readme&utm_campaign=org-profile">App</a> ·
  <a href="https://docs.unlimitedmessaging.app">Docs</a> ·
  <a href="https://unlimitedmessaging.app/mcp?utm_source=github&utm_medium=readme&utm_campaign=org-profile">MCP</a> ·
  <a href="https://unlimitedmessaging.app/pricing?utm_source=github&utm_medium=readme&utm_campaign=org-profile">Pricing</a> ·
  <a href="https://status.unlimitedmessaging.app">Status</a> ·
  <a href="https://discord.gg/danrEJV5Xx">Discord</a> ·
  <a href="https://x.com/unlimitedmess">X</a>
</p>

---

### Channels

| Channel | From | How it connects |
| --- | --- | --- |
| **WhatsApp** | Your own number | Linked as a device by QR code. No Meta template approval, no per-message fee. |
| **Email** | Your own mailbox | IMAP/SMTP (Gmail, your own domain). Outlook and Microsoft 365 not supported yet. |
| **SMS** | Your own Android phone | Its SIM, through our [open source Android app](https://github.com/UnlimitedMessaging/unlimited-messaging-android). |

One `POST /message` can go out on all three channels at once. Inbound messages arrive in the app and as webhooks.

### Four ways to use it

1. **MCP server** for Claude, ChatGPT, Cursor, VS Code and any MCP client: `https://mcp.unlimitedmessaging.app` (remote, OAuth 2.1, no API key). Official MCP Registry name: `app.unlimitedmessaging/mcp`. [Setup guide](https://github.com/UnlimitedMessaging/unlimited-messaging-mcp)
2. **REST API and SDKs**: [TypeScript on npm](https://www.npmjs.com/package/@unlimited-messaging/sdk) and [Python on PyPI](https://pypi.org/project/unlimited-messaging). [API docs](https://docs.unlimitedmessaging.app)
3. **n8n**: the [n8n-nodes-unlimited-messaging](https://www.npmjs.com/package/n8n-nodes-unlimited-messaging) community node for no-code workflows.
4. **Web app**: [app.unlimitedmessaging.app](https://app.unlimitedmessaging.app?utm_source=github&utm_medium=readme&utm_campaign=org-profile) to link accounts, send and read messages without code.

### Repositories

| Repository | What it is |
| --- | --- |
| [unlimited-messaging-mcp](https://github.com/UnlimitedMessaging/unlimited-messaging-mcp) | Hosted MCP server: setup per client, tools, ready-to-paste configs, `server.json` |
| [unlimited-messaging-sdk](https://github.com/UnlimitedMessaging/unlimited-messaging-sdk) | OpenAPI spec, official TypeScript and Python SDKs, n8n node source |
| [unlimited-messaging-android](https://github.com/UnlimitedMessaging/unlimited-messaging-android) | Open source Android app that sends and receives SMS from your own phone |

### Pricing

No per-message fees. [Start free, no credit card.](https://app.unlimitedmessaging.app?utm_source=github&utm_medium=readme&utm_campaign=org-profile)

| | Free | Medium 19 EUR/mo | Max 29 EUR/mo |
| :--- | :---: | :---: | :---: |
| Unlimited messages | ✓ | ✓ | ✓ |
| WhatsApp + email + SMS in one request | ✓ | ✓ | ✓ |
| MCP server, API, SDKs, web app | ✓ | ✓ | ✓ |
| Webhook message reception | | ✓ | ✓ |
| WhatsApp media messages | | ✓ | ✓ |
| Templating and dynamic variables | | | ✓ |
| Advanced analytics and Excel export | | | ✓ |
| "Sent with UnlimitedMessaging.app" footer | Free only | | |

Full details on [unlimitedmessaging.app/pricing](https://unlimitedmessaging.app/pricing?utm_source=github&utm_medium=readme&utm_campaign=org-profile).

### Good to know

WhatsApp goes through a linked device on your normal account, not Meta's official Business API: no templates and no per-message fee, but sending spam can get a number banned. Use it for your own conversations and opted-in contacts.

### Team

Built in France by co-founders [Ilian A](https://www.linkedin.com/in/ilianAzz/) and Adrien.

Contact: [contact@unlimitedmessaging.app](mailto:contact@unlimitedmessaging.app) · Community: [Discord](https://discord.gg/danrEJV5Xx) · [Product Hunt](https://www.producthunt.com/products/unlimited-messaging)
