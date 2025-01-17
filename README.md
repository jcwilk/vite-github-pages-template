[![Run Tests](https://github.com/jcwilk/vite-github-pages-template/actions/workflows/test.yml/badge.svg)](https://github.com/jcwilk/vite-github-pages-template/actions?query=workflow%3A%22Run%20Tests%22)
(Fix this badge after forking from template)

# vite-github-pages-template
A just-enough template for throwing javascript into github pages

# Deploy

Just push to master and the github action will build into the `gh-pages` branch.

Make sure you have Pages enabled on your repository pointing at `gh-pages` branch from `/` root.

Note that this continuous deployment process is not blocked by the test suite failing. Adjust the `.github/workflows/deploy.yml` action configuration if you want this to work differently.

# Local development

Make sure node is installed and updated, then after cloning and cding into the project:

```
npm install
npm run dev
```

Vite should handle automatically re-serving files as they change.

# After building a repo from the template

You'll need to go into your repo settings, "Actions -> General", and set "Workflow permissions" to "Read and write permissions" in order for the included CI/CD actions to work.

Look for instances of "Vite App" and "vite-template" to rename to something more appropriate.

Also as per the note, fix the test build badge at the top of the README to point to the new user/repo.
