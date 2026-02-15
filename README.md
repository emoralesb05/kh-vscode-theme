# KH Theme Pack

Subtle, accessibility-minded fantasy-inspired dark themes for VS Code.

## Themes

- **KH Gold (Subtle)**: midnight navy base, warm gold accents, crystal-cyan highlights.
- **KH Silver (Subtle)**: steel-blue dark base, silver UI framing, restrained gold cues.

## Install Locally

```bash
pnpm install
pnpm exec vsce package
```

Then in VS Code: **Extensions -> ... -> Install from VSIX...** and select the generated `.vsix`.

## Publish

```bash
pnpm exec vsce login <your-publisher-id>
pnpm exec vsce publish
```

Publisher setup docs: https://code.visualstudio.com/api/working-with-extensions/publishing-extension

## Notes

- Theme tokens cover core VS Code chrome, editor, diagnostics, and git/testing status semantics.
- Some extension webviews (chat panels, custom dashboards) may only partially inherit theme tokens.


## Disclaimer

This is an independent, fan-made theme pack. It is not affiliated with, endorsed by, or sponsored by any game studio or publisher.
