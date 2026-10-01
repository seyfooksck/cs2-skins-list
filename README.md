# CS2 Skins List

A collection of Counter-Strike 2 skin, glove, sticker, agent, and other item images, organized by category and item ID. Item folders include available images and a `skins.json` file with metadata such as names, rarity, wear variants, and prices.

## Folder structure

```
skins/
  ak47/
    1449/
      fn.png
      mw.png
      ft.png
      ww.png
      bs.png
      skins.json
  sticker/
    1444/
      0.png
      skins.json
  agent/
    4613/
      0.png
      skins.json
  ...
```

Folders are grouped by category and then by numeric item or paint ID. Wear variants use the corresponding wear abbreviation: `fn` (Factory New), `mw` (Minimal Wear), `ft` (Field-Tested), `ww` (Well-Worn), and `bs` (Battle-Scarred). Items without wear variants use `0.png`.

## Categories

The collection includes weapon and knife skins, gloves, stickers, agents, patches, graffiti, keychains, music kits, collectibles, crates, and keys.

## Data sources

- Prices: [Skinport public API](https://api.skinport.com/v1/items) (USD)
