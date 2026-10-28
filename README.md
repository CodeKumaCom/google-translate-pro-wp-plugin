# Google Translate Pro – WordPress Plugin

Add multilingual support to your WordPress site with smart caching, 100+ languages, and a flexible language switcher.

This plugin translates your content on the fly, stores the results in cache, and serves them instantly on subsequent visits. You can use a free built-in translation provider or connect your own Google Cloud Translation API key.

---

## Key Features

- Support for 100+ languages with native names and flags
- Intelligent caching (database or filesystem) to minimize API usage
- Dual translation providers: free built-in or official Google Cloud API
- Built-in rate limiting and circuit breaker protection
- SEO-friendly with automatic hreflang tags
- Fully customizable language switcher (dropdown, buttons, flags, etc.)
- Exclude specific pages or elements from translation
- Developer-friendly with extensive WordPress hooks and filters
- Clean admin dashboard with cache statistics and one-click cache clear

---

## Download

**Current release: v1.0.0**

[Download the plugin ZIP](https://github.com/CodeKumaCom/google-translate-pro-wp-plugin/releases/latest/download/google-translate-pro-wp-plugin-v1.0.0.zip)

All versions are available on the [Releases page](https://github.com/CodeKumaCom/google-translate-pro-wp-plugin/releases).

---

## Installation

1. Download the ZIP file.
2. In WordPress go to **Plugins → Add New → Upload Plugin**.
3. Select the ZIP and click **Install Now**.
4. Activate the plugin.

After activation, go to **GTranslate** in the WordPress admin menu to configure the plugin.

---

## Quick Start

1. Choose your translation provider (Free or Google Cloud API).
2. Select your source language and the target languages you want to offer.
3. Add the language switcher using the shortcode `[gtranslate_switcher]`, a widget, or by enabling it in the header/footer/menu.
4. Optionally exclude specific pages or CSS selectors from translation.

The plugin will automatically cache translated pages so repeat visitors get fast results.

---

## Language Switcher Options

You can display the switcher in several ways:

- Shortcode: `[gtranslate_switcher]`
- Widget (Appearance → Widgets)
- Automatically in the primary menu
- Header or footer injection
- Custom PHP template code

Style options include dropdown, buttons, flags only, names only, and more.

---

## Settings Overview

The admin panel is organized into clear tabs:

- **General** – Choose provider and basic options
- **Languages** – Select source and target languages
- **Translation** – Control which HTML tags are translated + exclusions
- **Display** – Switcher style, position, and custom CSS
- **Advanced** – Rate limits, cache type, expiry, and debug tools

---

## Requirements

- WordPress 5.8 or higher
- PHP 7.4 or higher

---

## License

This plugin is released under the GPL-2.0-or-later license.

---

## Credits

Uses translation technology compatible with Google Cloud Translation API.
