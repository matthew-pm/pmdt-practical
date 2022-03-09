# PMDT FE Practical
This starter uses [Parcel](https://parceljs.org/), a zero config build tool. By default it handles compiling and bundling languages such as Sass and JavaScript. 

## Getting Started

There are two npm scripts defined in `package.json`:
- `dev`: runs the development server, and handles watching your files and bundling
- `build`: builds a production output of your project

To get started:

```bash
# Install dependencies
cd pmdt-fe
npm install 

# Run dev server
npm run dev
# or run dev server & open in your browser
npm run dev -- --open 
```

## Project Structure

### `src/`
Your main project code should go here. The files here can by reorganized however you want, but keep in mind that Parcel needs to at least know where the entry point of your project is. Keeping `index.html` where it is will solve that issue, or you can update the `dev` npm script to use a different entry file path.

Note: if you use the `html-include` feature, any HTML file you include with `<include src="<file>.html">...` will have it's path references relative to the file it's "included" within.

### `src/images/`
All the image files from the design have been exported and processed for you, and placed into this directory.

Note:
- `crown-crafted-stealth-logo.svg` is the "Crown Sport: Stealth Series" logotype to use for the hero overlay
- `stealth-1.jpg` corresponds to the first image below the hero, and so on
- `...-mobile.jpg` files are the versions of the images that should be rendered on mobile-sized screens

---

Note: the `.gitignore` at the root of the _project_ repo has been configured to sensibly ignore folders within this directory as well.
