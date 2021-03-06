# talk-template

A ready-to-fork template for talks, using [remark](https://github.com/gnab/remark), [KaTeX](https://github.com/Khan/KaTeX) and some customised CSS.

## Instructions

- Clone this repository:
```
git clone https://github.com/glouppe/talk-template.git
cd talk-template
```
- Start an HTTP server to serve the slides:
```
python -m http.server 8001
```
- Edit `talk.md` for making your slides.
- Use [decktape](https://github.com/astefanutti/decktape) for exporting your slides to PDF.

## Integration with GitHub pages

Slides can be readily integrated with [GitHub pages](https://pages.github.com/) by hosting the files in a GitHub repositery and enabling Pages in the Settings tab.

See e.g. [https://glouppe.github.io/talk-template](https://glouppe.github.io/talk-template) for this deck. 
