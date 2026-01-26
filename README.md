# Citizens Initiative

[**Live Demo**](https://citizens-initiative.surge.sh/)

A Hugo theme for citizen initiatives and advocacy, forked from [Calligraphy](https://github.com/pacollins/calligraphy).

## Features

- Clean, readable design with Zain font family
- Dark and light mode support
- Responsive layout
- Custom color scheme (dark blue, lime green accent)

## Getting Started

### Clone Repository

```shell
git clone https://github.com/dfrkp/citizens-initiative.git themes/citizens-initiative
```

### Submodule

```shell
git submodule add https://github.com/dfrkp/citizens-initiative.git themes/citizens-initiative
git submodule update --init --recursive
```

## Configuration

Add the theme to your Hugo site's config:

```toml
theme = "citizens-initiative"
```

## Development

To run the example site locally:

```shell
HUGO_THEME=citizens-initiative hugo server --source exampleSite --themesDir /path/to/themes
```

## Requirements

- Hugo 0.145.0 extended or later
- Dart Sass

## License

MIT License - see [LICENSE](LICENSE)

## Credits

- Original theme: [Calligraphy](https://github.com/pacollins/calligraphy) by Patrick Collins
- Font: [Zain](https://fonts.google.com/specimen/Zain)
