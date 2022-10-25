---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Simple Cargo Solutions (CARGO)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Simple Cargo Solutions (CARGO)

[Home](./index.md)

A request came up for just a couple of simple stockalike cargo bays.... and here they are!

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `AxialAerospace` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/AxialAerospace/SimpleCargoSolutions`
* Extract the package's `AxialAerospace/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/AxialAerospace` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/AxialAerospace/SimpleCargoSolutions`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/AxialAerospace/SimpleCargoSolutions`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/AxialAerospace/SimpleCargoSolutions`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [AxialAerospace]
      + [SimpleCargoSolutions]
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * changelog.md
        * GPL-2.0.txt
        * ManualInstallation.htm
        * readme.htm
        * SimpleCargoSolutions.version
      ...
    * ModuleManager.ConfigCache
    ...
  * KSP.log
  ...
```

### Dependencies

* [Axial Aerospace Ltd (AA/L)][AAL]

[AAL]: https://forum.kerbalspaceprogram.com/index.php?/topic/209301-*/ "Axial Aerospace Ltd (AA/L)"
