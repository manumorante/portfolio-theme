# theme

> 🚧 Work in progress - Experimenting.

Tailwind CSS Theme - Clean, just the variables, no HTML, ...

## Package

### Installing the package

```sh
npm i @estadologico/theme
```

### Usage

Import all variables:

```css
@import "@estadologico/theme/src/theme/all.css";
```

Import custom category:

```css
@import "@estadologico/theme/src/theme/colors.css";
@import "@estadologico/theme/src/theme/spacing.css";
```

## Theme preview (this site)

Install dependencies and run `build`, this will compile the CSS in the `dist` folder.

```bash
npm i
npm run build
```

Or to edit and view changes live:

```bash
npm i
npm run dev
```

Open the `dist/index.html` file in a live preview.

You should see something like this:

![Theme preview](https://raw.githubusercontent.com/manumorante/theme/refs/heads/main/src/assets/screenshot.png)
