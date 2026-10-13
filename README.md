# fjia-xu.github.io

Source of Feiyu Jia's academic homepage, served by GitHub Pages at <https://fjia-xu.github.io>.
Plain HTML and CSS: no build step, no Jekyll, no dependencies.

```
index.html              the whole page (text, styles, and a small copy-button script)
assets/photo.jpg        portrait
assets/FeiyuJia_CV.pdf  CV (add it: the US version, without photo, keep this exact file name)
.nojekyll               tells GitHub Pages to serve the files as they are
```

## Publish it (about 10 minutes, one time)

1. **Add your CV.** In Overleaf, choose *Menu → Main document → FeiyuJia_CV_US.tex*, recompile,
   download the PDF, rename it `FeiyuJia_CV.pdf` and put it in the `assets` folder.
2. **Create the repository.** On GitHub: **New repository** → name it exactly
   `fjia-xu.github.io` → **Public** → **Create repository**.
3. **Upload the files.** On the new repository page choose **uploading an existing file**,
   then drag in `index.html`, `README.md`, `.nojekyll` and the whole `assets` folder
   (dragging the folder keeps the `assets/` path). Click **Commit changes**.
   On macOS, `.nojekyll` is hidden in Finder; press `Cmd + Shift + .` to show it. The site also works without it.
4. **Turn on Pages.** **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*,
   Branch = `main`, folder = `/ (root)` → **Save**.
5. Wait 1–2 minutes, then open <https://fjia-xu.github.io>. Check the photo, the CV link and the OpenReview link.
6. **Put the website on your CV.** In Overleaf, open `cv-content.tex` and uncomment the
   `fjia-xu.github.io` line in the header (it was left out because the site was not live yet).

## Updating later

* **Text:** open `index.html` on GitHub, click the pencil icon, edit, **Commit changes**. The site refreshes within a minute or two.
* **CV:** upload a new `assets/FeiyuJia_CV.pdf` with the same name; it replaces the old one.
* **News:** add a new `<li>` at the top of the News list, copying the format of the existing items.
* **When a paper is accepted:** change `<span class="status review">Under review</span>` to
  `<span class="status published">Published</span>`, update the venue, and add arXiv / PDF / Code buttons
  (copy the `<a class="btn" href="...">OpenReview</a>` pattern).
* **Google Scholar / OpenReview:** two prepared lines sit in a comment in the contact list near the top of
  `index.html`. Uncomment them once you want them shown (add your real Scholar link first).

Do not post the anonymous review PDFs. The DSD-Sim submission PDF forbids sharing it during review.
Link the OpenReview page or a public arXiv version instead, after checking with Prof. Zhang.
