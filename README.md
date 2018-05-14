# models

## Exploring the Python side of nteract's setIn based models

We've done some previous explorations for a model backed by `setIn`

Originally it started with the [synchronized object diff spec](https://github.com/rgbkrk/synchronized-object-diff-spec). We evenutally implemented a "hidden" version of this that uses a `setIn` based reducer under the hood:

https://github.com/nteract/nteract/blob/master/packages/core/src/reducers/comms.js#L42-L55

Example notebook: https://github.com/nteract/nteract/blob/master/applications/desktop/example-notebooks/model-debug.ipynb

----

This repository is going to be an exploration on a python module for binding the comms (two-way) with a python object for these.
