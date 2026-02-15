# Kingdom Hearts Theme Pack

Subtle, accessibility-minded Kingdom Hearts-inspired dark themes for VS Code.

## Themes

- **Kingdom Hearts Gold (Subtle)**: midnight navy base, keyblade-gold accents, crystal-cyan highlights.
- **Kingdom Hearts Silver (Subtle)**: steel-blue dark base, silver UI framing, restrained gold cues.

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
