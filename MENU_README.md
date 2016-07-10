Folding, multi-level sidebar added.

The following files are adapted from code found in the [Docker Docs theme](https://github.com/docker/docs-base):

  1. `/layouts/partials/navbar.html`          (Copied verbatim)
  2. `/layouts/partials/navbar-inner.html`    (Copied, class `currentPage` renamed to `current` to match existing CSS)
  3. `/static/menu.js`                        (Copied verbatim)
  4. `/static/stylesheets/menu.css`           (Copied & adapted fragments from `documentation.css`)

[The Docker Docs theme is under the Apache 2.0 License.](https://github.com/docker/docs-base/blob/master/LICENSE) .

The `menu.js` uses JQuery (`jquery-3.0.0.min.js`) which is under the MIT license.