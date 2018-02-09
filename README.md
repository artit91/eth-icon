# eth-icon
Ethereum Icon Component

[![npm](https://img.shields.io/npm/v/eth-icon.svg)](https://www.npmjs.com/package/eth-icon)

## Usage
```JavaScript
import React from "react";
import EthIcon from "eth-icon";

const render = props => (
  <EthIcon
    // Address to draw
    address={props.address}
    // scale * 8 pixel image size
    scale={16}
    // <img> props
    style={{
      background: "red"
    }}
  />
);

```
