## Jinja Snippets Flask for VSCode

***"Jinja Snippets Flask" is a powerful and comprehensive extension designed to boost your productivity when working with Flask and Jinja in Visual Studio Code. This extension provides a rich collection of code snippets that cover a wide range of Jinja template engine functionalities, from basic template structures to complex control flows. Whether you're building a simple web application or a complex web service with Flask, our snippets can help you write Jinja templates faster and with fewer errors. The snippets include shortcuts for blocks, extends, imports, loops, conditional statements, macros, filters, comments, and much more.***


***Jinja*** is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax. Then the template is passed data to render the final document.


## Getting started

To start using the snippets simply type **j.** *snippet_name*.
* Example: `j.html` For
``` jinja
<!DOCTYPE html>
<html lang="en">
<head>
    {% block head %}
        <link rel="stylesheet" href="style.css" />
        <title>{% block title %}{% endblock %} - My Webpage</title>
    {% endblock %}
</head>
<body>
    <div id="content">{% block content %}{% endblock %}</div>
    <div id="footer">
        {% block footer %}
            &copy; Copyright 2024 by <a href="https://hackerwasii.com/">Waseem Akram💙</a>.
        {% endblock %}
    </div>
</body>
</html>
```
* To preview the selected snippet click `CTRL+SPACEBAR`.  
* To use the selected snippet simply click `TAB`.


## Features
>All snippets support **Tabstops**  
>Some snippets providing **Placeholders**  
>some snippets like `j.imp` support **Choice**

## Key Features:

Key Features:
- Comprehensive set of Jinja2 snippets for Flask applications.
- Easy to use: just type the prefix and select the snippet from the IntelliSense suggestions.
- Covers a wide range of Jinja2 functionalities, from basic to advanced.
- Helps write code faster and reduces the chance of errors.
- Constantly updated with new snippets and improvements.

### Snippets

* `j.base` - Base Template
* `j.block` - Block
* `j.ext` - Extends
* `j.imp` - Import
* `j.for` - For Loop
* `j.if` - If Statement
* `j.elif` - Elif Statement
* `j.else` - Else Statement
* `j.macro` - Macro
* `j.set` - Set
* `j.call` - Call
* `j.filter` - Filter
* `j.include` - Include
* `j.comment` - Comment
* `j.raw` - Raw
* `j.autoescape` - Autoescape
* `j.with` - With
* `j.do` - Do
* `j.super` - Super
* `j.end` - End

***and many more...***

## Installation

1. Open **Extensions** sidebar panel in Visual Studio Code. `View → Extensions`
2. Search for `Jinja Snippets Flask`
3. Click **Install** to install it.
4. Click **Reload** to reload your editor
5. Code > Preferences > File Icon Theme > **Jinja Snippets Flask**
6. Open a Jinja file or HTML file and start typing!
7. Alternatively, Open Visual Studio Code
8. Press `Ctrl+P` to open the Quick Open dialog
9.  Type `ext install WaseemAkram.jinja-snippets-flask` to find the extension
10. Click the `Install` button, then the `Enable` button
11. Alternatively, you can install the extension from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=WaseemAkram.jinja-snippets-flask)

## Contributing

If you have suggestions for improving the BashSnippets, please [open an issue or
submit a pull request](https://github.com/evildevill/Jinja-snippets-vsce.git).

## License

[MIT](LICENSE) © Waseem Akram

## Support

If you like this extension, you can support me by:

- Star this repository on [GitHub](https://github.com/evildevill/Jinja-snippets-vsce.git)
- [Follow me on GitHub](https://github.com/evildevill)
- [Support me on Patreon](https://www.patreon.com/hackerwasii)
- [Follow me on Facebook](https://facebook.com/hackerwasii)
- [Follow me on Instagram](https://instagram.com/wasii_254)
- Your support is greatly appreciated! 💙

**Enjoy!**

**[Waseem Akram](https://hackerwasii.com)**
