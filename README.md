Markdown to HTML Render
===

A simple markdown render using [GitHub Markdown Rendering API](http://developer.github.com/v3/markdown).

It converts a Markdown file to ready-to-view HTML file.

### Usage
```python
python render_markdown.py <input> [<output>]
```

#### Options:

	<input>:
        Markdown file to render.

	<output>:
        Output file to save rendering. Optional.

### Example
```bash
python render_markdown.py README.md out.html
```