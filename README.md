
# howtofixit

A quarto site about how to fix common problems when using R and git.

## How to update

Render the project locally before pushing any changes. If you're using R, you can render the site with `quarto::quarto_render()`, then add any changed or new files, commit, and push your changes.

If you're adding a new page, you'll need to add it to `_quarto.yml` under `website: navbar` before rendering.
