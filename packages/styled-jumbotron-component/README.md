# styled-jumbotron-component

[![npm](https://img.shields.io/npm/v/styled-jumbotron-component.svg?style=flat-square)](https://www.npmjs.com/package/styled-jumbotron-component)
[![Travis branch](https://img.shields.io/travis/aichbauer/styled-bootstrap-components/master.svg?style=flat-square)](https://travis-ci.org/aichbauer/styled-bootstrap-components)
[![Codecov branch](https://img.shields.io/codecov/c/github/aichbauer/styled-bootstrap-components/master.svg?style=flat-square)](https://codecov.io/gh/aichbauer/styled-bootstrap-components)
[![storybook](https://img.shields.io/badge/docs%20with-storybook-f1618c.svg?style=flat-square)](https://aichbauer.github.io/styled-bootstrap-components)
[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg?style=flat-square)](https://lernajs.io/)

> The [bootstrap](https://getbootstrap.com) jumbotron component made with [styled-components](https://styled-components.com).

## Table of Contents

* [Documentation](https://aichbauer.github.io/styled-bootstrap-components)
* [Why?](#why)
* [Installation](#installation)
* [Usage](#usage)
* [Properties](#properties)
* [Related](#related)
* [License](#license)

## Why?

This is a modular approach to use [bootstrap](https://getbootstrap.com) components for quick prototypes, as an entrypoint of your own component library, or if you need just one [bootstrap](https://getbootstrap.com) component for your application. To work with ease with any other libary or framework this component is built with [styled-components](https://styled-components.com).

## Installation

> Note: this component has a peer dependency on `styled-components` > v4. To use this component you also need to `npm i styled-components -S`.

```sh
$ npm i styled-jumbotron-component -S
```

or

```sh
$ yarn add styled-jumbotron-component
```

## Usage

For detailed information take a look at the [documentation](https://aichbauer.github.io/styled-bootstrap-components).

To use HTML that uses the Boostrap style, use [styled-base-components](https://github.com/aichbauer/styled-bootstrap-components/blob/master/packages/styled-base-components/README.md).

```jsx
/*
  if you installed `styled-bootstrap-components` use

    import { ... } from 'styled-bootstrap-components'

  instead.
*/
import { Jumbotron } from 'styled-jumbotron-component';

const MyButtonComponent = (props) => (
  {/* use different props to change the visual appearance */}
  <Jumbotron fluid>
    <h1>
    Fluid jumbotron
    </h1>
    <p>
      This is a modified jumbotron that occupies the entire horizontal space of its parent.
    </p>
  </Jumbotron>
);
```

## Properties

Properties which can be added to the component to change the visual appearance.

* `fluid` **Type**: boolean

## Related

* [bootstrap](https://getbootstrap.com)
* [styled-components](https://styled-components.com)

## License

MIT © Lukas Aichbauer
