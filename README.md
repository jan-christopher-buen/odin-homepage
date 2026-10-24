# Homepage

A responsive homepage for Jan Christopher Buen, built with semantic HTML and CSS for [The Odin Project’s Homepage assignment](https://www.theodinproject.com/lessons/node-path-advanced-html-and-css-homepage). It introduces my learning journey and showcases six projects with real preview screenshots, source links, and live demos.

## View locally

No installation or build step is required. From the repository directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://localhost:8000>. Stop the server with `Ctrl+C`. Opening `index.html` directly also works.

## Design and accessibility

- Desktop: a prominent illustrated introduction beside the About panel, a three-column project grid, and a split contact section.
- Tablet (640–1023px): the illustration overlaps the About panel; text wraps beside and beneath it. Project cards use two columns.
- Mobile (below 640px): the introduction, cards, and contact content stack, with a full-width footer illustration.
- Fluid containers, flexible card heights, and a 1200px content limit keep spacing comfortable across screen sizes.
- Semantic landmarks, one main heading, a keyboard skip link, visible focus indicators, and descriptive names for icon links support navigation.
- Project previews supplement adjacent descriptions, so they use empty alternative text, as does the decorative footer illustration.
- Fonts, screenshots, and artwork are served locally. Images reserve layout space; project previews and the footer image load lazily.

The project uses HTML, CSS Grid, Flexbox, media queries, and an SVG illustration. It has no JavaScript, framework, package dependencies, or backend.

## Featured projects

[Source repositories](https://github.com/jan-christopher-buen): Battleship, Weather App, Todo List, Restaurant Page, Tic Tac Toe, and Admin Dashboard. Each card links to its corresponding repository and deployed preview. Screenshots show the initial state of the real pages; they are static previews, and the linked projects may change.

## Credits

- Layout brief and desktop, tablet, and mobile references: [The Odin Project](https://www.theodinproject.com/lessons/node-path-advanced-html-and-css-homepage).
- Playfair Display by the Playfair Display Project Authors: [Google Fonts source](https://github.com/google/fonts/tree/main/ofl/playfairdisplay), under the SIL Open Font License 1.1. See [included notice](assets/fonts/playfair-display-LICENSE.txt).
- Roboto by the Roboto Project Authors: [Google Fonts source](https://github.com/google/fonts/tree/main/ofl/roboto), under the SIL Open Font License 1.1. See [included notice](assets/fonts/roboto-LICENSE.txt).
- Workspace illustration: original SVG artwork created for this homepage, used as a decorative alternative to a personal portrait.
- Project screenshots: captured from the six project previews linked on the homepage. The Admin Dashboard screenshot includes its original Material Design Icons; that project credits [Material Design Icons](https://pictogrammers.com/library/mdi/), whose icons use the [Apache 2.0 license](https://github.com/Templarian/MaterialDesign/blob/master/LICENSE). The upstream notice and license are [included](assets/images/mdi-LICENSE.txt); the icon font is not bundled here.
- Code and external-link symbols use text characters; no icon library is included.

## Learning outcomes and scope

This exercise practices responsive compositions, text wrapping around a floated image, Grid/Flexbox layouts, image optimization, and keyboard navigation. Contact links lead to my GitHub profile; no personal email, phone number, or contact form is included.

For GitHub Pages, publish `main` from `/ (root)` in the repository’s **Settings → Pages**. All local asset paths are relative and support the repository subpath. No build workflow is needed.
