# PostHTML

> [PostHTML](https://posthtml.org/) snippets for VS Code.

![Snippets preview animation](https://github.com/cossssmin/vscode-posthtml/raw/master/media/screenshot.gif)


## Install

```sh
$ ext install posthtml
```

Or, `F1` → `Install Extension` → Search for `posthtml`


## Snippets

The following snippets are included:

For [posthtml-extends](https://github.com/posthtml/posthtml-extend):

- `<extends src="">`
- `<layout src="">` (`extends` alias)

* `<block name="">`
* `<block name="" type="">`

For [posthtml-expressions](https://github.com/posthtml/posthtml-expressions):

- `<if condition="">`
- `<elseif condition="">`
- `<else>`
- `<each loop="{value}, {index} in {array}">`
- `<each loop="{value}, {key} in {object}">`
- `<for loop="{value}, {index} in {array}">`
- `<for loop="{value}, {key} in {object}">`
- `<switch expression="">`
  - `<case n="">`
  - `<default>`
- `<scope with="">`
- `<raw>`, `<verbatim>`

For [posthtml-include](https://github.com/posthtml/posthtml-include):

- `<include src="" locals="">`

For [posthtml-modules](https://github.com/posthtml/posthtml-modules):

- `<module href="" locals="">`

For other plugins:

- `<component src="">` (modules in [maizzle.js](https://maizzle.com))
- `<spaceless>` ([posthtml-spaceless](https://github.com/posthtml/posthtml-spaceless))
- `<lorem size="">` ([posthtml-lorem](https://github.com/jonathantneal/posthtml-lorem))
- `<markdown>`, `<md>` ([posthtml-md](https://github.com/jonathantneal/posthtml-md), [posthtml-markdown](https://github.com/OzymandiasTheGreat/posthtml-markdown), [posthtml-md2html](https://github.com/posthtml/posthtml-md2html))

## Usage

Start writing a snippet's `prefix` (tag name) and then press <kbd>Tab ↹</kbd> to expand the snippet.

## License

MIT © [Cosmin Popovici](https://github.com/cossssmin)
