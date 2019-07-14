`yarn`

`yarn build`

```
$ yarn build
yarn run v1.17.3
$ parcel build index.js
√  Built in 469ms.

dist\lib.c67b7947.wasm    ‼  1.4 MB    22ms
dist\index.js.map            5.9 KB     5ms
dist\index.js               3.11 KB    39ms
Done in 2.20s.
```

Note the size of the `.wasm` file.

Ideally it would be much smaller than 1.4MB when there are only 5 lines of rust code.
