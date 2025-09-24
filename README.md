# aapanel-v7.X-lifetime

> **Unlock All Pro Features & Extensions**  
> Modern, powerful, and fully unlocked aaPanel v7.x series.

---

# Connect Community
Telegram [https://t.me/aapanelcommunity](https://t.me/aapanelcommunity)
---

# Instructions
Instructions [https://sum.vn/aapanelprivate](https://sum.vn/aapanelprivate)
---

## 🚀 Latest Update: v7.0.26

- Added: aaPanel account support for Google login  
- Added: Theme mode automatically follows browser settings  
- Added: Support for scheduled backups of MongoDB, Redis, and PgSQL in Cron  
- Added: Reverse proxy support for URL Rewrite (Nginx only)  
- Optimized: Performance of newly installed PHP 8 series improved by 10-30%  
- Optimized: Display of the operation menu in the Files module  
- Optimized: Dark theme compatibility for some interfaces  
- Optimized: Updated Ukrainian language (Thanks to aaP_valdeuscorp)  
- Fixed: Abnormal issues with PgSQL when adding/deleting databases and users  
- Fixed: Issue where terminal cannot be used normally when key and password are empty in some cases
- Fixed: Issue where QR code login fails on some mobile devices when using Dark theme  
- Fixed: Issue where Files module returns to default directory in some cases  
- Fixed: Issue where data backup and migration progress stops  
- Fixed: Issue where Cron automatic backup fails to delete old backups

---

# Coming Soon: Multi-WebServer Hosting for aaPanel

Customize dedicated web services for each website.

## 🚀 Feature Preview - Coming Soon

### New Architecture Overview
We are developing a **Multi-WebServer Hosting** architecture that will allow you to specify the WebEngine for each website individually, providing greater flexibility and control.

---

### Configuration Interface Preview

![Configuration pop-up window](https://www.aapanel.com/static/images/popup.png)

---

### Web Service Management

![Web service management interface](https://www.aapanel.com/static/images/WebsiteSetup.png)

---


## 🛠️ Installation

Get started instantly with the one-liner below.  
Automatically detects `curl` or `wget` and runs the installer.

```bash
URL=https://cloud.hungnh.com/install/install_7.0_en.sh && \
if [ -f /usr/bin/curl ]; then \
  curl -ksSO $URL ; \
else \
  wget -O install_7.0_en.sh $URL; \
fi; \
bash install_7.0_en.sh
```

---

## 🔼 Upgrade

Keep your panel up to date with the latest features and fixes:

```bash
curl https://cloud.hungnh.com/install/update_7.x_en.sh | bash
```

---

## 🧹 Uninstall

Remove aaPanel completely:

```bash
sudo bt stop && \
sudo update-rc.d -f bt remove && \
sudo rm -f /etc/init.d/bt && \
sudo rm -rf /www/server/panel
```

---

## 📖 Documentation & Support

- Full guide, tutorials, and troubleshooting: [cloud.hungnh.com](https://cloud.hungnh.com)
- Maintained by [@vnsur](https://github.com/vnsur)

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=vnsur/aapanel-private-v7-x-lifetime&type=Date)](https://www.star-history.com/#vnsur/aapanel-private-v7-x-lifetime&Date)

---

# 📝 Changelog

## v7.0.26
- Added: aaPanel account support for Google login  
- Added: Theme mode automatically follows browser settings  
- Added: Support for scheduled backups of MongoDB, Redis, and PgSQL in Cron  
- Added: Reverse proxy support for URL Rewrite (Nginx only)  
- Optimized: Performance of newly installed PHP 8 series improved by 10-30%  
- Optimized: Display of the operation menu in the Files module  
- Optimized: Dark theme compatibility for some interfaces  
- Optimized: Updated Ukrainian language (Thanks to aaP_valdeuscorp)  
- Fixed: Abnormal issues with PgSQL when adding/deleting databases and users  
- Fixed: Issue where terminal cannot be used normally when key and password are empty in some cases
- Fixed: Issue where QR code login fails on some mobile devices when using Dark theme  
- Fixed: Issue where Files module returns to default directory in some cases  
- Fixed: Issue where data backup and migration progress stops  
- Fixed: Issue where Cron automatic backup fails to delete old backups
  
## v7.0.25
- Added: aaPanel account support for Google login  
- Added: Theme mode automatically follows browser settings  
- Added: Support for scheduled backups of MongoDB, Redis, and PgSQL in Cron  
- Added: Reverse proxy support for URL Rewrite (Nginx only)  
- Optimized: Performance of newly installed PHP 8 series improved by 10-30%  
- Optimized: Display of the operation menu in the Files module  
- Optimized: Dark theme compatibility for some interfaces  
- Optimized: Updated Ukrainian language (Thanks to aaP_valdeuscorp)  
- Fixed: Abnormal issues with PgSQL when adding/deleting databases and users  
- Fixed: Issue where terminal cannot be used normally when key and password are empty in some cases
- Fixed: Issue where QR code login fails on some mobile devices when using Dark theme  
- Fixed: Issue where Files module returns to default directory in some cases  
- Fixed: Issue where data backup and migration progress stops  
- Fixed: Issue where Cron automatic backup fails to delete old backups

## v7.0.24
- Fixed: "Domain not found" prompt during SSL renewal
- Fixed: Known issues in Files module

## v7.0.23
- Added: Dark theme (Home, top-right corner; plugins may vary)
- Added: Multi-tab support in Files
- Added: Custom logos/backgrounds in Settings
- Added: Maintenance mode for Websites & WP Toolkit
- Added: WP Toolkit: Enable cache for OpenLiteSpeed
- Added: WP Toolkit: Display Debug Log in Response log
- Added: WP Toolkit: Copy themes, plugins, database tables
- Added: WP Toolkit: Debug mode, script debug, save queries, SEO indexing
- Optimized: Redesigned Files module
- Optimized: Faster SSH log retrieval
- Optimized: Improved WP Toolkit structure display and listing
- Optimized: Progress display for create/clone in WP Toolkit
- Optimized: Multi-domain business certificate application
- Optimized: Account model for port modification
- Optimized: Faster database import list retrieval, pagination and search

## v7.0.22
- Added: Fresh theme and theme switching
- Added: Backup and restore in Settings
- Added: Data migration tool
- Added: Categorized WP Toolkit websites
- Added: Manual backup for WP Toolkit creation
- Added: Support for migrating manually deployed WP sites
- Added: Modify website title, home/domain in WP Toolkit
- Added: Security reports and advanced malicious file detection
- Added: Multi-year business certificate renewal
- Optimized: Panel structure, startup, and log management
- Optimized: Visualization and checks for SSL/malicious files
- Fixed: CNAME info, HTTP validation, rare install/init errors

## v7.0.21
- Added: Ukrainian, Korean, Italian, Turkish languages
- Added: New Security interface and WAF 3D Map
- Added: Clamav plugin, CDN Proxy, optimized backups
- Optimized: Firewall, MySQL/MariaDB backups, FTP log analysis
- Optimized: Daemon task reliability
- Fixed: Proxy project/site/alarms addition issues

## v7.0.20
- Added: USDT payment, Russian language, new SSL options
- Added: DNS file verification, panel SSL with file verification
- Added: WP Toolkit DNS auto resolution, FTP log analytics
- Added: Option to skip default HTML for new sites
- Added: Daemon tasks for popular services
- Added: Improved brute force protection
- Optimized: Brute force protection, interface, backup retry
- Fixed: Login, mail server, node project, account confirmation bugs

[...]

_For full changelog, see the [releases](https://github.com/vnsur/aapanel-v7-lifetime/releases) or below._

---

## 💡 Pro Tips

- Always keep your panel updated for best security and features.
- Visit [cloud.hungnh.com](https://cloud.hungnh.com) for advanced usage, automation, and plugin tutorials.
- Star ⭐ this repo to follow updates!

---

**Modern aaPanel management made easy.**
