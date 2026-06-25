# WhatsApp Baileys

<p align="center">
    <img src="https://t2.pixhost.to/thumbs/8868/742823214_1001152425.jpg" width="300"/>
    <br>
    <b>Pustaka Bot WhatsApp</b><br>
    Wrapper Baileys berkinerja tinggi untuk otomatisasi bot WhatsApp kalian
</p>

# Overview

WhatsApp Baileys adalah library open source berbasis Baileys yang telah dimodifikasi untuk kebutuhan automation dan integrasi WhatsApp skala besar.

Dirancang agar ringan, cepat, dan mudah digunakan, serta mendukung berbagai fitur terbaru dari WhatsApp bot.

---

## Features

### Core Features

- Multi Device Support
- Pairing Code Authentication
- QR Authentication
- Interactive Message
- Native Flow Message
- Carousel Message
- Button Message
- List Message
- Poll Message
- Event Message
- Product Message
- Payment Request Message
- Newsletter Support
- Group Management
- Chat Management
- Contact Management

### Media Features

- Image Message
- Video Message
- Audio Message
- Voice Note Message
- Sticker Message
- Document Message
- Album Message
- Media Downloader
- Media Uploader
- Media Converter

### Toolkit

- Media Resolver
- Buffer Fetcher
- File Uploader
- URL Resolver
- MP4 Preview Generator
- Image Resizer
- Promise Resolver
- Helper Utilities

### Builder

- Button Builder
- Carousel Builder
- Native Flow Builder
- Interactive Builder
- Message Builder

## Installation

### Clone Repository

```bash
git clone https://github.com/BudidiawanXTenka/baileys.git
cd baileys
```

### Install Dependencies

```bash
npm install
```

### Run Project

```bash
npm start
```

## Example

```js
sock.ev.on('messages.upsert', async ({ messages }) => {
  const msg = messages[0]

  if (msg.message?.conversation === 'ping') {
    await sock.sendMessage(msg.key.remoteJid, {
      text: 'pong'
    })
  }
})
```

## Requirements

- Node.js 20+
- npm atau pnpm
- WhatsApp Multi Device

## Project Structure

```text
.
├── lib/
├── WAProto/
├── package.json
├── README.md
└── index.js
```

## Contributing

Pull Request dan Issue sangat diterima untuk membantu pengembangan project ini.

## License

MIT License

## Credits

- Baileys Team
- Open Source Contributors
- BudidiawanXTenka

# Installation

npm install BudidiawanXTenka/baileys

---
