# aapanel-v7.X-lifetime

> **Unlock All Pro Features & Extensions**  
> Modern, powerful, and fully unlocked aaPanel v7.x series.

---

# Connect Community
Telegram [https://t.me/aapanelcommunity](https://t.me/aapanelcommunity)
Get a 21-day trial of aaPanel Pro now
---

# Instructions
Instructions [https://sum.vn/aapanelprivate](https://sum.vn/aapanelprivate)
---
## 🛸 Beta  Update: v7.54.0

📝 *Changelog:*
1. Added: Simplified Chinese language
2. Added: Server restart alert prompt on the Home
3. Optimized: Improved success rate for enabling Multi-WebServer Hosting  
4. Optimized: Performance issues with SSL deployment in Multi-WebServer Hosting  
5. Fixed: Problem with SSL application failure for Node projects
6. Fixed: Files module incorrectly applies permission changes to subdirectories when not selected


## 🚀 Latest Update: v7.0.27

1. Added: Multi-WebServer Hosting (allows setting a specific WebServer for individual websites)
2. Added: Under Multi-WebServer Hosting, WP Toolkit supports enabling cache for Apache
3. Added: Files module - new features including Copy Path, Open in New Window, and rename when overwriting
4. Added: Adminer to support visual management of MongoDB and PgSQL
5. Added: lsphp management integration in Openlitespeed management
6. Added: Support for batch deletion in Security - Firewall
7. Added: Server restart alert prompt on the Home page  
8. Added: Simplified Chinese language
9. Added: Account supports WHMCS seamless processing of orders, payments, and activations
10. Added: aaPanel app is newly launched (currently available for Android)
11. Optimized: Multi-WebServer Hosting enabled, default environment for "Add WordPress" in WP Toolkit is Nginx + Openlitespeed
12. Optimized: Docker module Overview interface and speed
13. Optimized: Italian and Turkish language translations
14. Optimized: Unified display of SSL application and renewal interfaces
15. Fixed: Issue where hidden files become directories when restoring site files backed up via Cron
16. Fixed: Issue where Vulnerability Scan in WP Toolkit reports errors in certain cases
17. Fixed: Problem with SSL application failure for Node projects
18. Fixed: Problem with PgSQL automatic backup failure
19. Fixed: Known issues in the Files module

---

# Coming Soon: Multi-WebServer Hosting for aaPanel

Customize dedicated web services for each website.

## 🚀 Feature Preview

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

## v7.0.27
- Added: Multi-WebServer Hosting (allows setting a specific WebServer for individual websites)
- Added: Under Multi-WebServer Hosting, WP Toolkit supports enabling cache for Apache
- Added: Files module - new features including Copy Path, Open in New Window, and rename when overwriting
- Added: Adminer to support visual management of MongoDB and PgSQL
- Added: lsphp management integration in Openlitespeed management
- Added: Support for batch deletion in Security - Firewall
- Added: Server restart alert prompt on the Home page  
- Added: Simplified Chinese language
- Added: Account supports WHMCS seamless processing of orders, payments, and activations
- Added: aaPanel app is newly launched (currently available for Android)
- Optimized: Multi-WebServer Hosting enabled, default environment for "Add WordPress" in WP Toolkit is Nginx + Openlitespeed
- Optimized: Docker module Overview interface and speed
- Optimized: Italian and Turkish language translations
- Optimized: Unified display of SSL application and renewal interfaces
- Fixed: Issue where hidden files become directories when restoring site files backed up via Cron
- Fixed: Issue where Vulnerability Scan in WP Toolkit reports errors in certain cases
- Fixed: Problem with SSL application failure for Node projects
- Fixed: Problem with PgSQL automatic backup failure
- Fixed: Known issues in the Files module

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
