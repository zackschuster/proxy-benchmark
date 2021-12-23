# Simple Proxy Benchmark

Code forked from [this blog post](https://thecodebarbarian.com/thoughts-on-es6-proxies-performance)

## Run

```console
$ npm i
$ npm start
```

## Sample

Generated using `node@16.13.1` on Apple M1 Pro

```console
vanilla x 1,030,372,179 ops/sec ±0.11% (100 runs sampled)
proxy x 59,212,141 ops/sec ±0.10% (101 runs sampled)
defineProperty x 1,027,998,412 ops/sec ±0.13% (101 runs sampled)
Fastest is vanilla
```
