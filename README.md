# react-transition-group [![npm][npm-badge]][npm]

**This fork exists in order to allow support for React 0.14 for the v1 branch.**

v1.1.1 was found to be the best candidate for altering to support the older version of React, as later versions carry a PropType warning.

The branch `morph-compat-c/1.1.1` contains the modifications. This was then built (`npm run build`) and the lib directory pushed removed from the `.gitignore` and then tagged as `v1.1.1-custom`.

> **ATTENTION!** To address many issues that have come up over the years, the API in v2 is not backwards compatible with the original [`React addon (v1-stable)`](https://github.com/reactjs/react-transition-group/tree/v1-stable).
>
> **For a drop-in replacement for `react-addons-transition-group` and `react-addons-css-transition-group`, use the v1 release. Documentation and code for that release are available on the [`v1-stable`](https://github.com/reactjs/react-transition-group/tree/v1-stable) branch.**
>
> We are no longer updating the v1 codebase, please upgrade to v2 when possible

A set of components for managing component states (including mounting and unmounting) over time, specifically designed with animation in mind.

## Documentation

- [**Main documentation**](https://reactcommunity.org/react-transition-group/)
- [Migration guide from v1](/Migration.md)

## Examples

Clone the repo first:

```
git@github.com:reactjs/react-transition-group.git
```

Then run `npm install` (or `yarn`), and finally `npm run storybook` to start a storybook instance that you can navigate to in your browser to see the examples.

[npm-badge]: https://img.shields.io/npm/v/react-transition-group.svg
[npm]: https://www.npmjs.org/package/react-transition-group
