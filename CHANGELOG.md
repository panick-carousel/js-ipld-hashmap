### [2.1.9](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.8...v2.1.9) (2021-12-09)


### Trivial Changes

* **deps-dev:** bump polendina from 1.1.1 to 2.0.0 ([#24](https://github.com/rvagg/js-ipld-hashmap/issues/24)) ([31fc577](https://github.com/rvagg/js-ipld-hashmap/commit/31fc577e989b134e534a8cc2cd7a944e4c93f764))
* **no-release:** bump actions/setup-node from 2.4.1 to 2.5.0 ([#23](https://github.com/rvagg/js-ipld-hashmap/issues/23)) ([81e51b1](https://github.com/rvagg/js-ipld-hashmap/commit/81e51b1f340be367a6df1a8481979be613af8a6f))

### [2.1.8](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.7...v2.1.8) (2021-11-04)


### Trivial Changes

* **deps:** bump actions/checkout from 2.3.5 to 2.4.0 ([cc6790e](https://github.com/rvagg/js-ipld-hashmap/commit/cc6790e2a31d2acd3b5d4f1bde866b9250b14404))

### [2.1.7](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.6...v2.1.7) (2021-10-18)


### Trivial Changes

* **deps:** bump actions/checkout from 2.3.4 to 2.3.5 ([217bb45](https://github.com/rvagg/js-ipld-hashmap/commit/217bb45de4088d1b779b8114205f6f7b59d9065f))

### [2.1.6](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.5...v2.1.6) (2021-09-28)


### Trivial Changes

* **deps:** bump actions/setup-node from 2.4.0 to 2.4.1 ([21b3d5f](https://github.com/rvagg/js-ipld-hashmap/commit/21b3d5fdce3337249c3325b42739692c2c1f1580))

### [2.1.5](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.4...v2.1.5) (2021-08-07)


### Trivial Changes

* **deps:** bump actions/setup-node from 2.3.2 to 2.4.0 ([90e787d](https://github.com/rvagg/js-ipld-hashmap/commit/90e787d6fc68765f00b9c9cf5851a93558d97432))

### [2.1.4](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.3...v2.1.4) (2021-08-05)


### Trivial Changes

* **deps:** bump actions/setup-node from 2.3.0 to 2.3.2 ([113f2ca](https://github.com/rvagg/js-ipld-hashmap/commit/113f2cadb69ce9e3ae05afd7a2d47e8ee8384713))

### [2.1.3](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.2...v2.1.3) (2021-07-23)


### Trivial Changes

* **deps-dev:** bump @types/mocha from 8.2.3 to 9.0.0 ([ab39aee](https://github.com/rvagg/js-ipld-hashmap/commit/ab39aeefa8afd66f746f9c96e3dee16a9091eae6))

### [2.1.2](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.1...v2.1.2) (2021-07-20)


### Trivial Changes

* **deps:** bump actions/setup-node from 2.2.0 to 2.3.0 ([37c315f](https://github.com/rvagg/js-ipld-hashmap/commit/37c315f08c426331fdb7531f0604f834aa054a03))

### [2.1.1](https://github.com/rvagg/js-ipld-hashmap/compare/v2.1.0...v2.1.1) (2021-07-09)


### Bug Fixes

* AsyncIterator -> AsyncIterable ([22f4481](https://github.com/rvagg/js-ipld-hashmap/commit/22f44815bb230d56d72a71957c99b6ae03c1b6ac))

## [2.1.0](https://github.com/rvagg/js-ipld-hashmap/compare/v2.0.2...v2.1.0) (2021-07-09)


### Features

* expose ability to interact with keys as bytes ([df722e8](https://github.com/rvagg/js-ipld-hashmap/commit/df722e88614d1add98a1ff7cc3a05b82cd19dada))

### [2.0.2](https://github.com/rvagg/js-ipld-hashmap/compare/v2.0.1...v2.0.2) (2021-07-09)


### Bug Fixes

* optional hasher and hashBytes params in types defn ([c27113c](https://github.com/rvagg/js-ipld-hashmap/commit/c27113ce904d3f85a9c79e3c4db0e0ea4e19190c))

### [2.0.1](https://github.com/rvagg/js-ipld-hashmap/compare/v2.0.0...v2.0.1) (2021-07-07)


### Trivial Changes

* **deps:** bump actions/setup-node from 2.1.5 to 2.2.0 ([3a9c93f](https://github.com/rvagg/js-ipld-hashmap/commit/3a9c93f384ecb45d95ea23da1253b10c5a3abb9d))

## [2.0.0](https://github.com/rvagg/js-ipld-hashmap/compare/v1.0.0...v2.0.0) (2021-07-07)


### ⚠ BREAKING CHANGES

* adapt to new iamap serialization format
* use multiformats, mandatory hasher & codec, latest iamap

### Features

* adapt to new iamap serialization format ([6d07159](https://github.com/rvagg/js-ipld-hashmap/commit/6d07159e89ba8e5fa7da1648ab9fbcfc33ab5c2f))
* full typing, ESM, remove murmur, browser tests, and more ([1dcb258](https://github.com/rvagg/js-ipld-hashmap/commit/1dcb25813daee6e260a2cbc6f5884ae8edd09706))
* use multiformats, mandatory hasher & codec, latest iamap ([4ae611d](https://github.com/rvagg/js-ipld-hashmap/commit/4ae611d6537e57f26f292a4318e3d3102e6e4aaf))


### Bug Fixes

* properly handle bitWidth and bucketSize options ([8811fcd](https://github.com/rvagg/js-ipld-hashmap/commit/8811fcd4384a980e758a846c3cd89ce2a402513e))


### Trivial Changes

* add alice-words spec fixture generator / checker ([5490d77](https://github.com/rvagg/js-ipld-hashmap/commit/5490d770ae4473673582c8ae1b4df732f218d72b))
* add example, expand and clarify README ([36e286b](https://github.com/rvagg/js-ipld-hashmap/commit/36e286b055e1d4e465d5485661a2c171845619e3))
* add GitHub Actions - dependabot, test & semantic-release ([b312521](https://github.com/rvagg/js-ipld-hashmap/commit/b312521130ea6636209b9601606eec6ce38e4fbd))
* add schema and compiled validator ([84501ce](https://github.com/rvagg/js-ipld-hashmap/commit/84501cedd4aa4b07ecc1631e944752bbc032e10d))
* update deps ([64751bb](https://github.com/rvagg/js-ipld-hashmap/commit/64751bb1de2bc67b2d29da7dd988e08ca5b7eb3a))
