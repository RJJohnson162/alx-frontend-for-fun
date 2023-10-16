# markdown2html.py

## Overview

`markdown2html.py` is a Python script that converts Markdown files to HTML. It provides a command-line interface for converting Markdown documents to HTML format. This tool can be useful for generating HTML files from Markdown content.

## Requirements

- Python 3.7 or higher
- Markdown file as input
- Output HTML file

## Usage

To use `markdown2html.py`, follow these steps:

1. Clone or download this repository to your local machine.

2. Open a terminal or command prompt.

3. Run the script with the following command:

    ```shell
    ./markdown2html.py <input_markdown_file> <output_html_file>
    ```

<input_markdown_file>: The name of the Markdown file you want to convert.
<output_html_file>: The name of the HTML file where the converted content will be saved.
If the Markdown file exists and the conversion is successful, you will find the HTML output in the specified output file.
Example

```shell
    ./markdown2html.py README.md README.html
```

This command converts the README.md Markdown file into an HTML file named README.html.

Features
Converts Markdown headings to HTML <h1> to <h6> tags.
Converts Markdown unordered lists to HTML <ul> and <li> tags.
Converts Markdown ordered lists to HTML <ol> and <li> tags.
Supports Markdown bold syntax (**text**) and italic syntax (**text**).
Replaces [[]] syntax with the MD5 hash of the enclosed text.
Removes the letter 'C' from ((text)) syntax.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Author
This script was created by [Marubi N Richard].

Feel free to contribute or report issues on GitHub: Link to GitHub Repository

Support
If you have any questions or need assistance, please contact [richardnyamwamu@gmail.com].

Enjoy using markdown2html.py to convert your Markdown documents into HTML effortlessly!
