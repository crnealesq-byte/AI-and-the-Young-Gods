# The Chief Archon — GitHub Pages project

A static, responsive website for the graphic-novel serial. It uses plain HTML and CSS; no framework, build step, database, or JavaScript is required.

## Preview locally

Open `index.html` in a browser. For a local server, run `python3 -m http.server` from this folder and visit `http://localhost:8000`.

## Publish with GitHub Pages

The site source is now in the private repository `crnealesq-byte/AI-and-the-Young-Gods`. GitHub Pages has not been enabled, so the site is not published.

Before enabling Pages, choose whether the site should be public. On a GitHub Free personal account, GitHub Pages requires a public repository. Making this repository public exposes the source and commit history, and lets anyone fork it. If the repository stays private, Pages requires an eligible paid plan; check the account's current Pages options under **Settings → Pages**.

When ready to publish, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save. The site uses relative links and works at a project URL.

## Add approved artwork

Episode art slots have stable human-readable labels such as `CA01-P01`, `CA01-P02A`, and `CA01-P04E`. Put approved images in `assets/img/` and replace the corresponding `.art-slot` placeholder `<div>` in the episode page with a `<figure>` and `<img>`.

Example:

```html
<figure class="panel">
  <img src="../../assets/img/ca01-p01.webp" alt="A luminous phone-shaped rectangle floating before a curved cosmic membrane.">
  <figcaption class="panel-copy"><p class="caption">The first kingdom was a rectangle.</p><p class="caption">We carried it in our hands.</p></figcaption>
</figure>
```

Keep all story text as live HTML for accessibility. Do not bake captions, speech balloons, or UI text into images unless Kit approves a lettering workflow.

## Editorial boundaries

- The Source, Demiurge, archons, younger gods, brane, and simulacrum are the project's fictional vocabulary.
- The novel stages distinct religious and philosophical sources in conversation; do not describe them as one historical doctrine.
- Public figures appear in fictionalized roles. Dialogue and events are invented.
- The 4D brane imagery is speculative framing, not evidence of a separate physical simulation universe.
- Keep the project unpublished until Kit approves the copy, art, and publication details.
