# Wenjie Lin Academic Homepage

This is a simple static academic homepage for GitHub Pages.

## File structure

```text
.
├── index.html
├── publications.html
├── notes.html
├── css/
│   └── style.css
├── images/
│   └── photo.jpg
└── pdffile/
    ├── cv.pdf
    ├── note.pdf
    ├── variational-analysis-note.pdf
    ├── manifold-optimization-note.pdf
    └── mpcc-note.pdf
```

## How to use

1. Upload all files to your GitHub repository.
2. Put your photo at `images/photo.jpg`.
3. Put your PDF files in the `pdffile/` folder.
4. Enable GitHub Pages:
   `Settings -> Pages -> Deploy from a branch -> main -> /root`.
5. Visit your GitHub Pages URL.

## Notes

- If you replace a PDF while keeping the same filename, the webpage links do not need to be changed.
- If you rename a PDF, update the corresponding `<a href="pdffile/xxx.pdf">` link in the HTML files.
