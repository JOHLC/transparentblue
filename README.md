# Transparent Blue Theme for Home Assistant

[![HACS Default](https://img.shields.io/badge/HACS-Default-blue.svg)](https://github.com/custom-components/hacs)
![GitHub Downloads](https://img.shields.io/github/downloads/JOHLC/transparentblue/total)
![Maintenance](https://img.shields.io/maintenance/yes/2026)
![GitHub Release Date](https://img.shields.io/github/release-date/JOHLC/transparentblue)
![GitHub Release](https://img.shields.io/github/v/release/JOHLC/transparentblue)
![GitHub Stars](https://img.shields.io/github/stars/JOHLC/transparentblue?style=social)

---

## Overview

**Transparent Blue** is a sleek, modern theme for Home Assistant featuring a transparent blue aesthetic.  
It’s my first custom theme for Home Assistant and my first ever GitHub/HACS repository.

- **Report issues:** [GitHub Issues](https://github.com/JOHLC/transparentblue/issues)
- **Community & feedback:** [HA Community Thread](https://community.home-assistant.io/t/transparent-blue-custom-theme/)

---

## Screenshots

| Main | More Info |
|------|-----------|
| <img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/v2023.12.1-1.png" alt="Main Screenshot" width="400"> | <img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/v2023.12.1-4.png" alt="More Info Screenshot" width="300"> |

| Sidebar | Menu |
|---------|------|
| <img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/v2023.12.1-2.png" alt="Sidebar Screenshot" width="400"> | <img src="https://raw.githubusercontent.com/JOHLC/transparentblue/main/images/v2023.12.1-3.png" alt="Menu Screenshot" width="300"> |

[Included background image](https://github.com/JOHLC/transparentblue/blob/main/images/background.jpg)

---

## Quick Start

> **Recommended:** Install via HACS for easiest setup and updates.

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=JOHLC&repository=transparentblue&category=frontend)
1. Open HACS in Home Assistant
2. Go to **Frontend**
3. Click **Add (+)**
4. Search for **Transparent Blue**
5. Click **Download**
6. Select the theme in Home Assistant

---

## Manual Installation (not recommended)

1. Download `transparentblue.yaml` from the [latest release](https://github.com/JOHLC/transparentblue/releases).
2. Upload to your `themes` directory.
3. Add the resource reference to your Lovelace config.
4. Select the theme in Home Assistant.

---

## Customizing the Background

To change your background, edit this line in your `.yaml`:

```
lovelace-background: 'center / cover no-repeat fixed url("")'
```

**With local or remote image:**
```
lovelace-background: 'center / cover no-repeat fixed url("/local/background.png")'
# or
lovelace-background: 'center / cover no-repeat fixed url("https://example.com/background.jpg")'
```

**With base64:**
```
lovelace-background: 'center / cover no-repeat fixed url("data:image/png;base64,YOURLONGSTRING")'
```
---

## Beta Versions

Beta releases may be available for testing.  
Enable/disable beta versions in HACS via **Show beta versions** setting.

<img src="https://github.com/JOHLC/transparentblue/blob/main/images/hacsbeta.png?raw=true" alt="HACS Beta Setting" width="400">

---

## Compatibility

Tested on Home Assistant 2023.x and newer.

---

## Contributing

We welcome contributions to improve the Transparent Blue theme! Please read our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before submitting pull requests.

### How to Contribute
- Report bugs via [GitHub Issues](https://github.com/JOHLC/transparentblue/issues)
- Suggest features via [Feature Requests](https://github.com/JOHLC/transparentblue/issues/new/choose)
- Submit improvements via [Pull Requests](https://github.com/JOHLC/transparentblue/pulls)

---

## Support

- **Issues & Bug Reports**: [GitHub Issues](https://github.com/JOHLC/transparentblue/issues)
- **Community Discussion**: [Home Assistant Community](https://community.home-assistant.io/t/transparent-blue-custom-theme/)
- **Documentation**: This README and inline comments in the theme file

---

## License

This theme is released under the [MIT License](LICENSE). Feel free to use, modify, and distribute as per the license terms.

---

## Other Cool Themes

- [3ative Blue Theme](https://github.com/3ative/3ative-blue-theme)
- [Clear Theme Dark](https://github.com/naofireblade/clear-theme-dark)

---

## Acknowledgments

- Thanks to the Home Assistant community for feedback and testing
- Inspired by various blue themes in the Home Assistant ecosystem

---

> _PRs, suggestions, and feedback are always welcome!_
