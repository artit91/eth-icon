# eth-icon
Ethereum Icon Component

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
