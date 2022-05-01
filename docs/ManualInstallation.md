---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
SimpleCargoSolutions (SCS)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# SimpleCargoSolutions (SCS)

[Home](./index.md)

A request came up for just a couple of simple cargo bays.... and here they are!

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the AxialAerospace folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/AxialAerospace/SimpleCargoSolutions`
* Extract the package's `AxialAerospace/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/AxialAerospace` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/AxialAerospace/SimpleCargoSolutions`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
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
        + [Agencies]
          ...
        + [Compatibility]
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
        * changelog.md
        * License.txt
        * readme.htm
        * SimpleCargoSolutions.version
      ...
    ...
  * KSP.log
  ...
```

### Dependencies

* none
