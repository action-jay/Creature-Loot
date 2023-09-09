# Creature Loot Crafting & Gathering

![Latest Release Download Count](https://img.shields.io/github/downloads/p4535992/foundryvtt-creature-loot-crafting-and-gathering/latest/module.zip?color=2b82fc&label=DOWNLOADS&style=for-the-badge)

[![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fcreature-loot-crafting-and-gathering&colorB=006400&style=for-the-badge)](https://forge-vtt.com/bazaar#package=creature-loot-crafting-and-gathering)

![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fp4535992%2Ffoundryvtt-creature-loot-crafting-and-gathering%2Fmaster%2Fmodule.json&label=Foundry%20Version&query=$.compatibleCoreVersion&colorB=orange&style=for-the-badge)

![Latest Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fp4535992%2Ffoundryvtt-creature-loot-crafting-and-gathering%2Fmaster%2Fmodule.json&label=Latest%20Release&prefix=v&query=$.version&colorB=red&style=for-the-badge)

[![Foundry Hub Endorsements](https://img.shields.io/endpoint?logoColor=white&url=https%3A%2F%2Fwww.foundryvtt-hub.com%2Fwp-json%2Fhubapi%2Fv1%2Fpackage%2Fcreature-loot-crafting-and-gathering%2Fshield%2Fendorsements&style=for-the-badge)](https://www.foundryvtt-hub.com/package/creature-loot-crafting-and-gathering/)

![GitHub all releases](https://img.shields.io/github/downloads/p4535992/foundryvtt-creature-loot-crafting-and-gathering/total?style=for-the-badge)

[![Translation status](https://weblate.foundryvtt-hub.com/widgets/creature-loot-crafting-and-gathering/-/287x66-black.png)](https://weblate.foundryvtt-hub.com/engage/creature-loot-crafting-and-gathering/)

### If you want to buy me a coffee [![alt-text](https://img.shields.io/badge/-Patreon-%23ff424d?style=for-the-badge)](https://www.patreon.com/p4535992)

or support the original autor

[![alt-text](https://img.shields.io/badge/-Patreon-%23ff424d?style=for-the-badge)](https://www.patreon.com/user/membership?u=78783518)


Collating Jon Gazda's Creature Loot supplements for use in Foundry with theripper93's premium modules Gatherer and Mastercrafted

This will include:
- Compendium of lootable and crafted items described in the supplement
- Compendium of rollable tables for each creature
- Journal with Gatherer entries for automated looting

And later:
- Recipe books for crafting items from loot

*tables need to be imported to your world for Gatherer journal entries to work. Everything else references from within the compendiums

Source Content: https://www.gmbinder.com/share/-L9zV7_eIrs3bqQ_cNd5

Monster Manual Progress:
⬤⬤⬤◔○○○○○○○○○ 26%


The Gathering Journal entry and Recipe books require theripper93's **Gatherer and Mastercrafted premium modules**. More information on those at https://theripper93.com/

## Installation

It's always easiest to install modules from the in game add-on browser.

To install this module manually:
1.  Inside the Foundry "Configuration and Setup" screen, click "Add-on Modules"
2.  Click "Install Module"
3.  In the "Manifest URL" field, paste the following url:
`https://raw.githubusercontent.com/p4535992/foundryvtt-creature-loot-crafting-and-gathering/master/src/module.json`
4.  Click 'Install' and wait for installation to complete
5.  Don't forget to enable the module in game using the "Manage Module" button

## Issues

Any issues, bugs, or feature requests are always welcome to be reported directly to the [Issue Tracker](https://github.com/p4535992/foundryvtt-creature-loot-crafting-and-gathering/issues ), or using the [Bug Reporter Module](https://foundryvtt.com/packages/bug-reporter/).

## Api

# Build

## Install all packages

```bash
npm install
```
## npm build scripts

### build

will build the code and copy all necessary assets into the dist folder and make a symlink to install the result into your foundry data; create a
`foundryconfig.json` file with your Foundry Data path.

```json
{
  "dataPath": "~/.local/share/FoundryVTT/"
}
```

`build` will build and set up a symlink between `dist` and your `dataPath`.

```bash
npm run-script build
```

### NOTE:

You don't need to build the `foundryconfig.json` file you can just copy the content of the `dist` folder on the module folder under `modules` of Foundry

### build:watch

`build:watch` will build and watch for changes, rebuilding automatically.

```bash
npm run-script build:watch
```

### clean

`clean` will remove all contents in the dist folder (but keeps the link from build:install).

```bash
npm run-script clean
```
### lint and lintfix

`lint` launch the eslint process based on the configuration [here](./.eslintrc)

```bash
npm run-script lint
```

`lintfix` launch the eslint process with the fix argument

```bash
npm run-script lintfix
```

### prettier-format

`prettier-format` launch the prettier plugin based on the configuration [here](./.prettierrc)

```bash
npm run-script prettier-format
```

### package

`package` generates a zip file containing the contents of the dist folder generated previously with the `build` command. Useful for those who want to manually load the module or want to create their own release

```bash
npm run-script package
```

## [Changelog](./CHANGELOG.md)

## Issues

Any issues, bugs, or feature requests are always welcome to be reported directly to the [Issue Tracker](https://github.com/p4535992/foundryvtt-creature-loot-crafting-and-gathering/issues ), or using the [Bug Reporter Module](https://foundryvtt.com/packages/bug-reporter/).

## License

This package is under an [MIT license](LICENSE) and the [Foundry Virtual Tabletop Limited License Agreement for module development](https://foundryvtt.com/article/license/).

## Credit

Thanks to anyone who helps me with this code! I appreciate the user community's feedback on this project!
