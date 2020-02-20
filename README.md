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
│   └── main.scss
│    
├── vui.css
└── vui.min.css
```

    - Default `vui.css` ready for development and possible [optimizations](#how-to-use) before a project release
    - Minified `vui.min.css` version ready to be used in production
    - Core framework files and partials into the `scss` folder


## How To Configure?

There are several options that you can configure into `scss/partials/_variables.scss`:
    - Number of grid columns ( <em>defaults to 12</em> )
    - General spacing values for margin & padding ( <em>sm / md / lg</em> ) represented in `rem` units, `:root` equals to `16px`
    - Page left & right space gap ( <em>defaults to 15px</em> )
    - <em>more to come..</em>

## How To Use?

You already know how to use this framework if you know the well known story about the `flex` parent. Who takes care of it's <em>children</em> elements, pointing them into a right direction :)

We can start simple, getting into the concept by a real world example.
We'll start building the following Ui model:

