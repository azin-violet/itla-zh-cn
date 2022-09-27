# Introduction to Linear Algebra Chinese translation

The Chinese translation for the book&mdash;Introduction to Linear Algebra written by Gilbert Strang.

## Requirements

Bulid this book locally requires [mdbook], to get it:

[mdbook]: https://github.com/rust-lang-nursery/mdBook

```bash
$ cargo install mdbook
```

## Building 

To build the book, type:

```bash
$ mdbook build
```

The output will be in the `book` subdirectory. You can open it in web browser.

_Firefox:_
```bash
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

_Chrome:_
```bash
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```
