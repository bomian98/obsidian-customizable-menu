# Obsidian Hide Commands in Menus

This plugin allows you to hide any commands, including those of community plugins.

## Prerequisite

Before using this plugin, ensure you have disable "Native menus" in Obsidian's Appearance settings!

## Hide Commands

You can customize to hide any commands across various interface menus in Obsidian through configuration.

There are some differentiators from kzhovn's [obsidian-customizable-menu](https://github.com/kzhovn/obsidian-customizable-menu):

1. Hiding commands across multiple menus - This plugin allows you to hide commands across various interface menus in Obsidian, including file-menu, files-menu, editor-menu, and url-menu.
2. Intelligent Separator Management - Command hiding operations automatically trigger an intelligent cleanup mechanism for redundant separators.
3. Structured Rule Configuration - Utilizes line-by-line entry format instead of comma separation, significantly improving rule readability.

If you would like to style the listed commands yourself, instead of simply removing them, the selector is `div.custom-menu-hide-item`. And if you want to style the hiding separators, the selector is `div.custom-menu-hide-separator`.

## Development Roadmap

- [ ] Develop hide commands across multiple menus.
  - [x] file-menu
    - [x] tab-header position
    - [x] more-options position
    - [x] file-explorer position
  - [ ] files-menu
  - [x] editor-menu
  - [ ] url-menu
- [x] Hide redundant menu separators when all enclosed commands are hidden for cleaner UI.
- [ ] Regex support.

## Thanks

This plugin was initially a fork of kzhovn's excellent [obsidian-customizable-menu](https://github.com/kzhovn/obsidian-customizable-menu).
