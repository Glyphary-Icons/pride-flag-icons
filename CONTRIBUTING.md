# Contributing

Thank you for helping improve Glyphary Pride Flags. Contributions from LGBTQIA+ communities and allies are welcome. Please approach differences in identity, language, and flag usage with respect; do not gatekeep who may participate or claim to represent an entire community.

## Add or update a flag

1. Choose the appropriate subfolder under `flags/` (or propose a new category if needed).
2. Add a self-contained `.svg` file with a clear, lowercase, hyphenated filename, such as `nonbinary-pride-flag.svg`.
3. Add or update the matching entry in `flags.json` with:
   - `name`: a concise, accessible display name;
   - `category`: the folder name;
   - `tags`: useful alternate spellings and search terms;
   - `path`: the relative path to the SVG, for example `flags/gender/nonbinary-pride-flag.svg`.
4. Update the README if the change adds a new category or changes how the collection is used.
5. Review the rendered SVG and catalog entry before submitting a pull request.

## SVG guidelines

- Keep each asset standalone and self-contained. Do not link to remote resources or embed scripts, external fonts, or raster images.
- Use valid SVG markup and a `viewBox` so the flag scales cleanly. The collection currently uses a `300 × 200` canvas; preserve the established canvas unless the flag requires another proportion.
- Use explicit fill colors so files look the same when opened outside Glyphary. Do not use `currentColor` or site-specific CSS.
- Prefer simple, readable vector geometry and remove editor-only metadata or unrelated hidden content.
- Preserve distinctive symbols and meaningful proportions when present; do not flatten them into stripes if that changes the design.

## Documentation and review

Flag colors, proportions, stripe order, and symbols can vary across communities and over time. When multiple variants are in use, describe the chosen variation clearly in the flag name or tags, and include a short explanation in the pull request. Avoid calling colors universal or designs universally official unless a relevant community has established that wording.

For corrections, please share context or references that help reviewers understand the proposed change. A color reference can inform design decisions, but it is not an artwork source. Never copy or import SVG artwork from third-party code repositories; create the vector composition for this collection.

Please keep pull requests focused, explain what changed and why, and note any accessibility or rendering considerations. Maintainers may request clarification to ensure flags are represented carefully and respectfully.
