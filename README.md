# unisonweb-base

This docker image contains a `ucm` executable, and a codebase located at `WORKDIR/codebase` containing [`base`](https://github.com/unisonweb/base).

You are free to bring your own codebase, i.e.

```
ADD my-codebase .
CMD ucm -codebase ./my-codebase
```
