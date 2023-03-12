# Espanso Serbian Accent Letters

Simple package to extend [Espanso](https://espanso.org) with accented latin letters used in Serbian language.

In Serbian, the term "truncated" or "bald" letters (ošišana ili ćelava latinica) is used for latin letters that are missing accent marks but should be written with them. If you find it difficult to correctly enter proper Serbian latin letters with accents (latinična slova sa kvačicama) in your keyboard layout, you should use this package.

- caron letters (čČššžŽ),
- acute accent letters (ćĆ),
- crossed D, D with stroke, crossbar letter D (đĐ)

## Installation

Before installing this package, please ensure that you have already installed [Espanso](https://espanso.org/install).

To install package from the [Espanso Hub](https://hub.espanso.org/), run the following command:

```sh
espanso install serbian-accents
```

Alternatively, you can install the package directly from it's repository using the following command:

```sh
espanso install serbian-accents --git https://github.com/cvladan/espanso-serbian-accents-package --external
```

Please note that you need to have a valid Git installation for the second method.

You are now ready to start using the package.

## Usage

To get the desired replacement, simply type in the corresponding keyword and the package will automatically replace it with the correct accented Latin letter used in the Serbian language. If you need to capitalize the accented letter, type the combination in the capital letter and the package will automatically replace it with the corresponding capitalized accented letter.

| Keyword                         | Replaced |
| ------------------------------- | -------- |
| `c~` or `cz~`                   | "č"      |
| `s~`                            | "š"      |
| `z~`                            | "ž~`     |
| `c~` or `cc~` or `ch~` or `ci~` | "ć"      |
| `d~`                            | "đ"      |

## 📄 License

This espanso package is licensed under the [MIT](https://github.com/cvladan/espanso-serbian-accents-package/blob/main/LICENSE)

###### Synonyms and Search Tags

> letters with diacritical marks, diacritic letters, diacritics, diacritical marks, diacritical signs, accents, accent marks, accented characters, accents and diacritical marks, adding glyph to a letter
