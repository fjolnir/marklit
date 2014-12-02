marklit
=======

A little tool for writing literate C code using markdown.

Any line starting with `\s*///` gets treated as markdown, anything else, as code.

## Usage:
```sh
# Markdown output (With github language annotation):
$ cat my_file.c | marklit --github-flavor > output.md
# HTML output (Requires python, with Pygments and markdown installed)
$ cat my_file.c | marklit-html > output.md
```
