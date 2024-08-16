---
package_name: "lower-upper"
package_title: "Lower and UPPER case"
package_desc: "A simple package to convert clipboard content to lower case, UPPER case or Capitalize. (UNIX only)"
package_version: "0.1.0"
package_author: "Anthony Graignic"
package_repo: "https://github.com/anthonygraignic/espanso-package-lower-upper"
---

# Espanso lower UPPER

A simple espanso package to convert clipboard content to lower case or UPPER case using the [tr](https://man7.org/linux/man-pages/man1/tr.1.html) command and [sed](https://man7.org/linux/man-pages/man1/sed.1p.html) command of GNU coreutils.

## Installation

Make sure you have already installed [Espanso](https://espanso.org/install/) first.

```sh
espanso install lower-upper
espanso restart
```

## Usage

Available replacements:

| replacement | description                     |
| ----------- | ------------------------------- |
| ::low       | Convert clipboard to lowercase. |
| ::up        | Convert clipboard to UPPERCASE. |
| ::cap       | Convert clipboard to Capitalized. |

## Package details

Repository: [https://github.com/anthonygraignic/espanso-package-lower-upper](https://github.com/anthonygraignic/espanso-package-lower-upper)
