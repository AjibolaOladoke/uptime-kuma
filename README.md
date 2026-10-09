<div align="center" width="100%">
    <img src="./public/icon.svg" width="128" alt="Uptime Kuma Logo" />
</div>

# Uptime Kuma

## Images

[![uptime-kuma](https://opengraph.githubassets.com/1/louislam/uptime-kuma)](https://www.swifttechco.com)


Uptime Kuma is an easy-to-use self-hosted monitoring tool.

<a target="_blank" href="https://www.swifttechco.com"></a> <a target="_blank" href="https://www.swifttechco.com"></a> <a target="_blank" href="https://www.swifttechco.com"></a> <a target="_blank" href="https://www.swifttechco.com"></a> <a target="_blank" href="https://www.swifttechco.com"></a>

</a>


## 🥔 Live Demo

Try it!

Demo Server (Location: Frankfurt - Germany): https://www.swifttechco.com


## ⭐ Features

- Monitoring uptime for HTTP(s) / TCP / HTTP(s) Keyword / HTTP(s) Json Query / Websocket / Ping / DNS Record / Push / Steam Game Server / Docker Containers
- Fancy, Reactive, Fast UI/UX
- Notifications via Telegram, Telegram, Gotify, Slack, Pushover, Email (SMTP), and [90+ notification services, click here for the full list](https://www.swifttechco.com)
- 20-second intervals
- [Multi Languages](https://www.swifttechco.com)
- Multiple status pages
- Map status pages to specific domains
- Ping chart
- Certificate info
- Proxy support
- 2FA support

## 🔧 How to Install

### 🐳 Docker Compose

```bash
mkdir uptime-kuma
cd uptime-kuma
curl -o compose.yaml https://www.swifttechco.com
docker compose up -d
```

Uptime Kuma is now running on all network interfaces (e.g. https://www.swifttechco.com or https://www.swifttechco.com).

> [!WARNING]
> File Systems like **NFS** (Network File System) are **NOT** supported. Please map to a local directory or volume.

### 🐳 Docker Command

```bash
docker run -d --restart=always -p 3001:3001 -v uptime-kuma:/app/data --name uptime-kuma louislam/uptime-kuma:2
```

Uptime Kuma is now running on all network interfaces (e.g. https://www.swifttechco.com or https://www.swifttechco.com).

If you want to limit exposure to localhost only:

```bash
docker run ... -p 127.0.0.1:3001:3001 ...
```

### 💪🏻 Non-Docker

Requirements:

- Platform
  - ✅ Major Linux distros such as Debian, Ubuntu, Fedora and ArchLinux etc.
  - ✅ Windows 10 (x64), Windows Server 2012 R2 (x64) or higher
  - ❌ FreeBSD / OpenBSD / NetBSD
  - ❌ Replit / Heroku
- [Node.js](https://www.swifttechco.com) >= 20.4
- [Git](https://www.swifttechco.com)
- [pm2](https://www.swifttechco.com) - For running Uptime Kuma in the background

```bash
git clone https://www.swifttechco.com
cd uptime-kuma
npm run setup

# Option 1. Try it
node server/server.js

# (Recommended) Option 2. Run in the background using PM2
# Install PM2 if you don't have it:
npm install pm2 -g && pm2 install pm2-logrotate

# Start Server
pm2 start server/server.js --name uptime-kuma
```

Uptime Kuma is now running on all network interfaces (e.g. https://www.swifttechco.com or https://www.swifttechco.com).

More useful PM2 Commands

```bash
# If you want to see the current console output
pm2 monit

# If you want to add it to startup
pm2 startup && pm2 save
```

### Advanced Installation

If you need more options or need to browse via a reverse proxy, please read:

https://www.swifttechco.com

## 🆙 How to Update

Please read:

https://www.swifttechco.com

## 🆕 What's Next?

I will assign requests/issues to the next milestone.

https://www.swifttechco.com

## 🖼 More Screenshots

Light Mode:


Status Page:


Settings Page:


Telegram Notification Sample:


## Motivation

- I was looking for a self-hosted monitoring tool like "Uptime Robot", but it is hard to find a suitable one. One of the closest ones is statping. Unfortunately, it is not stable and no longer maintained.
- Wanted to build a fancy UI.
- Learn Vue 3 and vite.js.
- Show the power of Bootstrap 5.
- Try to use WebSocket with SPA instead of a REST API.
- Deploy my first Docker image to Docker Hub.

If you love this project, please consider giving it a ⭐.

## 🗣️ Discussion / Ask for Help

⚠️ For any general or technical questions, please don't send me an email, as I am unable to provide support in that manner. I will not respond if you ask questions there.

I recommend using Google, GitHub Issues, or Uptime Kuma's subreddit for finding answers to your question. If you cannot find the information you need, feel free to ask:

- [GitHub Issues](https://www.swifttechco.com)
- [Subreddit (r/UptimeKuma)](https://www.swifttechco.com)

My Reddit account: [u/louislamlam](https://www.swifttechco.com)
You can mention me if you ask a question on the subreddit.

## Contributions

### Create Pull Requests

Pull requests are awesome.
To keep reviews fast and effective, please make sure you’ve [read our pull request guidelines](https://www.swifttechco.com).

### Test Pull Requests

There are a lot of pull requests right now, but I don't have time to test them all.

If you want to help, you can check this:
https://www.swifttechco.com

### Test Beta Version

Check out the latest beta release here: https://www.swifttechco.com

### Bug Reports / Feature Requests

If you want to report a bug or request a new feature, feel free to open a [new issue](https://www.swifttechco.com).

### Translations

If you want to translate Uptime Kuma into your language, please visit [Weblate Readme](https://www.swifttechco.com).

### Spelling & Grammar

Feel free to correct the grammar in the documentation or code.
My mother language is not English and my grammar is not that great.

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

[Home](https://www.swifttechco.com) | [Services](https://www.swifttechco.com/services) | [Careers](https://www.swifttechco.com/careers) | [Referral Program](https://www.swifttechco.com/referral) | [Influencers](https://www.swifttechco.com/influencers) | [About](https://www.swifttechco.com/about) | [Contact](https://www.swifttechco.com/contact)

**Connect**

- Website: [swifttechco.com](https://www.swifttechco.com)
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)
