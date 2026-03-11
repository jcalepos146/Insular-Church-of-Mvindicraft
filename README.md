# The Insular Church of Mvindicraft — Website

A medieval illuminated manuscript-styled website for the Insular Church of Mvindicraft, designed for GitHub Pages.

**Pre-Tridentine Insular Rite · In Communion with Constantinople · Sede Vacante**

**🔗 [Visit the Live Site](https://jcalepos146.github.io/Insular-Church-of-Mvindicraft/)**

## Deploying to GitHub Pages

1. Upload the full contents of this folder (including `index.html`, `docs/`, and this README) to the repository.
2. Go to **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**, choose `main`, root `/`.
4. Click **Save**. The site is live at https://jcalepos146.github.io/Insular-Church-of-Mvindicraft/

## Adding PDF Documents

1. Place `.pdf` files inside the `docs/` folder.
2. Open `index.html` and find the `documents` array in the `<script>` section near the bottom.
3. Add a new entry:

```js
{
  title: "The Bishops' Book",
  description: "The Revised Confession of Faith as written by Corpo MacAirthir.",
  category: "Doctrine",
  file: "docs/bishops-book.pdf"
}
```

4. Available categories with icons: `Lectionary`, `Canon Law`, `Doctrine`, `Manuscripts`, `Liturgy`, `Theology`, `History`, `Catechism`. Add more in the `categoryIcons` object.
5. Commit and push — the document will appear in the Scriptorium.

## Current Documents

- **The Insular Book — 28-Day Lectionary (2nd Edition)** — Complete liturgical calendar with biweekly KJV lectionary
- **Canons of the Synod of Armagh** — The twelve canons of the First Insular Synod

## File Structure

```
/
├── index.html          ← The complete website (single file)
├── docs/
│   ├── Insular_Book_Lectionary_2nd_Edition.pdf
│   └── Canons_of_the_Synod_of_Armagh.pdf
└── README.md
```

## Links

- **[The Insular Church of Mvindicraft — Live Site](https://jcalepos146.github.io/Insular-Church-of-Mvindicraft/)**
- [Mvindicraft Discord](https://discord.gg/2M34xrJS)
- [Insular Church Discord](https://discord.gg/2S7Q6YhDXe)
