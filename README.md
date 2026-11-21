# OctoWoW Consumables Calculator

A lightweight browser calculator for planning crafted combat consumables on OctoWoW.

## Features
- Search and filter consumables by category.
- Set target quantities for multiple items.
- Recursively expand crafted intermediate materials.
- Aggregate raw ingredients into one shopping list.
- Mark items as already owned and subtract them from totals.
- Clearly labels recipe records that still need in-game verification.

## Run
Open `index.html` in a browser, or enable GitHub Pages for the repository (Deploy from a branch: `main`, folder `/ (root)`).

## Recipe data policy
OctoWoW's database is the primary reference: https://octowow.st/db/
The community AckisRecipeList backport is a useful secondary index: https://gitlab.com/Artur91425/ackisrecipelist-classic

The public OctoWoW database has documented gaps, so a recipe is not treated as confirmed merely because a similar Vanilla recipe exists. Review `data/recipes.json`; each recipe includes a source/status note. Add or correct recipes only when the OctoWoW recipe and ingredient quantities have been verified.

## License
The calculator implementation is an independent implementation. Recipe data and names remain subject to their respective sources' terms.