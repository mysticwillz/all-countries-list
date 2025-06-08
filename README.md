# all-countries-list

**A comprehensive array of all countries with ISO 3166-1 alpha-2 codes, Unicode representations, country dial code and emoji flags.**

## 🌍 Overview

This package provides a complete list of countries along with their respective:

- Country name
- ISO 3166-1 alpha-2 code
- Unicode flag representation
- Emoji flag

Useful for internationalization (i18n), dropdowns, flag displays, and more.

## 📦 Installation

```bash
npm install all-countries-list
```

or with Yarn:

```bash
yarn add all-countries-list
```

## 🚀 Usage

### JavaScript (CommonJS)

```js
const countries = require("all-countries-list");

console.log(countries[1]);
// {
//   name: 'Afghanistan',
//   code: 'AF',
//   unicode: 'U+1F1E6 U+1F1EB',
//   emoji: '🇦🇫',
//   dialCode:'+93'
// }
```

### JavaScript (ESM)

```js
import countries from "all-countries-list";

console.log(countries[1]);
// {
//   name: 'Afghanistan',
//   code: 'AF',
//   unicode: 'U+1F1E6 U+1F1EB',
//   emoji: '🇦🇫',
//   dialCode:'+93'
// }
```

### TypeScript (Optional Types)

```ts
import countries from "all-countries-list";

interface Country {
  name: string;
  code: string;
  unicode: string;
  emoji: string;
  dialCode: string;
}

const firstCountry: Country = countries[0];
```

## 📚 Data Format

Each country object has the following structure:

```ts
{
  name: string; // e.g., "Nigeria"
  code: string; // e.g., "NG"
  unicode: string; // e.g., "U+1F1F3 U+1F1EC"
  emoji: string; // e.g., "🇳🇬"
  dialCode: string; // e.g "+234"
}
```

## ✅ Example Use Cases

- Country selectors
- International shipping forms
- Travel applications
- Flag display utilities
- Locale-aware interfaces

## 📄 License

MIT

## 👤 Author

Eze Williams Ezebuilo

## 🛠 Contributing

Feel free to open issues or pull requests to help improve the data or add features!
