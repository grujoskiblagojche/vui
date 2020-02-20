<img src="https://i.imgur.com/IMWSQFN.png" alt="vUi" width="125" height="125">

<p>
The most lightweight, performant, and powerful front-end framework for faster and easier Ui development.
<br>
<em>Configure it by your needs and get ready to rock!</em>
</p>


## Table of contents

- [Quick start](#quick-start)
- [What's included](#whats-included)
- [How to configure ?](#how-to-configure)
- [How to use ?](#how-to-use)
- [Cheat Sheet](#cheat-sheet)


## Quick start


- Download the latest release: https://github.com/grujoskiblagojche/vui/archive/master.zip
- Clone the repo: `git clone https://github.com/grujoskiblagojche/vui`
- Add the `/scss` source files into your project


## What's included

Within the download you'll find the following directories and files combined into ` 2.95 KB ` :)

```text
vui/
├── scss/
│   ├── partials/
│   │   ├── variables.scss
│   │   ├── grid.scss
│   │   ├── columns.scss
│   │   ├── spacings.scss
│   │   └── helpers.scss
│   └── vui.scss
│    
├── vui.css
└── vui.min.css
```

- Default `vui.css` ready for development and possible [optimizations](#how-to-use) before a project release
- Minified `vui.min.css` version ready to be used in production
- Core framework files and partials into the `scss` folder


## How To Configure?

There are several options that you can configure into `scss/partials/_variables.scss`

- Number of grid columns ( <em>defaults to 12</em> )
```
$grid-columns: 12;
```
- General spacing values for margin & padding represented in `rem` units, `:root` equals to `16px`
```
$sm: 0.3125rem;  // 5px
$md: 0.625rem;   // 10px
$lg: 0.9375rem;  // 15px
```
- Page container width ( <em>defaults to `80vh` and max-width of `1440px`</em> )
```
$container-width: 80vw;
$container-max-width: 1440px;
```
- <em>more to come..</em>

## How To Use?

You already know how to use this framework if you know the well known story about the `flex` parent. Who takes care of it's <em>children</em> elements, pointing them into a right direction :)

We can start simple, getting into the concept by a real world examples:

https://codesandbox.io/s/vui-layout-showcase-txmod

## Cheat Sheet

- GRID

`.container` - wraps content in middle by 80vw as a default
<p></p>

`.row` - align child elements horizontaly
<p></p>

`.col` - align child elements verticaly
<p></p>

`.h-start` or `.h-s` - align horizontal start
<p></p>

`.h-center` or `.h-c` - align horizontal center
<p></p>

`.h-end` or `.h-s` - align horizontal end
<p></p>
<p></p>

`.v-start` or `.v-s` - align vertical start

`.v-center` or `.v-c` - align vertical center

`.v-end` or `.v-e` - align vertical end


`.abs` - align child elements in absolute center
<p></p>

`.spa` - make equal space around child elements
<p></p>

`.spb` - make equal space between child elements
<p></p>
<p></p>

`.wrap` - makes child elements to wrap into another row based on their width
<p></p>

- COLLUMNS

<em>Can be set to a custom value based on your needs into `_variables.scss` - `$grid-columns` (  defaults to 12 )</em>.

`.col-1`
`.col-2`
`.col-3`
.
.
.
`.col-n`


- SPACINGS ( <em>margin / padding</em> )

<em>Use</em> `_` <em>for directions ( top / right / left / bottom ), and</em> `-` <em>for size values ( sm / md / lg )</em>.

`.m-sm`

`.m_t-sm`
`.m_r-sm`
`.m_b-sm`
`.m_l-sm`

`.p-sm`

`.p_t-sm`
`.p_r-sm`
`.p_b-sm`
`.p_l-sm`


- HELPERS

`.relative`
`.absolute`
`.fixed`
`.sticky`

`.hidden`
`.scroll-x`
`.scroll-y`

`full-width`