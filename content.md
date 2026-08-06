When creating pages in the Atomic Learning Platform, you may wish to include either in-line snippets of code or code blocks which span several lines in the `content.md` file.

# In-line code snippets

To create an inline code snippet, wrap the code in a pair of backticks. This can be followed by a set of curly braces containing a period, then the name of the language to be used to highlight the code snippet. For example, the code snippet `console.log("Hello, World!");`{.javascript} was created using the following Markdown source code:

```html
 ...the code snippet `console.log("Hello, World!")`{.javascript} was created...
```

# Code blocks

To insert a longer multi-line block of code, precede it with a set of triple backticks, followed by the name of the language to be used for highlighting. For example, this code block:

```python
def greet(name):
    print("Hello, " + name + "!")
```

was created using the following Markdown source code:

```
 ```python
 def greet(name):
    print("Hello, " + name + "!")
 ```
```

# Runnable Code Cells

For some languages, such as Python and R, the Atomic Learning Platform supports the inclusion of runnable code cells, which are detailed in pages in the Related Content section.

# Supported Languages for Highlighting

The languages supported for syntax highlighting in the Atomic Learning Platform are listed below, along with their corresponding identifiers to be used in the Markdown source code.

- Bash: `bash`
- C: `c`
- C++: `cpp`
- C#: `csharp`
- CSS: `css`
- Diff: `diff`
- Go: `go`
- GraphQL: `graphql`
- INI (includes TOML): `ini`
- Java: `java`
- JavaScript: `javascript`
- JSON: `json`
- Kotlin: `kotlin`
- Less: `less`
- Lua: `lua`
- Makefile: `makefile`
- Markdown: `markdown`
- Objective-C: `objectivec`
- Perl: `perl`
- PHP: `php`
- PHP Template: `php_template`
- Plain Text: `plaintext`
- Python: `python`
- Python REPL: `python_repl`
- R: `r`
- Ruby: `ruby`
- Rust: `rust`
- SCSS: `scss`
- Shell: `shell`
- SQL: `sql`
- Swift: `swift`
- TypeScript: `typescript`
- VB.NET: `vbnet`
- WebAssembly: `wasm`
- XML (includes HTML aliases): `xml`
- YAML: `yaml`

If you would like to use a language that is not on the list, contact the Atomic Learning team.
