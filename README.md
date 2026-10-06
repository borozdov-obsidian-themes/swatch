# Borozdov Swatch

A theme from the Borozdov collection. Two faces — light **Noon**, a sunlit paper notebook
with highlighter swatches, and dark **Twilight**, the same notebook under a desk lamp.
Cream paper, ink outlines at 24px, and one sunshine yellow for what you act on.

![Borozdov Swatch in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/swatch/main/screenshots/light.png)

![Borozdov Swatch in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/swatch/main/screenshots/dark.png)

## Principles

- **Ink on cream.** The page is warm paper, never pure white; cards, callouts, tags and
  buttons define themselves by a 1px ink outline, not by fill, and nothing casts a shadow.
- **One highlighter.** Sunshine yellow is rationed to what you act on: the main button, a
  checked task, a toggle, the open file, the stroke under a link and the highlighter
  itself. Mint is kept for what went well.
- **Soft corners on flat paper.** 24px on cards and panels, pills for buttons and tags,
  small 6px corners on fields and code.
- **One sans, two weights.** The platform's own sans at 400 for the text and 500 for
  headings and labels, tracked in a little as it grows.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Links in ink with a stroke of highlighter underneath; the whole word lights up on hover
- Callouts as outlined cards with the title in the type's colour
- Tags and property values as filter pills that fill with sunshine on hover
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts, so the theme stays around 12 KB
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Palette**. Install Borozdov Palette under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Swatch** under Style Settings → Borozdov Palette → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/swatch/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Swatch/`, then choose Borozdov Swatch under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Полдень» — залитый солнцем
бумажный блокнот с пробами маркера, и тёмный «Сумерки» — тот же блокнот под настольной
лампой. Кремовая бумага, чернильные контуры со скруглением 24px и один солнечно-жёлтый для
того, что вы делаете. Шрифты не встроены. В каталоге тема живёт вариантом Borozdov Palette: установите Borozdov Palette и плагин Style Settings, затем выберите Swatch в Style Settings → Borozdov Palette → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
