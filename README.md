# Cherry Belts

The source of the Fern docs site at https://cherry-belts.docs.buildwithfern.com.

## Edit the docs

- The pages are in `fern/docs/pages/`.
- The navigation, theme and logo are in `fern/docs.yml`.

## Preview and publish

```bash
npm install -g fern-api
fern docs dev            # preview the site on your computer
fern generate --docs     # publish the site
```

If the repository has `.github/workflows/publish-docs.yml`, each push to the default branch publishes the site.

See the [Fern Docs guide](https://buildwithfern.com/learn/docs/getting-started/overview) for more.
