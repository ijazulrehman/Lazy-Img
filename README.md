# Lazy Image Loader Angular Web Element 

Lazy Image loader web element generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

## Demo

For demo [click](https://ijazulrehman.github.io/Lazy-Img/)

## Use 

1. Add `script.js` to exiting project.
2. Use `<lazy-img></lazy-img>` width property of `src` width `width` heigth `height` for example

```html
<lazy-img src="https://cdn.pixabay.com/photo/2019/06/08/21/23/women-4261014_960_720.jpg">
    <span slot="header">Caption title here</span>
    <span slot="caption">
        Captions here
    </span>
</lazy-img>
```

## Local Testing 

1. Install `http-server` using `npm`

```bash
    npm install --global http-server
```

2. Run `http-server` on cmd or bash for a dev server. 

```bash
    http-server
```

3. Navigate to `http://127.0.0.1:8080/`.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

