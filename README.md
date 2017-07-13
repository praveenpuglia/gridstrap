# GridStrap

A rough implementation of Bootstrap V4 grids using CSS Grids Module. Use it anywhere you want a minimal, grid without the overhead of an entire framework.

Wanna help? Here are the things to start with.

- Columns with just `.col` don't auto span multiple columns to take up entire width.
- Have not tested nested rows.
- Repeats the CSS for spanning different columns in all media queries. 

## [Demo](https://praveenpuglia.com/gridstrap)

## Development
### Installation
```sh
npm install
```

### Run 
```sh
npm start #for simple css and js
```

### With SCSS
If you plan to use SCSS, try putting your CSS into **src/style.scss**. If you need to use multiple files, import all of them in **src/style.scss**.

```sh
npm run watch:scss
```

Make changes to any file and it'll reflect on every single browser you go to [`localhost:3000`](http://localhost:3000)

---
Made with ❤️ using [Demoplate](https://github.com/praveenpuglia/demoplate)