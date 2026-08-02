# CS2 Skin Radar - Game Script Utility 2026

> **A browser-based Counter-Strike 2 skin deal scanner that compares Skinport listings with Steam reference prices and highlights potential discounts.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/benwestzh4012/cs2-skin-price-radar?style=flat-square)](https://github.com/benwestzh4012/cs2-skin-price-radar)

---

<p align="center">
  <a href="https://benwestzh4012.github.io/cs2-skin-price-radar/">
    <img src="https://img.shields.io/badge/Download-CS2%20Skin%20Radar%20Script-brightgreen?style=for-the-badge" alt="Download CS2 Skin Radar Script">
  </a>
</p>

> **[Download CS2 Skin Radar](https://benwestzh4012.github.io/cs2-skin-price-radar/)**

---

[Download Latest Build](https://benwestzh4012.github.io/cs2-skin-price-radar/)

---

## What It Does

CS2 Skin Radar is a web utility for reviewing Counter-Strike 2 skin listings and finding offers that satisfy chosen price and discount conditions. It reads listing information from Skinport and compares those values with Steam Market prices for reference.

Several controls help narrow the results by discount level, maximum price, item condition, category, and StatTrak availability. Each result can include direct links to its Skinport listing and the corresponding Steam Market page. The hosted version refreshes its data on an approximately three-minute cycle.

---

## Key Capabilities

- Scan Counter-Strike 2 listings for potential skin deals
- Retrieve listing information through the Skinport API
- Use Steam Market prices as comparison references
- Set a minimum acceptable discount
- Set a maximum item price
- Filter by skin condition
- Filter by skin category
- Show or hide StatTrak items
- Open Skinport purchase pages directly
- Open Steam Market reference pages directly
- Deploy the application through GitHub Pages
- Refresh available data every three minutes
- Run with plain HTML, CSS, and JavaScript without front-end dependencies

---

## Getting Started

### Hosted Version

To use the current online build, open:

[Launch CS2 Skin Radar](https://benwestzh4012.github.io/cs2-skin-price-radar/)

After opening the utility, apply the discount, price, condition, category, and StatTrak filters to focus on the listings you want to inspect.

### Local Usage

Run the project from a local web server with these steps:

1. Clone or download the repository.
2. Change into the project directory.
3. Start a local server for the project files.
4. Visit the application in a web browser.

For example:

```bash
git clone https://github.com/benwestzh4012/cs2-skin-price-radar.git
cd REPO
```

The front end is written with vanilla HTML, CSS, and JavaScript. No package manager or dependency installation is needed for these files.

---

## Available Filters

The following controls determine which listings remain visible:

| Option | Purpose |
|---|---|
| Minimum discount | Shows only listings meeting or exceeding the chosen discount |
| Maximum price | Restricts results to items at or below the selected price range |
| Condition | Selects skins according to their wear or condition |
| Category | Limits results to a particular item category |
| StatTrak | Adds or removes StatTrak listings from the results |
| Refresh cycle | Retrieves updated data approximately once every 3 minutes |

The exact controls and selectable values can change when the hosted build is updated.

---

## Technical Details and Compatibility

- **Target game:** Counter-Strike 2
- **Platform:** Web browser
- **Market sources:** Skinport and Steam Market reference prices
- **Implementation:** Vanilla HTML, CSS, and JavaScript
- **Deployment:** GitHub Pages

CS2 Skin Radar is designed for examining and comparing market listings. It does not alter Counter-Strike 2 files and does not add functionality inside the game. Prices, available listings, API responses, and market URLs are controlled by their respective services and may change separately from this project.

---

## Frequently Asked Questions

### What is the quickest way to use CS2 Skin Radar?

Open the hosted build, then choose the filters that describe the listings you want to examine. Alternatively, download or clone the repository and serve it locally.

### When does the scanner refresh its data?

The application is set to update its data at roughly three-minute intervals.

### Which filters are available?

You can configure the minimum discount, maximum price, condition, category, and StatTrak settings to control the results shown.

### Is the interface editable?

Yes. Since the project is made with standard HTML, CSS, and JavaScript, its appearance and filtering logic can be changed directly in the repository.

### What marketplaces does it use?

Listing data comes from Skinport, while Steam Market prices provide the comparison reference. When available, the interface also links directly to both services.

### Are any JavaScript packages required?

No. The front end has no external dependencies and uses vanilla HTML, CSS, and JavaScript.

### Where can I find the current hosted build?

Use the following link to open it:

[Open the Latest Build](https://benwestzh4012.github.io/cs2-skin-price-radar/)

### How can I access the source?

The project files are available in the repository. You can download or clone them for local operation and customization.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
