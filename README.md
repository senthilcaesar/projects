# My Projects

A single-page portfolio of the projects I've built, with a live preview, a short write-up, the tech stack and links for each one.

## Projects

| Project | What it does | Links |
|---|---|---|
| **TraceIQ** | Answers the "why" behind a project. It stores decisions, bugs, fixes and dependencies in a Neo4j knowledge graph, and an LLM turns plain-English questions into Cypher queries. | [Live app](https://spalanivelu1989.github.io/trace-iq/) · [Source](https://github.com/spalanivelu1989/trace-iq) |

## Run it

The page is one self-contained `index.html` file with no build step. Open it in a browser, or serve the folder:

```sh
python3 -m http.server
```

## Add a project

1. Put a screenshot of the app in `images/` (16:10 works best).
2. In `index.html`, copy an entry in the `PROJECTS` list near the top of the `<script>` block and change its values.

Each entry needs `id`, `name`, `summary`, `skills` and `links`. `tagline`, `status`, `image` and `sampleQuestion` are optional.

## Design

The colours come from the [Catppuccin Frappé](https://catppuccin.com/palette/) palette. The page has a light/dark toggle, project search (press `/` to jump to it) and a layout that works on phones.
