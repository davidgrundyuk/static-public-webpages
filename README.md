# Static Public Webpages

Simple standalone webpages, hosted free with GitHub Pages.

**Live site:** https://davidgrundyuk.github.io/static-public-webpages/

> Everything in this repository is public. Don't put anything private in it.

## Adding a page

**Single file:** add `my-page.html` to the top level. It will be at
`https://davidgrundyuk.github.io/static-public-webpages/my-page.html`

**Page with images or other files:** make a folder, name the page `index.html`, and put its files next to it:

```
my-page/
  index.html
  photo.jpg
```

It will be at `https://davidgrundyuk.github.io/static-public-webpages/my-page/`

Changes go live about a minute after they're pushed. The home page lists every page automatically.

### From the GitHub website

On the repository page, click **Add file → Upload files**, drag your files in, then click **Commit changes**.

### From this PC

The local copy is in `C:\Users\David\GitHub\static-public-webpages`. Add your files there, then run:

```
git add .
git commit -m "Add my-page"
git push
```

## Notes

- Files and folders whose names start with `_` or `.` are left off the home page list. They're still public if someone has the link.
- `.nojekyll` tells GitHub Pages to serve files exactly as they are. Leave it in place.
