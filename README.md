# ElementEasyLoader

Lazy Image loader web element  generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

## Use 

1. Add `script.js` to exiting project.
2. Use `<lazy-img></lazy-img>` width property of `src` width `width` heigth `height` for example

``
  <lazy-img src="https://cdn.pixabay.com/photo/2019/06/08/21/23/women-4261014_960_720.jpg">
    <span slot="header">Caption title here</span>
    <span slot="caption">
      Captions here
    </span>
  </lazy-img>
``

## Local Testing 

1. Install `http-server` using `npm`

``
    npm install --global http-server
``
2. Run `http-server` for a dev server. Navigate to `http://127.0.0.1:8080/`.
## Code scaffolding


