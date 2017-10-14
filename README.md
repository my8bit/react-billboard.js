# react-billboard.js

[![npm](https://img.shields.io/npm/v/react-billboard.js.svg)](https://www.npmjs.com/package/react-billboard.js)
[![npm](https://img.shields.io/npm/dt/react-billboard.js.svg)](https://www.npmjs.com/package/react-billboard.js)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/my8bit/react-billboard.js/master/LICENSE)

[![bitHound Overall Score](https://www.bithound.io/github/my8bit/react-billboard.js/badges/score.svg)](https://www.bithound.io/github/my8bit/react-billboard.js)
[![bitHound Dependencies](https://www.bithound.io/github/my8bit/react-billboard.js/badges/dependencies.svg)](https://www.bithound.io/github/my8bit/react-billboard.js/master/dependencies/npm)
[![bitHound Dev Dependencies](https://www.bithound.io/github/my8bit/react-billboard.js/badges/devDependencies.svg)](https://www.bithound.io/github/my8bit/react-billboard.js/master/dependencies/npm)
[![bitHound Code](https://www.bithound.io/github/my8bit/react-billboard.js/badges/code.svg)](https://www.bithound.io/github/my8bit/react-billboard.js)

[![Code Climate](https://codeclimate.com/github/my8bit/react-billboard.js/badges/gpa.svg)](https://codeclimate.com/github/my8bit/react-billboard.js)
[![Issue Count](https://codeclimate.com/github/my8bit/react-billboard.js/badges/issue_count.svg)](https://codeclimate.com/github/my8bit/react-billboard.js)

## This is a fork of [react-c3js](https://github.com/bcbcarl/react-c3js) adopted for [billboard.js](https://naver.github.io/billboard.js/)

React component for [billboard.js](https://naver.github.io/billboard.js/)

```javascript
import BillboardChart from 'react-billboard.js';
import 'billboard/billboard.css';

const data = {
  columns: [
    ['data1', 30, 200, 100, 400, 150, 250],
    ['data2', 50, 20, 10, 40, 15, 25]
  ]
};

const mountNode = document.getElementById('react-billboardjs');

ReactDOM.render(<BillboardChart data={data} />, mountNode);
```

You can see the `docs` for more details.

[Demo]: http://my8bit.github.io/react-billboardjs/

## Installation

```
$ npm install --save react-billboard.js
```

## Contributing

Please feel free to add pull requests.

### NPM

1. Modify `src/index.js`.
2. Build the lib by using `npm run build`
3. Import BillboardChart from react-billboard.js.
4. Enjoy the result.

## Properties

Check out [billboard.js Reference](https://naver.github.io/billboard.js/release/latest/doc/) for more details.

## License

MIT
