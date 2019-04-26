# ngx-slickjs

[![Maintainability](https://api.codeclimate.com/v1/badges/822ebfba446c893a385a/maintainability)](https://codeclimate.com/github/mehmet-erim/ngx-slickjs/maintainability)
[![Build Status](https://travis-ci.org/mehmet-erim/ngx-slickjs.svg?branch=master)](https://travis-ci.org/mehmet-erim/ngx-slickjs)
![Codecov](https://img.shields.io/codecov/c/gh/mehmet-erim/ngx-slickjs.svg)


## Installation
```bash
yarn add ngx-slickjs
```
or
```bash
npm install ngx-slickjs
```

## Usage
Import core module to your main module as follows:

```typescript
// ...
import { NgxSlickJsModule } from 'ngx-slickjs';

@NgModule({
  imports: [NgxSlickJsModule.forRoot()],
  // ...
})
export class AppModule {}

``` 
