# ramya036.github.io

Personal portfolio of Ramya Sree Narra, a full-stack and AI engineer. Live at https://ramya036.github.io

A single static page (HTML, CSS and vanilla JavaScript, no build step). The "Ask about my work" box runs a small TF-IDF keyword search over the page's own content in the browser, the same idea as the retrieval step in [AskDB](https://github.com/ramya036/askdb).

## Changing which projects are shown

All projects come from one list, `PROJECTS`, near the projects section in `index.html`. Every project is rendered the same way: label, name, description, tools, links and a demo panel. To tailor the page to a job description, reorder, edit or replace entries in that list. The "Ask about my work" search picks up the change automatically.

Each entry's `demo` is one of:

- a built-in demo: `"askdb"`, `"mealmate"`, `"nestpoint"`, `"translator"` or `"assistant"`
- screenshots: `{ type: "image", images: [{ src, alt, label, caption }] }`, with images placed in `img/`
- a live app: `{ type: "live", url, height }`

## Live demos

`tic-tac-toe/` and `produce-filter/` are production builds of [tic-tac-toe-react](https://github.com/ramya036/tic-tac-toe-react) and [react-produce-filter](https://github.com/ramya036/react-produce-filter). To update one, run `npm run build` in that repo and copy its `build/` folder here.
