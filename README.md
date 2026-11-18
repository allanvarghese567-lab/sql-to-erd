# SQL to ERD

Interactive SQL → Entity-Relationship Diagram visualizer.

Paste `CREATE TABLE` and `CREATE VIEW` statements, click **Draw diagram**, and get a live, draggable ERD with foreign-key and view relationships.

**Live demo:** [https://allanvarghese567-lab.github.io/sql-to-erd/](https://allanvarghese567-lab.github.io/sql-to-erd/)

## Features

- Parses tables, primary keys, foreign keys, and views
- Optional inference of relationships from `idName` style columns
- Drag tables/views to rearrange
- Click a node to inspect columns and links
- Show / hide individual tables
- Light & dark mode (follows system preference)
- Pure client-side — no backend required

## Usage

1. Paste your SQL (or use the included sample)
2. Click **Draw diagram**
3. Drag nodes, select tables for details, toggle visibility

## Embed with iframe

You can embed this tool in any website using a simple iframe:

```html
<iframe
  src="https://allanvarghese567-lab.github.io/sql-to-erd/"
  width="100%"
  height="800"
  style="border: 1px solid #ccc; border-radius: 8px;"
  title="SQL to ERD"
  loading="lazy"
  allowfullscreen
></iframe>
```

### Tips

- Adjust `height` as needed (recommended 700–900px).
- Use `width="100%"` for responsive layouts.
- The tool works fully inside the iframe (drag, select, draw, etc.).

## Enable GitHub Pages

If the live demo link above is not working yet:

1. Go to the repository → **Settings** → **Pages**
2. Under **Build and deployment** → **Source**, choose **Deploy from a branch**
3. Select branch: `main` and folder: `/ (root)`
4. Click **Save**

The site will be available at  
`https://allanvarghese567-lab.github.io/sql-to-erd/` within a minute or two.
