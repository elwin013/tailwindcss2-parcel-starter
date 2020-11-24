# TailwindCSS 2.x Parcel 1.x Starter project

Just a starter of [Tailwind CSS](https://tailwindcss.com) (2.x) and [ParcelJS](https://parceljs.org) project.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/elwin013/tailwindcss2-parcel-starter)


## Getting started

```
# Clone repo
git clone https://github.com/elwin013/tailwindcss2-parcel-starter
cd tailwindcss2-parcel-starter

# Install deps
npm install

# Run dev server - available at http://localhost:1234
npm run start

# Run production build - production files in dist/ directory
npm run build
```

## JetBrains IDE Support without plugins

If you want to have TailwindCSS support in Intellij/WebStorm etc. please run:

```
npm run tailwind
```

which will create `.tailwind/tailwind.css` file with all classes. Unfortunately
there is size limit of files that can be indexed - to fix that just add this:

```
idea.max.intellisense.filesize=5000
```

to custom properties. You can do this by selecting in menu: `Help -> Edit custom properties`

## Parcel 2.x

You can easily start with new Parcel - just run:

```
npm uninstall parcel-bundler
npm install -D parcel@next
``` 

everything mentioned above should work the same.


## Mentions

Photo used in example made by <a href="https://unsplash.com/@leonsa">Leonsa</a>, see it on <a href="https://unsplash.com/photos/fVNyjet1CXY">Unsplash</a></span>

## Contribute
You're interested in contributing? Awesome! Fork, make change, commit and create pull request. I'll do my best to merge changes!

## License
[MIT](LICENSE)
