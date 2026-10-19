# Plot Armor site

The public files of [Plot Armor](https://nickharder.github.io/plot-armor-site/privacy.html), served
by GitHub Pages at `https://nickharder.github.io/plot-armor-site/`:

- `daily.json`: the signed daily file the extension downloads once a day (trending titles and
  their packs). The extension refuses it unless its ECDSA P-256 signature checks out.
- `privacy.html`: the privacy policy, the same page the extension carries.

Nothing here is written by hand. The private code repository's daily workflow builds, signs and
pushes both files with this repository's deploy key.
