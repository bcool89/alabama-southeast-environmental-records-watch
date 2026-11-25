# Alabama & Southeast Environmental Records Watch

Independent public-interest environmental records research across Alabama and the Southeast. Established November 25, 2026. **This regional repository is separate from the national Hazardous Stockpile Records Watch project.**

**Public website:** https://bcool89.github.io/alabama-southeast-environmental-records-watch/

## Geographic scope
1. Chelsea and Shelby County
2. Greater Birmingham
3. Central Alabama
4. Alabama military environmental records
5. Alabama statewide
6. Southeastern sites with demonstrable Alabama relevance

## Website and data
- `index.html`: public website with searchable investigation inventory and records-request tracker.
- `chelsea-shelby.html`: local drinking-water and Shelby County records research overview.
- `coosa-river.html`: Coosa River watershed and former military/industrial cleanup research overview.
- `sites.csv`: **33** initial investigation entries, including confirmed historical records and clearly marked screening leads.
- `records-requests.csv`: **10 proposed requests**, none submitted as of the launch baseline.
- `METHODOLOGY.md`: evidence, fee-control and publication standards.
- `CHANGELOG.md`: project updates.

The homepage loads both CSV files using browser `fetch()` and renders their rows. Editing `sites.csv` or `records-requests.csv` updates the online tables after a new GitHub Pages deployment. The HTML includes its older launch snapshot as an offline/fetch-error fallback, so if the CSV cannot be loaded that older content may be displayed with an explicit warning. On a live site, always check the data status message. CSV fields are rendered as text, not injected as HTML. The featured investigation pages are curated narratives and **do not auto-update** when CSV rows change.

## GitHub Pages
Publish from `main` / `(root)` under **Settings → Pages**. No build step or paid hosting is needed.

## Evidence and publication rules
A facility or watershed's appearance in this list does **not** imply it is dangerous. Historical results are not proof of current exposure. Source attribution must be supported by sampling and documented pathways. Cite official records and label screening subjects, assessments, documented contamination and emergency notices distinctly. Do not characterize proposed records requests as filed.

To submit corrections or additional public sources, [open an issue](https://github.com/bcool89/alabama-southeast-environmental-records-watch/issues). Do not disclose personal, restricted, or security-sensitive information. Third-party record rights remain with their respective holders.
