# Heavy and Light Buyers

Who actually makes the purchases in a category? Enter a mean and a shape and see how much of all buying comes from the heaviest buyers, the lightest half, and people who buy once. It tests the "target heavy users" instinct and the 80/20 rule against a negative binomial model.

Open `index.html` in any browser. No build step and no dependencies.

- **Inputs:** mean purchases per person (m) and shape (r), the same two numbers the banana chart uses, plus the slice of heaviest buyers to look at.
- **Verdict:** `far from 80/20`, `short of 80/20` or `80/20 holds`, from the share of purchases made by the heaviest 20% of buyers.
- **Shows:** the share of purchases from your chosen slice, the lightest half of buyers, buyers who buy once, penetration, a curve with the 80/20 point marked, and a quintile table.
- **Presets:** fast food, bread and cars. They are illustrative shapes, not measured data.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

A model of a typical category. Real categories vary, and heavy and light depend on the period you pick. One brand's buyers are lighter than the category's.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
