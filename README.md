# SolaChat i18n

This repository contains translation files for the SolaChat interface. It is maintained by the SolaChat organization and welcomes contributions from the community.

## Project Structure

Each supported language is placed in its own folder, using the language code as the folder name. Inside each folder is a single JSON file with the same name as the language code.

Example:
```
en/en.json
ru/ru.json
es/es.json
```

## Contributing

We welcome translation contributions in any language.

To contribute:

1. Fork the repository
2. Copy the `en/en.json` file into a new folder for your language (e.g., `fr/fr.json`)
3. Translate the content while keeping the structure and keys unchanged
4. Submit a pull request

### Guidelines

- Do not modify or remove any translation keys
- Preserve placeholders such as `{{username}}`, `{{count}}`, and `{{time}}`
- Ensure the JSON format is valid (you can use a linter or validator)

## Licensing

All translation files are licensed under the MIT License. See the `LICENSE` file for details.
