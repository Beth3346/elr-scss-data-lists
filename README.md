# Data Lists

[![npm version](http://img.shields.io/npm/v/elr-scss-data-lists.svg)](https://www.npmjs.org/package/elr-scss-data-lists)
[![CI](https://github.com/Beth3346/elr-scss-data-lists/actions/workflows/node.js.yml/badge.svg)](https://github.com/Beth3346/elr-scss-data-lists/actions/workflows/node.js.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-data-lists.svg?style=flat)](https://npmjs.com/package/elr-scss-data-lists)
[![last commit](https://img.shields.io/github/last-commit/Beth3346/elr-scss-data-lists.svg)](https://github.com/Beth3346/elr-scss-data-lists)

a scss mixin for data-lists

<!-- [View Demo](https://elr-data-lists.netlify.app/) -->

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-data-lists
```

or

```sh
yarn add elr-scss-data-lists
```

## Implementation

### HTML

```html
<div class="data-list">
  <header class="data-list-heading">
    <h3>Customer List</h3>
    <p>A list of active customers</p>
  </header>
  <section class="data-list-items">
    <dl>
      <div>
        <dt><span>Elizabeth Rogers</span></dt>
        <dd>
          <span>Senior Front End Developer</span>
          <span>Austin TX</span>
          <span>United States</span>
          <button>Edit</button>
          <button class="text-danger">Remove</button>
        </dd>
      </div>
      <div>
        <dt><span>Elizabeth Rogers</span></dt>
        <dd>
          <span>Senior Front End Developer</span>
          <span>Austin TX</span>
          <span>United States</span>
          <button>Edit</button>
          <button class="text-danger">Remove</button>
        </dd>
      </div>
      <div>
        <dt><span>Elizabeth Rogers</span></dt>
        <dd>
          <span>Senior Front End Developer</span>
          <span>Austin TX</span>
          <span>United States</span>
          <button>Edit</button>
          <button class="text-danger">Remove</button>
        </dd>
      </div>
      <div>
        <dt><span>Elizabeth Rogers</span></dt>
        <dd>
          <span>Senior Front End Developer</span>
          <span>Austin TX</span>
          <span>United States</span>
          <button>Edit</button>
          <button class="text-danger">Remove</button>
        </dd>
      </div>
      <div>
        <dt><span>Elizabeth Rogers</span></dt>
        <dd>
          <span>Senior Front End Developer</span>
          <span>Austin TX</span>
          <span>United States</span>
          <button>Edit</button>
          <button class="text-danger">Remove</button>
        </dd>
      </div>
    </dl>
  </section>
</div>
```

### Scss

```scss
.data-list {
  @include elr-data-list;
}
```

## License

SEE LICENSE IN LICENSE.md
