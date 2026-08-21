# RavenHawk Category Showcase

Custom WordPress plugin that replaces plain category links with a styled, responsive category showcase.

This repository contains the RavenHawk Category Showcase plugin package, update manifest, and repository documentation for RavenHawkTech.

## Current Version

**v2.1.0**

## Features

- Responsive category card showcase
- Shortcode support
- Optional automatic insertion on the assigned WordPress Posts page
- Category descriptions and post counts
- RavenHawkTech admin menu grouping
- Editable color and border-radius controls in WordPress Admin
- GitHub manifest-based update metadata

## Shortcode

```text
[ravenhawk_category_showcase]
```

Example:

```text
[ravenhawk_category_showcase limit="8" show_counts="true" show_descriptions="true"]
```

## Admin Settings

Open:

```text
RavenHawkTech → Category Showcase
```

Settings include auto-add to blog page, accent colors, background colors, card colors, text colors, and border radius controls.

## Repository Structure

This repository tracks the plugin package instead of the extracted plugin source files.

```text
/
├─ README.md
├─ SECURITY.md
├─ COPYRIGHT.md
├─ .gitignore
├─ releases/
│  └─ ravenhawk-category-showcase.zip
└─ updates/
   └─ ravenhawk-category-showcase.json
```

The package contains the full WordPress plugin folder, including the plugin PHP file, CSS, admin icon assets, and plugin README.

## Installation

1. In WordPress Admin, go to **Plugins → Add Plugin**.
2. Click **Upload Plugin**.
3. Choose the RavenHawk Category Showcase package.
4. Click **Install Now**.
5. Activate the plugin.
6. Open **RavenHawkTech → Category Showcase** in WordPress Admin.

---

## Support RavenHawkTech

<a href="https://www.buymeacoffee.com/wbakke7496c" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" style="height: 60px !important;width: 217px !important;" ></a>

---

## RavenHawkTech

Website: https://ravenhawktech.com

## License

GPL-3.0 unless otherwise noted.
