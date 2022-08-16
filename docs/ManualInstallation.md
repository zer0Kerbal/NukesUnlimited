---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Nuke's Unlimited (NU)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Nuke's Unlimited (NU)

[Home](./index.md)

Adds Nuke's Unlimited agent, flags, and common config files used in all Nuke's Unlimited's add-ons for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `NukesUnlimited` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Nuke/NukesUnlimited`
* Extract the package's `Nuke/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/Nuke` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/Nuke/NukesUnlimited`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Nuke/NukesUnlimited`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/Nuke/NukesUnlimited`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [Nuke]
      + [NukesUnlimited]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * changelog.md
        * License.txt
          ManualInstallation.htm
        * NukesUnlimited.version
        * readme.htm
      ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Nuke's Unlimited (NU)][NU]

[NU]: https://forum.kerbalspaceprogram.com/index.php?/topic/208107-*/ "Nuke's Unlimited Forum Thread"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
