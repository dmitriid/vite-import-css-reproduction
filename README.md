## Bug description

In watch mode vite doesn't rebuild CSS if an `@import`ed file changes.

If you change the root CSS file, the re-build happens as expected.

## This repo

This repo closely follows my current setup with respect to location of files, but I don't think there's anything out of the ordinary.

## To run

```
> cd assets
> npm run watch
```

Results are in `priv/static/css/app.css`

Try changing `assets/css/components/card.css`. Nothing happens.

Try changing `assets/css/app.css`. The CSS is rebuilt.
