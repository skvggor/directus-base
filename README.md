# directus-base

Studies on Directus CMS with the intention of using it in projects.

### Translation

Guide: https://docs.directus.io/guides/headless-cms/content-translations.html

#### Example of a request to get translations

```http
GET /items/Livros?deep[translations][_filter][languages_code][_eq]=en-US&fields=*,translations.*
```

## License

This project is licensed under the The GNU General Public License - see the [LICENSE](LICENSE) file for details.
