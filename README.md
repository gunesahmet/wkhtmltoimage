# wkhtmltoimage

Windows binaries of wkhtmltoimage / wkhtmltopdf used by FPanel.

Website: https://fpanel.net

## Branch workflow

- `main` and `dev` are protected: nobody pushes to them directly.
- Create your own branch from `dev` (for example `feature/short-name` or `fix/short-name`).
- Push your branch and open a pull request into `dev`.
- A pull request needs one approval before it can be merged.
- `dev` is merged into `main` through a pull request for releases.

## License

wkhtmltopdf / wkhtmltoimage are third-party software by the wkhtmltopdf authors, distributed under the GNU Lesser General Public License v3.0 (see `LICENSE` and `COPYING`). Upstream: https://wkhtmltopdf.org
