# Markdown React (MDX) for Atom

Adds language support for [MDX](https://github.com/mdx-js/mdx).

![Скриншот 2019-08-24 12.56.31](https://i.imgur.com/gbFo4uk.png)

## Installation

- `apm install language-mdxjs`
- `apm install react` (if you don't already have it)

## Using Toolbar for Markdown Writer with `.mdx` files?

If you want to use [Toolbar for Markdown Writer](https://github.com/zhuochun/tool-bar-md-writer), make sure to add `scope.mdx` to the plugin's settings.

![Скриншот 2019-08-23 15.41.33](https://i.imgur.com/sk9qoz2.png)

## Applying MDX grammar to `.md` files?

By default the MDX language is applied only to `.mdx` files. If MDX files in your project end with `.md`, you create a custom file type in your `config.cson`:

```cson
core:
  customFileTypes:
    'source.mdx': [
      'md'
    ]
```

## Auto-close tags

If you want Atom to automatically close tags while you type, you can install [Auto Close Tag](https://atom.io/packages/autoclose).
