When creating pages in the Atomic Learning Platform, you may wish to include either in-line snippets of code or code blocks which span several lines in the `content.md` file.

# In-line code snippets

To create an inline code snippet, wrap the code in three backticks. This can be followed by a set of curly braces containing a period, then the name of the language to be used to highlight the code snippet. For example, the code snippet `console.log("Hello, World!");`{.javascript} was created using the following Markdown source code:

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

The languages supported for syntax highlighting in the Atomic Learning Platform are listed in the table below, along with their corresponding identifiers to be used in the Markdown source code.

<table>
    <thead>
        <tr>
            <th>Language</th>
            <th>Identifier</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>Bash</td><td>bash</td></tr>
        <tr><td>C</td><td>c</td></tr>
        <tr><td>C++</td><td>cpp</td></tr>
        <tr><td>C#</td><td>csharp</td></tr>
        <tr><td>CSS</td><td>css</td></tr>
        <tr><td>Diff</td><td>diff</td></tr>
        <tr><td>Go</td><td>go</td></tr>
        <tr><td>GraphQL</td><td>graphql</td></tr>
        <tr><td>INI (includes TOML)</td><td>ini</td></tr>
        <tr><td>Java</td><td>java</td></tr>
        <tr><td>JavaScript</td><td>javascript</td></tr>
        <tr><td>JSON</td><td>json</td></tr>
        <tr><td>Kotlin</td><td>kotlin</td></tr>
        <tr><td>Less</td><td>less</td></tr>
        <tr><td>Lua</td><td>lua</td></tr>
        <tr><td>Makefile</td><td>makefile</td></tr>
        <tr><td>Markdown</td><td>markdown</td></tr>
        <tr><td>Objective-C</td><td>objectivec</td></tr>
        <tr><td>Perl</td><td>perl</td></tr>
        <tr><td>PHP</td><td>php</td></tr>
        <tr><td>PHP Template</td><td>php_template</td></tr>
        <tr><td>Plain Text</td><td>plaintext</td></tr>
        <tr><td>Python</td><td>python</td></tr>
        <tr><td>Python REPL</td><td>python_repl</td></tr>
        <tr><td>R</td><td>r</td></tr>
        <tr><td>Ruby</td><td>ruby</td></tr>
        <tr><td>Rust</td><td>rust</td></tr>
        <tr><td>SCSS</td><td>scss</td></tr>
        <tr><td>Shell</td><td>shell</td></tr>
        <tr><td>SQL</td><td>sql</td></tr>
        <tr><td>Swift</td><td>swift</td></tr>
        <tr><td>TypeScript</td><td>typescript</td></tr>
        <tr><td>VB.NET</td><td>vbnet</td></tr>
        <tr><td>WebAssembly</td><td>wasm</td></tr>
        <tr><td>XML (includes HTML aliases)</td><td>xml</td></tr>
        <tr><td>YAML</td><td>yaml</td></tr>
    </tbody>
</table>

If you would like to use a language that is not on the list, contact the Atomic Learning team.
