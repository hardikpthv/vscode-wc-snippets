<p align="center">
  <img width="100" src="https://raw.githubusercontent.com/hardikpthv/vscode-lit-snippets/master/images/logo.png">
</p>

# Web Components Snippets for VS Code

[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
[![Version](https://vsmarketplacebadge.apphb.com/version/hardikpthv.lit-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=hardikpthv.lit-snippets)
[![Install](https://vsmarketplacebadge.apphb.com/installs/hardikpthv.lit-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=hardikpthv.lit-snippets)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/hardikpthv.lit-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=hardikpthv.lit-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/hardikpthv.lit-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=hardikpthv.lit-snippets)

This extension for Visual Studio Code adds snippets of HTML and Javascript for [LitElement](https://lit-element.polymer-project.org), [lit-html](https://lit-html.polymer-project.org), [Stencil](https://stenciljs.com/), [FASTElement](https://www.fast.design/docs/fast-element/getting-started◊) and [Web components](https://www.webcomponents.org/introduction).

Have a look at [CHANGELOG](CHANGELOG.md) for the latest changes

## Installation

1.  Install Visual Studio Code 1.10.0 or higher
1.  Launch VS Code
1.  Hit `Cmd`-`Shift`-`P` (macOS) or `Ctrl`-`Shift`-`P` (Windows, Linux)
1.  Select `Install Extension`
1.  Choose the extension `Lit and Web Components snippets`
1.  Reload Visual Studio Code

## Usage

Start typing `lit-*` and hit `enter`, the snippet spreads out or e.g. `lit-component` to `lcomp`

![Use Extension](images/usage.gif)

### LitElement and lit-html Snippets

| Snippet                    | Purpose                                                                         |
| -------------------------- | ------------------------------------------------------------------------------- |
| `lit-component`            | Basic Lit component                                                             |
| `lit-component-decorator`  | Basic Lit component using decorator                                             |
| `lit-render`               | `render()`                                                                      |
| `lit-props`                | `properties()`                                                                  |
| `lit-props-decorator`      | `@property` decorator                                                           |
| `lit-styles`               | `styles()`                                                                      |
| `lit-ctor`                 | Add `constructor()`                                                             |
| `lit-cb`                   | `connectedCallback()` life cycle method                                         |
| `lit-dcb`                  | `disconnectedCallback()`life cycle method                                       |
| `lit-first-updated`        | `firstUpdated()`life cycle method                                               |
| `lit-updated`              | `updated()`life cycle method                                                    |
| `lit-ce`                   | Create the custom event using `CustomEvent`                                     |
| `lit-conditional-template` | Create conditional template expression                                          |
| `lit-tmpl-loop`            | Iterate templates through `map()`                                               |
| `lit-style`                | Add `styleMap()` to the element                                                 |
| `lit-class`                | Add `classMap()` to the element                                                 |
| `lit-should-update`        | Implement `shouldUpdate` life cycle hook                                        |
| `lit-test-open-wc`         | Test case based on [@open-wc](https://open-wc.org/testing/testing-helpers.html) |

### Stencil Snippets

| Snippet                         | Purpose                                                       |
| ------------------------------- | ------------------------------------------------------------- |
| `stencil-component`             | Stencil component                                             |
| `stencil-functional-component`  | Stencil functional component                                  |
| `stencil-prop`                  | `@Prop` decorator from Stencil                                |
| `stencil-element`               | `@Element` decorator from Stencil                             |
| `stencil-event`                 | `@Event` decorator from Stencil                               |
| `stencil-method-async`          | `@Method`(async) decorator from `@stencil/core`               |
| `stencil-method-promise`        | `@Method` decorator as returning promise from `@stencil/core` |
| `stencil-component-will-load`   | `@componentWillLoad` life cycle hook                          |
| `stencil-component-did-load`    | `@componentDidLoad` life cycle hook                           |
| `stencil-component-will-render` | `@componentWillRender` life cycle hook                        |
| `stencil-component-did-render`  | `@componentDidRender` life cycle hook                         |
| `stencil-component-will-update` | `@componentWillUpdate` life cycle hook                        |
| `stencil-cb`                    | `connectedCallback()` from Stencil                            |
| `stencil-dcb`                   | `disconnectedCallback()` from Stencil                         |

### FASTElement Snippets

| Snippet                  | Purpose                                   |
| ------------------------ | ----------------------------------------- |
| `fast-component`         | Basic FASTElement Component               |
| `fast-cb`                | `connectedCallback()` from FASTElement    |
| `fast-dcb`               | `disconnectedCallback()` from FASTElement |
| `fast-attr`              | `@attr` decorator                         |
| `fast-observable`        | `@observable` decorator                   |
| `fast-observable-notify` | `Observable.notify(...)`                  |
| `fast-observable-track`  | `Observable.track(...)`                   |
| `fast-dispatch`          | `$emit` to dispatch the custom event      |
| `fast-when`              | `when`for conditional rendering           |

### Web Components Snippets

| Snippet                   | Purpose                           |
| ------------------------- | --------------------------------- |
| `wc`                      | Basic Web Component               |
| `wc-observed-attrs`       | Define `observedAttributes`       |
| `wc-adopted-cb`           | Define `adoptedCallback`          |
| `wc-attribute-changed-cb` | Define `attributeChangedCallback` |
| `wc-slot`                 | Define `<slot>`                   |
| `wc-slot-named`           | Define `<slot name="name">`       |

## Using NgRx or Angular material 🤔

- Check out:
  - [NgRx Snippets](https://bit.ly/ngrx-vscode)
  - [Angular Material Snippets](https://bit.ly/ng-material-vscode)
