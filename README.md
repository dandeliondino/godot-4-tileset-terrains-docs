## Creating terrain sets (autotiling) documentation

This repo contains a PDF and resources from an archived PR that updated the **Using TileSets: Creating terrain sets (autotiling)** documentation for Godot 4. It is available here as a resource to help new users set up terrain tiles.

It contains content edited from the main Godot docs, and so is distributed here under that same license: © Copyright 2014-present Juan Linietsky, Ariel Manzur and the Godot community (CC BY 3.0).

### Links
Github can be weird about displaying such a long PDF, so I recommend either clicking the `Download raw file` button on the PDF page, or using `Code` -> `Download zip` from the main repo page.

- [PDF of the Creating terrain sets (autotiling) manual section](./terrain_sets_docs.pdf)
- [Godot 4 "starter" project](./starter_project/) that contains all the examples from these docs with the TileSets and terrains set up
- [Templates](./templates/) in `png` and `svg` format

### Contents
- Creating terrain sets (autotiling)
    - Understanding how terrains work
    - Choosing a terrain mode
        - Match Sides
        - Match Corners
        - Match Corners and Sides
    - Setting up a new terrain set
        - Setting up terrain tiles in Paint mode
        - Setting up terrain tiles in Select mode
    - Special cases
        - Animating terrain tiles
        - Using probabilities for multiple tiles with the same bitmask
        - Using alternative tiles for one tile with multiple bitmasks

### Why this is here

In 2023, I responded to a request to update the Godot 4 docs section for [Using TileSets: Creating terrain sets (autotiling)](https://docs.godotengine.org/en/latest/tutorials/2d/using_tilesets.html#creating-terrain-sets-autotiling). While I received feedback that [the PR I created](https://github.com/godotengine/godot-docs/pull/7789) had been submitted correctly, there wasn't interest in reviewing or merging it. I ended up closing the PR as it was blocking others from making edits that might be more likely to get merged.

I am guessing my PR might not have fit the goals the core team had for these docs, and I have tremendous respect for all of the Godot docs maintainers -- they've done an amazing job in establishing a standard of highly accessible documentation.

For a time, Godot users could still access the content in this original PR on Github as a reference. However, Github seems to have recently changed how the Sphinx (`rst`) file previews are displayed, so the images are no longer inline. And the images are particularly important for understanding these docs.

As of 5/2024, the official docs have yet to be updated, and I still see almost-daily requests on social media for explanations of Godot 4's terrain sets (particularly what the center bits are for!). So I decided to repost the docs here as a PDF. It is not as accessible as the original format, but I hope it will still be useful.

This documentation was created in Godot 4.0/4.1. There have been minor changes to the UI since then, but the tutorials in this these docs should work the same for 4.2/4.3.

I welcome anyone who wants to use any of the content from the original PR [#7789](https://github.com/godotengine/godot-docs/pull/7789) to create a new PR for the terrain sets section. See the [commit](https://github.com/godotengine/godot-docs/pull/7789/files#diff-f1afad32ca03f3a25b1c50f47996f838c74c9f94ead387382f21b9ef02d53a72) for the original `rst` file and `webp` images.
