# es6-easing
just import as a regular module:

```
import * as easings from './lib/easing.js';
```

And they'll be there:

```
let value = easings.easeOutExpo(t, b, c, d);
```

Parameters are:

| var | description           |
|-----|-----------------------|
| t | current time            |
| b | initial value - offset  |
| c | change in value         |
| d | duration                |

If you're using normalized values, just call with

```
easings.easeOutExpo(t, 0, 1, 1);
```
