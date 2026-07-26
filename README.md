# Monobrut

A dark, high-contrast theme for [Zed](https://zed.dev/) with concrete-black
surfaces, crisp borders, and a classic Monokai-inspired syntax palette.

![Monobrut theme in Zed with a Go service, project navigation, and terminal](assets/monobrut.png)

## Themes

- **Monobrut** is the default: a warmer palette deliberately close in feel to
  Monokai Pro, using independently chosen colors.
- **Monobrut Dark** keeps the original concrete-black palette.

## Installation

Once published in the Zed extension registry:

1. Open Zed Extensions with `ctrl-shift-x`.
2. Search for **Monobrut** and install it.
3. Open the theme selector with `cmd-k cmd-t` on macOS or `ctrl-k ctrl-t` on
   Linux and Windows.
4. Select **Monobrut**.

To try the development version, clone this repository and run
`zed: install dev extension` from Zed's command palette, then select the cloned
directory.

## Development

The theme lives in [`themes/monobrut.json`](themes/monobrut.json) and follows
Zed's [theme schema](https://zed.dev/schema/themes/v0.2.0.json).

## Attribution

The palette and syntax conventions are adapted from Visual Studio Code's
classic Monokai theme. See [Third-Party Notices](THIRD_PARTY_NOTICES.md).

## License

[MIT](LICENSE)
