# Resume

Resume of Samih Omer, built with Webpack + Pug + Postcss. (A fork from [Gosho's Repo](https://github.com/acro5piano/resume))

# Getting started

After checking out the repo, run: 

```
yarn install
yarn start
```

open http://localhost:3000 and you can see the resume.

# Write your resume with this template

Feel free to write your resume with this template, if you are odd enough to do so.

- `src/app.postcss` is for css
- `src/index.pug` is for template

# Screenshot

To take a screenshot, just run

- `yarn build:html`
- `yarn screenshot`

This runs your Chrome headlessly and take an image.

# Production build

To build all assets, run:

```
yarn build
```

This does:

- Bundle files with Webpack production mode
- Take screenshot as `png` and `pdf`

# TODO

- [x] Add script for taking screenshot.
- [x] Create GitHub page or something to render this as actual web page. → netlify
- [x] Add script for build. Generate multilingual PDF to `/dist`.
- [ ] Page too big to fit A4. Time to divide.
- [ ] Use React.js or Vue.js for template rendering. This is for HMR and scoped CSS and internationalization.
- [ ] Add ESLint for stability.
- [ ] Add Flow for type-safe and null-safe.
- [ ] Internationalization. currently I need `en` and `ja`. For the time being create `index.ja.pug`.
- [ ] `screenshot` command for all languages.
