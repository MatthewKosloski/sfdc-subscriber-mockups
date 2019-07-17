# sfdc-subscriber-mockups

High-fidelity mockups for the SFDC Subscriber dashboard, written in static HTML and CSS.  An adaptation of the [7-1 Sass architecture pattern](https://github.com/HugoGiraudel/sass-boilerplate) and Brad Frost's [Atomic Design Methodology](http://atomicdesign.bradfrost.com/chapter-2/#the-atomic-design-methodology).

## Compiling SCSS code

Make sure the [Sass](https://www.npmjs.com/package/sass) node module is installed globally.  If not, run:

```
npm install -g sass
```

Then, from `src`, run:

```
sass scss/style-guide.scss:style-guide.css --watch
```