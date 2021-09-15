# honkit-pdf-margin-settings-dont-work

**Install dependencies**

```bash
$ npm i
```

**Create PDF**

```bash
$ npx honkit pdf
```

I set the PDF setting in `book.json` like below.
But they're not reflected in `book.pdf`.

```bash
{
    "pdf": {
        "margin": {
            "top": 0,
            "right": 0,
            "bottom": 0,
            "left": 0
        }
    }
}
```
