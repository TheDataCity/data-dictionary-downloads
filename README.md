# data-dictionary-downloads

Public mirror of the data dictionary downloads served on
[docs.thedatacity.com/data-dictionary](https://docs.thedatacity.com/data-dictionary).

Files (CSV, Excel, JSON, PDF) are published automatically as release assets
under the `data-dictionary` tag by the sync workflow in the private `docs`
repo. **Do not edit by hand.**

`og-card.png` is the preview image that links to docs.thedatacity.com show
when they're shared. The `docs` repo generates it with `scripts/make_og_card.py`
and points `og:image` and `twitter:image` in its `docs.json` here, because the
`docs` repo is private and can't serve the file publicly. When the image
changes there, copy the new file here.
