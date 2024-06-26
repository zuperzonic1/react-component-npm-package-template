# React Component NPM Package Template

You wrote a sweet React component! Releasing it on [NPM](https://www.npmjs.com/)
seems like the obvious next step. Right?

Try it. Not as easy to do from scratch as you might think.

So here's a plug-and-play NPM package template that offers the following
features:

- Support for the latest ES6 + JSX goodies with
  [`eslint`](https://www.npmjs.com/package/eslint) _uber alles_.

- Automated [`lodash`](https://www.npmjs.com/package/lodash) cherry-picking with
  [`babel-plugin-lodash`](https://www.npmjs.com/package/babel-plugin-lodash).

- Front & back-end testing with [`mocha`](https://www.npmjs.com/package/mocha),
  [`chai`](https://www.npmjs.com/package/chai), and the
  [React Testing Library](https://www.npmjs.com/package/@testing-library/react).
  Includes examples and a sweet testing console!

- Code formatting at every save & paste with
  [`prettier`](https://www.npmjs.com/package/prettier).

- Automated documentation of your API with
  [`jsdoc-to-markdown`](https://www.npmjs.com/package/jsdoc-to-markdown) and
  assembly of your README with
  [`concat-md`](https://www.npmjs.com/package/concat-md).

- One-button release to GitHub & publish to NPM with
  [`release-it`](https://www.npmjs.com/package/release-it).

**[Click here](https://karmanivero.us/blog/react-component-npm-package-template/)
for full template documentation & instructions!**

_If you want to create a non-React NPM package, try my regular
[NPM Package Template](https://github.com/karmaniverous/npm-package-template)
instead!_

# API Documentation

```js
import { MyComponent } from '@karmaniverous/react-component-npm-package-template`;
```

<a name="MyComponent"></a>

## MyComponent([props]) ⇒ <code>object</code>
Wraps children in an `h1` tag with a specified `data-test-id` attribute.Using lodash purely to demonstrate Babel cherry-picking.

**Kind**: global function  
**Returns**: <code>object</code> - MyComponent  

| Param | Type | Description |
| --- | --- | --- |
| [props] | <code>object</code> | - |
| [props.children] | <code>object</code> | - |
| [props.testid] | <code>string</code> | - |

**Example**  
```js
<MyComponent testid="testid">Hello, world!</MyComponent>;// <h1 data-testid="testid">Hello, world!</h1>
```

---

See more great templates and other tools on
[my GitHub Profile](https://github.com/karmaniverous)!
