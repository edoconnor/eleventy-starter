# eleventy-starter

Minimal Eleventy starter template with `src/_includes` structure.

## Structure

```
src/
  _includes/
    partials/
      header.njk
      footer.njk
    base.njk
  assets/
    styles.css
  index.md
  about.md
.eleventy.js
package.json
```

## Clone

```bash
gh repo clone edoconnor/eleventy-starter my-new-project
cd my-new-project
npm install
npm start
```

## Usage

```bash
npm install
npm start     # dev server at localhost:8080
npm run build # output to /dist
```

## Save to your Github

```bash
git remote remove origin
git remote add origin https://github.com/their-username/their-project.git
git push -u origin main
```
