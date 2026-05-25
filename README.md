# RavenHawk Category Showcase

Custom WordPress plugin that replaces plain category links with a styled, responsive category showcase.

This repository contains the standalone RavenHawk Category Showcase plugin source, update manifest, release package location, and repository documentation for RavenHawkTech.

---

## Current Version

**v2.1.0**

---

## Features

- Responsive category card showcase
- Shortcode support
- Optional automatic insertion on the assigned WordPress Posts page
- Category descriptions and post counts
- RavenHawkTech admin menu grouping
- Editable color and border-radius controls in WordPress Admin
- GitHub manifest-based update metadata

---

## Shortcode

```text
[ravenhawk_category_showcase]
```

Example:

```text
[ravenhawk_category_showcase limit="8" show_counts="true" show_descriptions="true"]
```

---

## Admin Settings

Open:

```text
RavenHawkTech → Category Showcase
```

Settings include:

- Auto-add to blog page
- Accent colors
- Background colors
- Card colors
- Text colors
- Border radius controls

---

## Repository Structure

```text
/
├─ README.md
├─ SECURITY.md
├─ COPYRIGHT.md
├─ .gitignore
├─ plugins/
│  └─ ravenhawk-category-showcase/
│     ├─ ravenhawk-category-showcase.php
│     ├─ README.md
│     └─ assets/
│        ├─ ravenhawk-category-showcase.css
│        ├─ rht-admin-icon.png
│        ├─ rht-admin-icon-128.png
│        ├─ rht-admin-menu-icon.png
│        └─ rht-admin-heading-icon.png
├─ releases/
│  └─ ravenhawk-category-showcase-2.1.0-editable-colors.zip
└─ updates/
   └─ ravenhawk-category-showcase.json
```

---

## Installation

1. Download the plugin ZIP from the latest release.
2. Log in to **WordPress Admin**.
3. Go to **Plugins → Add Plugin**.
4. Click **Upload Plugin**.
5. Choose the RavenHawk Category Showcase ZIP.
6. Click **Install Now**.
7. Activate the plugin.
8. Open **RavenHawkTech → Category Showcase** in WordPress Admin.

---

## RavenHawkTech

Website: https://ravenhawktech.com

---

## License

GPL-3.0 unless otherwise noted.
