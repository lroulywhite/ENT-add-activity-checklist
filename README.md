# ENT | Add an Activity Checklist to a Record [Simulation]

Guided click-through simulation for Momentus Enterprise. The learner first sees how to get to the Add Activity button (Contracts in the navigation, the contract's Activities tab, Add Activity), then adds a checklist to a contract: open the Add Activity menu, choose Add Checklist, pick Contract Exchange, select Continue, then select Create. Seven steps in all.

Built for the Momentus Learning Center and embedded in Genially. One product only (Enterprise).

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole simulation. Self-contained: fonts, styles and product screens are embedded. No external requests. |
| `.nojekyll` | Tells GitHub Pages to serve the file as is. |

## Publish on GitHub Pages

1. Create a new repo named `ENT-add-activity-checklist` (public, or private if your plan allows Pages on private repos).
2. Upload `index.html`, `.nojekyll` and `README.md` to the repo root, or from a terminal:

```
git init
git add .
git commit -m "Add ENT activity checklist simulation"
git branch -M main
git remote add origin https://github.com/lroulywhite/ENT-add-activity-checklist.git
git push -u origin main
```

3. In the repo, go to **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the simulation is live at:

`https://lroulywhite.github.io/ENT-add-activity-checklist/`

## Embed in Genially

Use an iframe or website embed with the Pages URL above. If your Genially element takes code, use:

```html
<iframe src="https://lroulywhite.github.io/ENT-add-activity-checklist/" title="ENT | Add an Activity Checklist to a Record [Simulation]" width="100%" height="100%" style="border:0" allow="fullscreen"></iframe>
```

Give the element a 16:9 area and turn on full screen if the product text looks small. The simulation scales to fit, and the guide cards grow on small embeds so the text stays readable.

## Updating

Replace `index.html` and commit. GitHub Pages redeploys on its own. Cached copies in Genially can take a few minutes to refresh.

## Notes for reviewers

- Product screens come from Enterprise captures of the Edit Contract page (masterdemo). Names are fictional (Maple Ridge Crafts, Inc., Spring Planning Meeting, Wedding Reception Checklist).
- The simulation ends at the Create click. The screen after Create was not captured, so no result is shown.
- Inferred, for Product to confirm: after choosing Contract Exchange, its name appears in the Checklist To Add field. No capture shows that state.
- Not covered: the Actions menu route (Actions > Activities > Add > Add Checklist). It appears only as a tip on the final card.
- The first step is an orientation screen (no click needed) with numbered markers on Contracts, the Activities tab and Add Activity. How a user opens a contract from the Contracts list was not captured, so that line only says to open the contract.
- The product zooms and pans on each step so the menu or window is larger and the guide card never covers it.
- Keyboard: Enter or Space runs the highlighted action. Back and Restart are on every card after the title card.
- The embedded CSS includes the Wijmo grid library's license banner. Leave it in place.
