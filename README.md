# KH Theme Pack

Subtle, accessibility-minded KH-inspired dark themes for VS Code.

## Themes

- **KH Gold (Subtle)**: midnight navy base, keyblade-gold accents, crystal-cyan highlights.
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

This is a fan-made, KH-inspired theme pack. It is not affiliated with, endorsed by, or sponsored by Disney or Square Enix.
