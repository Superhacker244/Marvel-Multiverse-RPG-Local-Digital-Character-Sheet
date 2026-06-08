# Marvel Multiverse RPG Local Digital Character Sheet

A free, browser-based, offline character sheet and library editor for the Marvel Multiverse Role-Playing Game.

## Description

The Marvel Multiverse RPG Local Digital Character Sheet is a lightweight, client-side application designed to simplify character creation and management. Everything runs locally in your web browser.

No accounts. No subscription. No internet connection (after downloading). 

The project is designed to be flexible and homebrew-friendly by separating the application from its game data. Character libraries are stored as JSON files, allowing users to customize, create, and share their own content while keeping the application itself independent of any specific rules library.

## Features

- Single-file HTML application with no installation required
- Runs entirely offline after downloading
- Comprehensive character creation and management
- Automatic character statistic calculations
- Built-in 616 dice roller with Edge and Trouble support
- Automatic prerequisite validation
- Searchable power database
- Import and export custom JSON libraries
- Full homebrew support through editable libraries
- Included library editor for creating and maintaining custom content
- Custom notes for powers, traits, equipment, and other character features
- Equipment, Weapon, and Battle Suit management with automatic character adjustments
- Support for Origins, Occupations, Traits, Tags, Powers, Weapons, Items, Battle Suits, and more
- Character import and export support
- Fast local performance with no accounts, subscriptions, or cloud services

## How to Use

### Getting Started

1. Download `MMRPGDigitalCharacterSheet.html`.
2. Open it in a modern web browser.
3. Import one or more character libraries (`.json` files) containing Origins, Occupations, Traits, Tags, Powers, Items, Weapons, and other game data.

This repository doesn't contain the full, comprehensive library to avoid distributing copyrighted game content. However, there is a `sampleLibrary.json` which contains elements from the Basic Free Rules.

### Obtaining a Library

There are several ways to obtain a compatible library:

1. Import a library created by another user.
2. Use `sampleLibrary.json`, which contains content from the Marvel Multiverse RPG Free Basic Rules.
3. Create your own library using `MMRPGDigitalLibraryEditor.html`.

### Saving Characters

Characters can be saved in three different ways:

1. Save as .mar (a small file that requires the library used to create it to be functional)
2. Save as .marvel (a larger file that is self-contained with its library logic and rules)
3. Export as .pdf (using MARRPGP_Character_Sheet_Color_Fillable.pdf as a template, it is autopopulated with your character info)

## Known Issues

* **Linked Powers:** Linked powers currently behave as if they are the same power. They should remain independent, each maintaining their own Concentration and UI state while still applying any linked effects.
* **Health & Focus Controls:** Missing increment/decrement controls with configurable step values for quickly adjusting Health and Focus during play.
* **Identity Fields:** Identity text fields lose focus after each character is entered.
* **Thematic Bonus Calculation:** Powers belonging to multiple power sets should automatically use the most appropriate power set when calculating thematic bonuses.
* **Dice Rolls:** Starting a new roll should automatically replace the previous result or maintain a small roll history instead of requiring the previous roll to be manually dismissed.
* **Power Ordering:** Allow users to reorder powers within the Powers tab.
* **Combat Actions:** Remove trigger text from Standard and Movement combat actions.
* **Equipment Handling:** Items, Weapons, and Battle Suits should include an Equipped checkbox. Unequipping an item should temporarily remove any bonuses, powers, or modifiers it grants.
* **Iconic Weapons:** Prevent Iconic Weapon stat blocks from appearing in the Common Items & Weapons section.

## Features in Progress

* Custom color themes
* Infections & Possessions
* Full Team Maneuver support
* Stunts
* Narrative Powers

## Contributions

Bug reports, feature requests, and pull requests are welcome.

If you discover a bug, have an idea for improving usability, or would like to contribute additional functionality, please open an issue or submit a pull request.

## Disclaimer

This is an unofficial fan-made project.

It is not affiliated with, endorsed by, sponsored by, or associated with Marvel, Disney, or the publishers of the Marvel Multiverse Role-Playing Game.

Marvel, Marvel Multiverse Role-Playing Game, and all related trademarks are the property of their respective owners.

This repository contains only the original source code for the application. Any game libraries used with the application remain the responsibility of the user.

## Authors

**Super** (Project Designer & Maintainer)

GitHub: 
https://github.com/Superhacker244

Reddit:
https://www.reddit.com/user/Superhacker244/

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

Special thanks to the Marvel Multiverse RPG community and the many creators who have developed fan-made digital tools and resources over the years. Their projects helped demonstrate what was possible and provided inspiration for this project.


Development Note: This project was developed using AI-assisted programming tools under the direction of the project author. All design decisions, feature planning, testing, and project integration were performed by the maintainer.
