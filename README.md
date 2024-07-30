# vite-github-pages-template
A just-enough template for throwing javascript into github pages

# Deploy

Just push to master and the github action will build into the `gh-pages` branch.

Make sure you have Pages enabled on your repository pointing at `gh-pages` branch from `/` root.

# Local development

Make sure node is installed and updated, then after cloning and cding into the project:

```
npm install
npm run dev
```

Vite should handle automatically re-serving files as they change.

# After building a repo from the template

Look for instances of "Vite App" and "vite-template" to rename to something more appropriate.
