# Local Theme

A collection of custom UI tweaks and browser mods for Zen Browser, bundled together as a local theme package.

This project combines several small CSS-based enhancements into a single theme setup, making it easy to install, customize, and maintain. The layout includes a root theme config plus multiple modular theme add-ons stored in the `local-themes` and `user-content` directories.

## Included tweaks

- Better Compact Toolbar
- Hide Translation button
- Hide Unpinned Extensions
- Bookmark Toolbar Tweaks
- Clean Workspace UI
- Compact RTL Bookmark Toolbar
- No PiP Controls

## Project structure

- `theme.json` — metadata for the local theme package
- `preferences.json` — theme preference definitions
- `userChrome.css` — imports all Chrome-side theme modules
- `userContent.css` — imports the content-side customizations
- `local-themes/` — browser UI mods and theme modules
- `user-content/` — user content CSS additions

## How it works

The main entry points are the root CSS files:

- `userChrome.css` loads custom browser chrome (toolbar, tabs, UI elements)
- `userContent.css` loads page-level modifications

Each imported module contains a small CSS file and, where applicable, its own documentation and settings.

## Installation

1. Open Zen Browser and use the theme/customization system that supports local browser CSS.
2. Point the browser to the root CSS files in this repo, or copy the relevant files into your local theme directory.
3. Ensure the imported paths in `userChrome.css` and `userContent.css` resolve correctly from your installation location.
4. Reload the browser to apply the changes.

## Notes

- This is a personal/local theme collection intended for customization.
- Some modules are styled for Zen Browser-specific UI and may require updates if browser UI changes.
- Individual modules may include their own README files for specific options and behavior.

## License

This project is shared for personal use and customization. Please respect the original author and theme module licenses if redistributed.
