## About
Bootstrap v5 css utility framework integrates with [AEMO Design Tokens](https://github.com/danielwang/aemo-design-tokens)

### Utility list
- Root css var
- Background
- Borders
- Colors
- Display
- Flex
- Float
- Interactions
- Opacity
- Overflow
- Position
- Shadows
- Sizing
- Spacing
- Text
- Vertical align
- Visibility



## Scripts

```shell
# Compile Sass
npm run css-compile

# Watches Sass for changes and starts a local server
npm start
```

The following npm scripts are available to you in this starter repo. With the exception of `npm start` and `npm test`, the remaining scripts can be run from your command line with `npm run scriptName`.

| Script | Description |
| --- | --- |
| `server` | Starts a local server (<http://localhost:3000>) for development |
| `watch` | Automatically recompiles CSS as it watches the `scss` directory for changes |
| `css` | Runs `css-compile` and `css-prefix` |
| `css-compile` | Compiles source Sass into CSS |
| `css-lint` | Runs [Stylelint](https://stylelint.io) against source Sass for code quality |
| `css-prefix` | Runs [Autoprefixer](https://github.com/postcss/autoprefixer) on the compiled CSS |
| `css-purge` | Runs [PurgeCSS](https://purgecss.com) to remove CSS that is unused by `index.html` |
| `test` | Runs `css-lint` and `css`, in sequential order |

