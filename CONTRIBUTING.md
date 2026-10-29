# Contributing to ZemDomu Meta

Meta is the community entry point for ZemDomu. You can improve the getting-started
links, clarify how the products fit together, or share questions and examples.

## Choose a destination

Use the repository for the workflow that exposed a product bug or feature need:

- [Extension issues](https://github.com/Zemdomu/ZemDomu-extension/issues): VS Code commands, settings, diagnostics, and quick fixes.
- [Core issues](https://github.com/Zemdomu/ZemDomu-core/issues): CLI, Node.js API, and shared analysis behavior.
- [Action issues](https://github.com/Zemdomu/ZemDomu-action/issues): GitHub Actions configuration and CI reporting.
- [Meta issues](https://github.com/Zemdomu/ZemDomu/issues): broken community links or incorrect guidance in this repository.
- [Meta discussions](https://github.com/Zemdomu/ZemDomu/discussions): questions, examples, and feedback across products.

Search existing issues or discussions first. For a product report, include the
version or Action ref, workflow, expected and actual results, and a minimal
reproduction with private code, credentials, personal data, and identifying
paths removed. Do not upload private project archives or unsanitized CI logs.
See [SECURITY.md](SECURITY.md) for suspected vulnerabilities and follow the
[code of conduct](CODE_OF_CONDUCT.md).

## Improve the community documentation

Open an issue to discuss a substantial change, then keep your pull request
focused on one problem. Explain who the change helps and check the linked
product's current documentation before changing setup instructions or claims.
Use small public examples and describe the limits of static analysis.

This repository has no application build or automated test suite. For a
pull request, check the rendered Markdown, links, and example commands against
the owning product documentation. State what you checked and flag anything
you could not verify. Add customer-relevant changes to the appropriate
category in the unreleased changelog.
