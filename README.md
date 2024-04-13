## Sanctum 1.0 for Obsidian 0.16

### Disclaimer for Sanctum Users

- The sidenote syntax has changed (they are now callouts. Example: `>[!aside|left]` will give a left aligned callout. If you want to make it go further left, you can add up to 5 `+` next to the `left` information (for example: `>[!aside|left +++++]` will push the sidenote to the margin, so it doesn't mess with text);
- Images work similarly to asides, but they also get a `-` syntax, as well as sizing options (`-xs`, `-s`, `-m`, `-l`(regular size), `-xl`, `xxl`, as well as a `center`/`centre` option;
- Custom checkboxes have been expanded: `*`,`a`,`f`,`S`,`-`,`>`,`<`,`l`,`B`,`X`,`n`,`p`,`c`,`w`,`b`,`I`,`!`,`?`,`i`,`/`,`u`,`d`,`F`,`r`,`m`,`M`,`L`,`t`,`T`,`P`. They should mostly match the one's in Primary;
- there are TONS of new style settings options, and more to come;
- Work on the UI is at its beginning stages. The theme has been completely rewritten from scratch (no exaggeration there), so expect regular changes in the foreseeable future!

![sanctum-readme-title](https://user-images.githubusercontent.com/91087143/136701698-2464f5d0-30d5-4ee5-9261-4cca96448192.png)

Sanctum’s a minimalist theme for creating a serene space of retreat, for thought and uninterrupted work.

## Installation

Inside obsidian, go to `Settings ➞ Appearance ➞ Manage`, and look for `Sanctum`.

You can also manually install Sanctum by:

1. Downloading the CSS file and moving it into the folder `.obsidian/themes/` located in your vault folder;
2. Rename the css file to `Sanctum.css`;
3. In Obsidian, go to `Settings ➞ Appearance ➞ Themes ➞ Reload themes`, and select `Sanctum`.

## Disclaimer

The following theme significantly alters Obsidian's original css, and so is prone to breaking upon new Obsidian updates, as well as being incompatible with custom css snippets, which might require specific adjustments.

## Recommended Plugins

- [Smart Typography](https://github.com/mgmeyers/obsidian-smart-typography): for a better and coherent writing experience
- [Contextual Typography](https://github.com/mgmeyers/obsidian-contextual-typography): For a better typographic experience, and access to some of the theme's features
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings): for tons of customization options

## Design Principles

**Intentional**

- This theme was made with the intent of clarifying Obsidian's UI, reducing the unnecessary clutter and keeping what's essential for an enjoyable and intuitive experience;
- Greyscale palette is the same both for light as well as dark theme;
- Colour is also used for contrast when hovering and activating elements.

**Consistent**

- Every element is styled according to a predetermined grid, scale, animations (based on IBM's Carbon Design System) and colours - this conveys consistency throughout the theme;
- The theme was created with the intention of using only one workhorse font family, used everywhere, but styled differently. Thus the theme comes with only 1 font family - IBM Plex
- Offer a similar enjoyable experience, independently of screen size or device.

**Clean**

- Use of calming colours, only used either to convey importance, or in the note file itself;
- The background colour is the same in every element, to reduce visual noise and give a more calming atmosphere;
- Elements are related to each other using the rules of visual _gestalt_. This means that they're grouped by proximity, in a common region or as a focal point.

## Showcase (outdated)

###### Preview Mode

![preview-showcase](https://user-images.githubusercontent.com/91087143/136707215-fb674834-e1e0-4665-b8ba-089c869a74cc.jpg)

###### Edit Mode

![edit-showcase](https://user-images.githubusercontent.com/91087143/136707216-e0957565-bfe9-49f6-bb32-16eb775d6c74.jpg)

###### Modal

![modal-showcase](https://user-images.githubusercontent.com/91087143/136707218-32acaa9e-4b30-46ec-b3f9-73ce2d22e301.jpg)

###### Prompt

![prompt-showcase](https://user-images.githubusercontent.com/91087143/136707222-cc2ee9cf-adc9-4bab-a06f-f927d964eb57.jpg)

###### Resize Handles

- Resize Handles are understated, until hovered.

<img src="https://user-images.githubusercontent.com/91087143/136707350-c28ca674-fd4b-42e3-acf4-fa71a380ebf9.gif" width="200" />

## Features

- Custom icons (as well as custom file icons!);
- Sidenotes (credit @SlRvb);
- Multi-Color Highlights (credit @Atlas);
- Custom Checkbox / Task types, and Pseudo Admonitions;
- Custom Codeblock language - `pure-text`, that enables you to write text for easy copying;
- Image desaturation: better for consistency, they gain normal colour when hovered (credit @kepano);
- Active line highlighting;

(for a more <u>comprehensive</u> walkthrough of Sanctum's features, check out the [Theme Guide](documentation/Theme_Guide.md))

## Plugin Support

- Advanced Tables
- Block Reference Counter
- Breadcrumbs
- Calendar
- Changelogs
- Charts
- Checklist
- Copy Code Button (it now supports Obsidian v0.12.17's new code copy button!)
- Dataview
- Excalidraw
- Gallery
- Kanban
- Quick Explorer
- Sliding Panes (Andy’s Mode)
- Style Settings
- Templater

(for plugin support requests & issues, refer to Feedback & Contributions)

## Feedback & Contributions

If you encounter an issue, or would like to contribute to this theme, don't hesitate to submit an issue or raise a PR. You can also message me on [Discord](https://discord.com/invite/veuWUTm) @jdaniel or on the [Obsidian Forums](https://forum.obsidian.md/u/jdanielmourao/summary).

## Support

If you enjoy my work and would like to support it, you may click the icons below, or the links on the right side of this repository.

<a href="https://paypal.me/jdanielmourao"><img src="assets/PayPal.svg"></a>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X56R5Q1)
