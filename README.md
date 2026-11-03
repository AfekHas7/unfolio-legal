# Unfolio — Legal

The Privacy Policy and Terms of Service for the [Unfolio](https://github.com/AfekHas7)
app, published via GitHub Pages so the in-app and App Store links resolve:

| Document | English | עברית |
| --- | --- | --- |
| Privacy Policy | [privacy-policy-en](https://afekhas7.github.io/unfolio-legal/privacy-policy-en/) | [privacy-policy-he](https://afekhas7.github.io/unfolio-legal/privacy-policy-he/) |
| Terms of Service | [terms-en](https://afekhas7.github.io/unfolio-legal/terms-en/) | [terms-he](https://afekhas7.github.io/unfolio-legal/terms-he/) |

## Don't edit the markdown here

The four `*.md` files are **generated**. The source of truth is `legal/*.md` in
the private Unfolio app repo; this repo holds a copy with Jekyll front matter
prepended. To publish a change:

```sh
# in the app repo
tool/sync_legal.sh ../unfolio-legal
# then here
git add -A && git commit -m 'docs: sync legal text' && git push
```

Editing a document here directly will be overwritten on the next sync.

The site layout (`_layouts/legal.html`) and styles (`assets/legal.css`) *are*
maintained in this repo.
