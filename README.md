<p align="center">
  <a href="https://orbitcp.pro">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/images/logo-dark-mode.png">
      <img src="assets/images/logo-light-mode.png" alt="OrbitCP" width="320">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://orbitcp.pro">Website</a> ·
  <a href="https://orbitcp.pro/docs/">Docs</a> ·
  <a href="https://orbitcp.pro/changelog/">Changelog</a> ·
  <a href="https://github.com/orbitcp/orbitcp/issues">Issues</a> ·
  <a href="https://github.com/orbitcp/orbitcp/discussions">Discussions</a> ·
  <a href="https://discord.gg/YAF7We7sg">Discord</a>
</p>

<p align="center">
  <a href="https://discord.gg/YAF7We7sg"><img src="https://img.shields.io/badge/Discord-Join%20the%20community-5865F2?logo=discord&logoColor=white" alt="Join OrbitCP on Discord"></a>
  <a href="https://github.com/orbitcp/orbitcp/releases/latest"><img src="https://img.shields.io/github/v/release/orbitcp/orbitcp?label=release&color=F4B740" alt="Latest release"></a>
</p>

[OrbitCP](https://orbitcp.pro) is a modern server control panel with an AI assistant built in. Run websites,
WordPress, Node.js and Python apps, Docker, databases and backups from one clean screen, and host your own
customers on your VPS.

The AI assistant reads your logs, finds the cause of a problem and proposes a fix. Nothing changes on your server
until you press **Approve**.

<p align="center">
  <img src="assets/images/dashboard-preview.png" alt="The OrbitCP dashboard" width="100%">
</p>

## ✨ Highlights

- **Free plan**, no license key needed
- **AI assistant** that investigates by itself and fixes things only after you approve them
- **Websites and free SSL**: static, PHP and reverse proxy, with certificates that renew themselves
- **Fast WordPress**: page cache that clears itself, Redis object cache, Brotli and browser caching
- **One-click WordPress**, plus **Node.js and Python apps from Git** (Next.js, NestJS, Express, Flask, Django, FastAPI)
- **Docker** with an App Store and your own compose stacks
- **Databases**: MariaDB with phpMyAdmin, PostgreSQL 17 with PostGIS, Redis
- **Client accounts** to host your customers, each in their own isolated Linux user, with packages and limits
- **Security Center**: firewall, brute-force protection, safe SSH settings, web firewall and malware scans
- **Email hosting**: mailboxes on your own domains with webmail, spam filter and DKIM
- **Backups and cron jobs**, file manager and web terminal
- Ready in about **3 minutes**, one command to install and upgrade
- **Ubuntu 22.04, 24.04 and Debian 12**

## 💾 Installation

On a fresh server, as root:

```bash
curl -fsSL https://orbitcp.pro/install.sh | sudo bash
```

The installer prints your private panel link and admin password at the end. Run the same command again to upgrade.

Step-by-step guide: **[orbitcp.pro/docs](https://orbitcp.pro/docs/)**

Works on any VPS or dedicated server: Linode (Akamai), DigitalOcean, Vultr, Hetzner, AWS Lightsail and others.
At least 1 GB of memory; 2 GB or more for Node.js apps and Docker.

## 📦 Plans

| | Free | Pro | Premium |
|---|:---:|:---:|:---:|
| Websites, WordPress, SSL, apps, Docker, databases, backups | ✓ | ✓ | ✓ |
| Security Center | | ✓ | ✓ |
| AI assistant | | ✓ | ✓ |
| Client accounts | | up to 10 | unlimited |
| Node.js, PostgreSQL and Redis for clients | | | ✓ |
| AI credits every month | | | 300 |

Every new install gets a 14-day Premium trial. Plans and prices: **[orbitcp.pro/#pricing](https://orbitcp.pro/#pricing)**

## 🗺️ Roadmap

### Coming next

- [ ] **0.16 · Remote backups**: S3, Backblaze and Google Drive
- [ ] **0.17 · Alerts**: email when a disk fills up, an SSL certificate is about to expire, or a site or service goes down
- [ ] **0.18 · WHMCS module and API keys**: sell hosting with automatic account setup, suspend and one-click login
- [ ] **0.19 · Release candidate**: install and upgrade tests on every supported OS, restore tests, security review
- [ ] **1.0 · Stable release**: no breaking changes in 1.x
- [ ] **1.1 · Reseller accounts**

### Done

- [x] **0.15 · Page cache and speed**: page cache that clears itself, Redis object cache, Brotli, speed test
- [x] **0.14 · Email hosting**: mailboxes, webmail, spam filter, DKIM, DNS checklist, forwarders
- [x] **0.13 · File manager tools**: cut, copy, move, compress and extract
- [x] **0.12 · One-line install** with checksum-verified builds
- [x] **0.11 · Plans, licenses and AI credits**
- [x] **0.10 · AI assistant** that fixes things only after you approve
- [x] **0.9 · Security Center**: firewall, brute-force protection, web firewall, malware scans
- [x] **0.8 · Developer hosting for clients**: Node.js and Python apps, PostgreSQL, Redis
- [x] **0.7 · Client accounts** with packages, limits, PHP manager and SFTP/SSH
- [x] **0.6 · Docker** with an App Store and compose stacks
- [x] **0.5 · Backups and cron jobs**
- [x] **0.4 · One-click WordPress**, Node.js and Python apps from Git
- [x] **0.3 · Databases**: MariaDB and phpMyAdmin
- [x] **0.2 · Websites** with free SSL
- [x] **0.1 · First release**: dashboard, secure sign-in, file manager, web terminal, audit log

Have an idea? Share it in [Discussions](https://github.com/orbitcp/orbitcp/discussions). Full details in the [changelog](https://orbitcp.pro/changelog/).

## 💬 Community and help

- **Chat with other users and the team**: [Discord](https://discord.gg/YAF7We7sg)
- **Questions and ideas**: [GitHub Discussions](https://github.com/orbitcp/orbitcp/discussions)
- **Found a bug?** [Open an issue](https://github.com/orbitcp/orbitcp/issues/new/choose)
- **Security problem?** Please don't open a public issue. See [SECURITY.md](SECURITY.md).
- **Customers**: email [support@orbitcp.pro](mailto:support@orbitcp.pro)

## 💖 Support this project

- Star this repository ⭐
- Tell other people about OrbitCP on X (Twitter), Facebook or LinkedIn
- Write a blog post or make a video about OrbitCP
- Join our [Discord server](https://discord.gg/YAF7We7sg) and help other users
- Share your ideas in [Discussions](https://github.com/orbitcp/orbitcp/discussions)
- Report bugs in [Issues](https://github.com/orbitcp/orbitcp/issues)

---

This repository is OrbitCP's public home for releases, bug reports and ideas. OrbitCP is free to use on the free plan;
see the [Terms of Service](https://orbitcp.pro/terms/).
