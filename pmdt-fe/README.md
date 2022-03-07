# PMDT FE Practical
This starter uses [Parcel](https://parceljs.org/), a zero config build tool. By default it handles compiling and bundling languages such as Sass and JavaScript. 

## Getting Started

There are two npm scripts defined in `package.json`:
- `dev`: runs the development server, which includes watching your files and rebundling
- `build`: builds a production output of your project

To get started:

```bash
# Run dev server
npm run dev
# or run dev server & opens in your browser
npm run dev -- --open 
```

## Project Structure

### `src/`
Your main project code should go here. The files here can by reorganized however you want, but keep in mind that Parcel needs to at least know where the entry point of your project is. Keeping `index.html` where it is will solve that issue, or you can update the `dev` npm script to use a differnt entry file path.

### `src/assets/`
Any assets such as images can go here. In Parcel, these files can be used in your markup as expected, by using a typical relative path. 

### `dist/`
Parcel's build output (created automatically). This is what is served by the dev server.