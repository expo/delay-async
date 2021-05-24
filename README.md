# delay-async

A Promise-based wrapper for setTimeout

## Usage

```js

import delayAsync from 'delay-async';

async function wait100ms() {
    console.log("Start");
    await delayAsync(100);
    console.log("100ms later");
}

```