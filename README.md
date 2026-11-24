# Portfolio — Test Site

A sandbox copy of the live portfolio for trying out new features.

- **Test site:** https://nicolewalker314.github.io/portfolio-test/
- **Live site:** https://nicolewalker314.github.io/ (repo `nicolewalker314.github.io`)

Changes here never affect the live site.

## Trying a change

1. Edit `index.html` in this folder and save.
2. Double-click `index.html` to preview it on your computer.
3. To put it on the test site, run in PowerShell from this folder:

   ```
   git commit -am "Try new feature"
   git push
   ```

   The test site updates within a minute or two.

## Moving a finished feature to the live site

Copy the changed parts of this `index.html` into `portfolio-site\index.html`, commit and push from there.

**Don't copy the `<meta name="robots" content="noindex, nofollow">` line.** It's there only to keep search engines from listing the test site. On the live site it would hide your portfolio from Google.
