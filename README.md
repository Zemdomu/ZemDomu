# [ZemDomu](https://zemdomu.dev/)

Catch supported semantic HTML and accessibility defects in HTML, JSX, TSX,
React, and Vue source through VS Code, the CLI, or GitHub Actions.

Cross-component analysis follows statically resolvable local React and Vue
imports to find supported structural conflicts hidden across files. Use it
alongside rendered, keyboard, and assistive-technology testing.

## See a cross-component finding

![VS Code finding a skipped heading level across React components, then clearing the diagnostic after h3 is changed to h2.](https://zemdomu.dev/zemdomu-header-order-readme.gif)

The page and its imported component can each look reasonable on their own.
ZemDomu follows supported imports so heading-order diagnostics can include
their composed source context.

## Try ZemDomu

| Where you work | Start here | Source and issues |
| --- | --- | --- |
| VS Code | [Install the extension](https://marketplace.visualstudio.com/items?itemName=ZachariasErydBerlin.zemdomu) | [Extension repository](https://github.com/Zemdomu/ZemDomu-extension) |
| Terminal or Node.js | [Install the npm package](https://www.npmjs.com/package/zemdomu) | [Core repository](https://github.com/Zemdomu/ZemDomu-core) |
| Pull requests | [Add the GitHub Action](https://github.com/Zemdomu/ZemDomu-action#quick-start) | [Action repository](https://github.com/Zemdomu/ZemDomu-action) |

For a CLI scan, use Node.js 22.17 or newer:

```bash
npx zemdomu check "src/**/*.{html,jsx,tsx,vue}" --format pretty
```

Add `--cross --cross-depth 3` to follow supported local component imports.
See the [installation guides](https://zemdomu.dev/docs/installation) for each
workflow and the [rule reference](https://zemdomu.dev/docs) for detection limits.

## Feedback and contributions

Use the product repository above for bugs and feature requests. Include the
version, file type, expected result, and a small reproduction with private
source and credentials removed. False positives and missed findings are useful
reports too.

For questions, examples, or feedback across products, use
[Meta discussions](https://github.com/Zemdomu/ZemDomu/discussions) or
[Meta issues](https://github.com/Zemdomu/ZemDomu/issues). This repository is the
community entry point; the implementation lives in the product repositories.

## Support ZemDomu

If ZemDomu is useful to you, consider starring the repository for the tool you
use: [Extension](https://github.com/Zemdomu/ZemDomu-extension/stargazers),
[Core](https://github.com/Zemdomu/ZemDomu-core/stargazers), or
[Action](https://github.com/Zemdomu/ZemDomu-action/stargazers).
You can also [star Meta](https://github.com/Zemdomu/ZemDomu/stargazers) to keep
this community entry point handy.

## License

MIT (c) 2025 Zacharias Eryd Berlin
