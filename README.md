# Highlighter Plus for Obsidian

Supercharge your highlighting with unlimited custom colors, underline styles, and smart hotkey toggling for different text scopes.

Highlighter Plus extends Obsidian's default highlighting with a powerful, fully customizable system. Create distinct highlight profiles, tailor them perfectly for both Light and Dark themes, and apply them effortlessly using intuitive syntax or smart hotkeys—all without losing the ability to use the standard built-in highlighter.

## ✨ Key features

* 🎨 **Unlimited custom highlighters:** Create as many unique highlighting styles as you need.
* 🌓 **Light & dark mode ready:** Define separate colors, opacities, and text colors for Light and Dark themes within a single highlighter profile.
* 🖍️ **Highlight or underline:** Choose between a classic background fill or a subtle, customizable underline.
* ⌨️ **Smart hotkey toggling:** Cycle through your active highlighters with a single hotkey. 
* 🎯 **Context-aware scoping:** Assign highlighters to specific contexts (e.g., "All texts", "Only paragraphs", or "Only headers"). Your hotkey will only cycle through the styles relevant to the line you're currently editing!
* ⚙️ **Total visual control:** Fine-tune background opacity (0-100%), custom text colors, and corner radius.
* 🧹 **Clean & safe CSS overrides:** Highlighter Plus uses a "nuclear" CSS specificity approach. It flawlessly applies custom styles, and if you delete a highlighter from your settings, the affected text instantly and safely reverts to normal text.
* 📄 **Export friendly:** Fully compatible with Obsidian's native PDF export as well as third-party PDF exporter plugins.

## 🚀 How to use

### Syntax
Highlighter Plus uses a simple extension of Obsidian's native highlighting syntax:
`==id=Your highlighted text here==`

Where `id` is the short name you assign to your highlighter in the settings.
*Example:* If you create a highlighter named `alert`, you use it like this: `==alert=Pay attention to this!==`

### Using hotkeys (recommended)
1. Select a word or a paragraph.
2. Trigger the **"Toggle Highlighter Cycle"** command (assign a hotkey in Obsidian settings).
3. Press it repeatedly to cycle through your active highlighters. Press it again to remove the highlight completely.

## 🛠️ Settings & management

The plugin settings provide a rich, interactive UI to manage your styles:
* **Reorder:** Use the `↑` and `↓` arrows to change the hotkey cycle order.
* **Duplicate:** Quickly clone an existing profile with the `📄` button.
* **Live preview:** See exactly how your highlight and text colors will look in both Light and Dark modes in real-time.
* **Toggle scope:** Decide if a specific highlighter should be available everywhere, only in standard paragraphs, or exclusively in `# Headers`.

## 📦 Installation

### Manual installation
1. Download the latest release (`main.js` and `manifest.json`) from the [Releases](../../releases) page.
2. Create a folder named `highlighter-plus` inside your vault's `.obsidian/plugins/` directory.
3. Place the downloaded files into this new folder.
4. Reload Obsidian and enable **Highlighter Plus** in your Community Plugins settings.

## ☕ Support development

If you enjoy using Highlighter Plus and it makes your note-taking process better, consider supporting the development!

[![Buy me a coffee](https://img.shields.io/badge/Buy_me_a_coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buycoffee.to/creesee)
