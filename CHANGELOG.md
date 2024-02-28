# Changelog

## 1.13.3 (2024-02-28)

Full Changelog: [v1.13.2...v1.13.3](https://github.com/openai/openai-python/compare/v1.13.2...v1.13.3)

### Features

* **api:** add wav and pcm to response_format ([#1189](https://github.com/openai/openai-python/issues/1189)) ([dbd20fc](https://github.com/openai/openai-python/commit/dbd20fc42e93358261f71b9aa0e5f955053c3825))


### Chores

* **client:** use anyio.sleep instead of asyncio.sleep ([#1198](https://github.com/openai/openai-python/issues/1198)) ([b6d025b](https://github.com/openai/openai-python/commit/b6d025b54f091e79f5d4a0a8923f29574fd66027))
* **internal:** bump pyright ([#1193](https://github.com/openai/openai-python/issues/1193)) ([9202e04](https://github.com/openai/openai-python/commit/9202e04d07a7c47232f39196346c734869b8f55a))
* **types:** extract run status to a named type ([#1178](https://github.com/openai/openai-python/issues/1178)) ([249ecbd](https://github.com/openai/openai-python/commit/249ecbdeb6566a385ec46dfd5000b4eaa03965f0))


### Documentation

* add note in azure_deployment docstring ([#1188](https://github.com/openai/openai-python/issues/1188)) ([96fa995](https://github.com/openai/openai-python/commit/96fa99572dd76ee708f2bae04d11b659cdd698b2))
* **examples:** add pyaudio streaming example ([#1194](https://github.com/openai/openai-python/issues/1194)) ([3683c5e](https://github.com/openai/openai-python/commit/3683c5e3c7f07e4b789a0c4cc417b2c59539cae2))

## 1.13.2 (2024-02-20)

Full Changelog: [v1.13.1...v1.13.2](https://github.com/openai/openai-python/compare/v1.13.1...v1.13.2)

### Bug Fixes

* **ci:** revert "move github release logic to github app" ([#1170](https://github.com/openai/openai-python/issues/1170)) ([f1adc2e](https://github.com/openai/openai-python/commit/f1adc2e6f2f29acb4404e84137a9d3109714c585))

## 1.13.1 (2024-02-20)

Full Changelog: [v1.13.0...v1.13.1](https://github.com/openai/openai-python/compare/v1.13.0...v1.13.1)

### Chores

* **internal:** bump rye to v0.24.0 ([#1168](https://github.com/openai/openai-python/issues/1168)) ([84c4256](https://github.com/openai/openai-python/commit/84c4256316f2a79068ecadb852e5e69b6b104a1f))

## 1.13.0 (2024-02-19)

Full Changelog: [v1.12.0...v1.13.0](https://github.com/openai/openai-python/compare/v1.12.0...v1.13.0)

### Features

* **api:** updates ([#1146](https://github.com/openai/openai-python/issues/1146)) ([79b7675](https://github.com/openai/openai-python/commit/79b7675e51fb7d269a6ea281a568bc7812ba2ace))


### Bug Fixes

* **api:** remove non-GA instance_id param ([#1164](https://github.com/openai/openai-python/issues/1164)) ([1abe139](https://github.com/openai/openai-python/commit/1abe139b1a5f5cc41263738fc12856056dce5697))


### Chores

* **ci:** move github release logic to github app ([#1155](https://github.com/openai/openai-python/issues/1155)) ([67cfac2](https://github.com/openai/openai-python/commit/67cfac2564dfb718da0465e34b90ac6928fa962a))
* **client:** use correct accept headers for binary data ([#1161](https://github.com/openai/openai-python/issues/1161)) ([e536437](https://github.com/openai/openai-python/commit/e536437ae0b2cb0ddf2d74618722005d37403f32))
* **internal:** refactor release environment script ([#1158](https://github.com/openai/openai-python/issues/1158)) ([7fe8ec3](https://github.com/openai/openai-python/commit/7fe8ec3bf04ecf85e3bd5adf0d9992c051f87b81))

## 1.12.0 (2024-02-08)

Full Changelog: [v1.11.1...v1.12.0](https://github.com/openai/openai-python/compare/v1.11.1...v1.12.0)

### Features

* **api:** add `timestamp_granularities`, add `gpt-3.5-turbo-0125` model ([#1125](https://github.com/openai/openai-python/issues/1125)) ([1ecf8f6](https://github.com/openai/openai-python/commit/1ecf8f6b12323ed09fb6a2815c85b9533ee52a50))
* **cli/images:** add support for `--model` arg ([#1132](https://github.com/openai/openai-python/issues/1132)) ([0d53866](https://github.com/openai/openai-python/commit/0d5386615cda7cd50d5db90de2119b84dba29519))


### Bug Fixes

* remove double brackets from timestamp_granularities param ([#1140](https://github.com/openai/openai-python/issues/1140)) ([3db0222](https://github.com/openai/openai-python/commit/3db022216a81fa86470b53ec1246669bc7b17897))
* **types:** loosen most List params types to Iterable ([#1129](https://github.com/openai/openai-python/issues/1129)) ([bdb31a3](https://github.com/openai/openai-python/commit/bdb31a3b1db6ede4e02b3c951c4fd23f70260038))


### Chores

* **internal:** add lint command ([#1128](https://github.com/openai/openai-python/issues/1128)) ([4c021c0](https://github.com/openai/openai-python/commit/4c021c0ab0151c2ec092d860c9b60e22e658cd03))
* **internal:** support serialising iterable types ([#1127](https://github.com/openai/openai-python/issues/1127)) ([98d4e59](https://github.com/openai/openai-python/commit/98d4e59afcf2d65d4e660d91eb9462240ef5cd63))


### Documentation

* add CONTRIBUTING.md ([#1138](https://github.com/openai/openai-python/issues/1138)) ([79c8f0e](https://github.com/openai/openai-python/commit/79c8f0e8bf5470e2e31e781e8d279331e89ddfbe))

## 1.11.1 (2024-02-04)

Full Changelog: [v1.11.0...v1.11.1](https://github.com/openai/openai-python/compare/v1.11.0...v1.11.1)

### Bug Fixes

* prevent crash when platform.architecture() is not allowed ([#1120](https://github.com/openai/openai-python/issues/1120)) ([9490554](https://github.com/openai/openai-python/commit/949055488488e93597cbc6c2cdd81f14f203e53b))

## 1.11.0 (2024-02-03)

Full Changelog: [v1.10.0...v1.11.0](https://github.com/openai/openai-python/compare/v1.10.0...v1.11.0)

### Features

* **client:** support parsing custom response types ([#1111](https://github.com/openai/openai-python/issues/1111)) ([da00fc3](https://github.com/openai/openai-python/commit/da00fc3f8e0ff13c6c3ca970e4bb86846304bd06))


### Chores

* **interal:** make link to api.md relative ([#1117](https://github.com/openai/openai-python/issues/1117)) ([4a10879](https://github.com/openai/openai-python/commit/4a108797e46293357601ce933e21b557a5dc6954))
* **internal:** cast type in mocked test ([#1112](https://github.com/openai/openai-python/issues/1112)) ([99b21e1](https://github.com/openai/openai-python/commit/99b21e1fc681eb10e01d479cc043ad3c89272b1c))
* **internal:** enable ruff type checking misuse lint rule ([#1106](https://github.com/openai/openai-python/issues/1106)) ([fa63e60](https://github.com/openai/openai-python/commit/fa63e605c82ec78f4fc27469c434b421a08fb909))
* **internal:** support multipart data with overlapping keys ([#1104](https://github.com/openai/openai-python/issues/1104)) ([455bc9f](https://github.com/openai/openai-python/commit/455bc9f1fd018a32cd604eb4b400e05aa8d71822))
* **internal:** support pre-release versioning ([#1113](https://github.com/openai/openai-python/issues/1113)) ([dea5b08](https://github.com/openai/openai-python/commit/dea5b08c28d47b331fd44f6920cf9fe322b68e51))

## 1.10.0 (2024-01-25)

Full Changelog: [v1.9.0...v1.10.0](https://github.com/openai/openai-python/compare/v1.9.0...v1.10.0)

### Features

* **api:** add text embeddings dimensions param ([#1103](https://github.com/openai/openai-python/issues/1103)) ([94abfa0](https://github.com/openai/openai-python/commit/94abfa0f988c199ea95a9c870c4ae9808823186d))
* **azure:** proactively add audio/speech to deployment endpoints ([#1099](https://github.com/openai/openai-python/issues/1099)) ([fdf8742](https://github.com/openai/openai-python/commit/fdf87429b45ceb47ae6fd068ab70cc07bcb8da44))
* **client:** enable follow redirects by default ([#1100](https://github.com/openai/openai-python/issues/1100)) ([d325b7c](https://github.com/openai/openai-python/commit/d325b7ca594c2abaada536249b5633b106943333))


### Chores

* **internal:** add internal helpers ([#1092](https://github.com/openai/openai-python/issues/1092)) ([629bde5](https://github.com/openai/openai-python/commit/629bde5800d84735e22d924db23109a141f48644))


### Refactors

* remove unnecessary builtin import ([#1094](https://github.com/openai/openai-python/issues/1094)) ([504b7d4](https://github.com/openai/openai-python/commit/504b7d4a0b4715bd49a1a076a8d4868e51fb3351))

## 1.9.0 (2024-01-21)

Full Changelog: [v1.8.0...v1.9.0](https://github.com/openai/openai-python/compare/v1.8.0...v1.9.0)

### Features

* **api:** add usage to runs and run steps ([#1090](https://github.com/openai/openai-python/issues/1090)) ([6c116df](https://github.com/openai/openai-python/commit/6c116dfbb0065d15050450df70e0e98fc8c80349))


### Chores

* **internal:** fix typing util function ([#1083](https://github.com/openai/openai-python/issues/1083)) ([3e60db6](https://github.com/openai/openai-python/commit/3e60db69f5d9187c4eb38451967259f534a36a82))
* **internal:** remove redundant client test ([#1085](https://github.com/openai/openai-python/issues/1085)) ([947974f](https://github.com/openai/openai-python/commit/947974f5af726e252b7b12c863743e50f41b79d3))
* **internal:** share client instances between all tests ([#1088](https://github.com/openai/openai-python/issues/1088)) ([05cd753](https://github.com/openai/openai-python/commit/05cd7531d40774d05c52b14dee54d137ac1452a3))
* **internal:** speculative retry-after-ms support ([#1086](https://github.com/openai/openai-python/issues/1086)) ([36a7576](https://github.com/openai/openai-python/commit/36a7576a913be8509a3cf6f262543083b485136e))
* lazy load raw resource class properties ([#1087](https://github.com/openai/openai-python/issues/1087)) ([d307127](https://github.com/openai/openai-python/commit/d30712744be07461e86763705c03c3495eadfc35))

## 1.8.0 (2024-01-16)

Full Changelog: [v1.7.2...v1.8.0](https://github.com/openai/openai-python/compare/v1.7.2...v1.8.0)

### Features

* **client:** add support for streaming raw responses ([#1072](https://github.com/openai/openai-python/issues/1072)) ([0e93c3b](https://github.com/openai/openai-python/commit/0e93c3b5bc9cfa041e91962fd82c0d9358125024))


### Bug Fixes

* **client:** ensure path params are non-empty ([#1075](https://github.com/openai/openai-python/issues/1075)) ([9a25149](https://github.com/openai/openai-python/commit/9a2514997c2ddccbec9df8be3773e83271f1dab8))
* **proxy:** prevent recursion errors when debugging pycharm ([#1076](https://github.com/openai/openai-python/issues/1076)) ([3d78798](https://github.com/openai/openai-python/commit/3d787987cf7625b5b502cb0b63a37d55956eaf1d))


### Chores

* add write_to_file binary helper method ([#1077](https://github.com/openai/openai-python/issues/1077)) ([c622c6a](https://github.com/openai/openai-python/commit/c622c6aaf2ae7dc62bd6cdfc053204c5dc3293ac))

## 1.7.2 (2024-01-12)

Full Changelog: [v1.7.1...v1.7.2](https://github.com/openai/openai-python/compare/v1.7.1...v1.7.2)

### Documentation

* **readme:** improve api reference ([#1065](https://github.com/openai/openai-python/issues/1065)) ([745b9e0](https://github.com/openai/openai-python/commit/745b9e08ae0abb8bf4cd87ed40fa450d9ad81ede))


### Refactors

* **api:** remove deprecated endpoints ([#1067](https://github.com/openai/openai-python/issues/1067)) ([199ddcd](https://github.com/openai/openai-python/commit/199ddcdca00c136e4e0c3ff16521eff22acf2a1a))

## 1.7.1 (2024-01-10)

Full Changelog: [v1.7.0...v1.7.1](https://github.com/openai/openai-python/compare/v1.7.0...v1.7.1)

### Chores

* **client:** improve debug logging for failed requests ([#1060](https://github.com/openai/openai-python/issues/1060)) ([cf9a651](https://github.com/openai/openai-python/commit/cf9a6517b4aa0f24bcbe143c54ea908d43dfda92))

## 1.7.0 (2024-01-08)

Full Changelog: [v1.6.1...v1.7.0](https://github.com/openai/openai-python/compare/v1.6.1...v1.7.0)

### Features

* add `None` default value to nullable response properties ([#1043](https://github.com/openai/openai-python/issues/1043)) ([d94b4d3](https://github.com/openai/openai-python/commit/d94b4d3d0adcd1a49a1c25cc9730cef013a3e9c9))


### Bug Fixes

* **client:** correctly use custom http client auth ([#1028](https://github.com/openai/openai-python/issues/1028)) ([3d7d93e](https://github.com/openai/openai-python/commit/3d7d93e951eb7fe09cd9d94d10a62a020398c7f9))


### Chores

* add .keep files for examples and custom code directories ([#1057](https://github.com/openai/openai-python/issues/1057)) ([7524097](https://github.com/openai/openai-python/commit/7524097a47af0fdc8b560186ef3b111b59430741))
* **internal:** bump license ([#1037](https://github.com/openai/openai-python/issues/1037)) ([d828527](https://github.com/openai/openai-python/commit/d828527540ebd97679075f48744818f06311b0cb))
* **internal:** loosen type var restrictions ([#1049](https://github.com/openai/openai-python/issues/1049)) ([e00876b](https://github.com/openai/openai-python/commit/e00876b20b93038450eb317899d8775c7661b8eb))
* **internal:** replace isort with ruff ([#1042](https://github.com/openai/openai-python/issues/1042)) ([f1fbc9c](https://github.com/openai/openai-python/commit/f1fbc9c0d62e7d89ab32c8bdfa39cd94b560690b))
* **internal:** update formatting ([#1041](https://github.com/openai/openai-python/issues/1041)) ([2e9ecee](https://github.com/openai/openai-python/commit/2e9ecee9bdfa8ec33b1b1527d5187483b700fad3))
* **src:** fix typos ([#988](https://github.com/openai/openai-python/issues/988)) ([6a8b806](https://github.com/openai/openai-python/commit/6a8b80624636f9a0e5ada151b2509710a6f74808))
* use property declarations for resource members ([#1047](https://github.com/openai/openai-python/issues/1047)) ([131f6bc](https://github.com/openai/openai-python/commit/131f6bc6b0ccf79119096057079e10906b3d4678))


### Documentation

* fix docstring typos ([#1022](https://github.com/openai/openai-python/issues/1022)) ([ad3fd2c](https://github.com/openai/openai-python/commit/ad3fd2cd19bf91f94473e368554dff39a8f9ad16))
* improve audio example to show how to stream to a file ([#1017](https://github.com/openai/openai-python/issues/1017)) ([d45ed7f](https://github.com/openai/openai-python/commit/d45ed7f0513b167555ae875f1877fa205c5790d2))

## 1.6.1 (2023-12-22)

Full Changelog: [v1.6.0...v1.6.1](https://github.com/openai/openai-python/compare/v1.6.0...v1.6.1)

### Chores

* **internal:** add bin script ([#1001](https://github.com/openai/openai-python/issues/1001)) ([99ffbda](https://github.com/openai/openai-python/commit/99ffbda279bf4c159511fb96b1d5bb688af25437))
* **internal:** use ruff instead of black for formatting ([#1008](https://github.com/openai/openai-python/issues/1008)) ([ceaf9a0](https://github.com/openai/openai-python/commit/ceaf9a06fbd1a846756bb72cce50a69c8cc20bd3))

## 1.6.0 (2023-12-19)

Full Changelog: [v1.5.0...v1.6.0](https://github.com/openai/openai-python/compare/v1.5.0...v1.6.0)

### Features

* **api:** add additional instructions for runs ([#995](https://github.com/openai/openai-python/issues/995)) ([7bf9b75](https://github.com/openai/openai-python/commit/7bf9b75067905449e83e828c12eb384022cff6ca))


### Chores

* **cli:** fix typo in completions ([#985](https://github.com/openai/openai-python/issues/985)) ([d1e9e8f](https://github.com/openai/openai-python/commit/d1e9e8f24df366bb7b796c55a98247c025d229f5))
* **cli:** fix typo in completions ([#986](https://github.com/openai/openai-python/issues/986)) ([626bc34](https://github.com/openai/openai-python/commit/626bc34d82a7057bac99f8b556f9e5f60c261ee7))
* **internal:** fix binary response tests ([#983](https://github.com/openai/openai-python/issues/983)) ([cfb7e30](https://github.com/openai/openai-python/commit/cfb7e308393f2e912e959dd10d68096dd5b3ab9c))
* **internal:** fix typos ([#993](https://github.com/openai/openai-python/issues/993)) ([3b338a4](https://github.com/openai/openai-python/commit/3b338a401b206618774291ff8137deb0cc5f6b4c))
* **internal:** minor utils restructuring ([#992](https://github.com/openai/openai-python/issues/992)) ([5ba576a](https://github.com/openai/openai-python/commit/5ba576ae38d2c4c4d32a21933e0d68e0bc2f0d49))
* **package:** bump minimum typing-extensions to 4.7 ([#994](https://github.com/openai/openai-python/issues/994)) ([0c2da84](https://github.com/openai/openai-python/commit/0c2da84badf416f8b2213983f68bd2b6f9e52f2b))
* **streaming:** update constructor to use direct client names ([#991](https://github.com/openai/openai-python/issues/991)) ([6c3427d](https://github.com/openai/openai-python/commit/6c3427dac8c414658516aeb4caf5d5fd8b11097b))


### Documentation

* upgrade models in examples to latest version ([#989](https://github.com/openai/openai-python/issues/989)) ([cedd574](https://github.com/openai/openai-python/commit/cedd574e5611f3e71e92b523a72ba87bcfe546f1))

## 1.5.0 (2023-12-17)

Full Changelog: [v1.4.0...v1.5.0](https://github.com/openai/openai-python/compare/v1.4.0...v1.5.0)

### Features

* **api:** add token logprobs to chat completions ([#980](https://github.com/openai/openai-python/issues/980)) ([f50e962](https://github.com/openai/openai-python/commit/f50e962b930bd682a4299143b2995337e8571273))


### Chores

* **ci:** run release workflow once per day ([#978](https://github.com/openai/openai-python/issues/978)) ([215476a](https://github.com/openai/openai-python/commit/215476a0b99e0c92ab3e44ddd25de207af32d160))

## 1.4.0 (2023-12-15)

Full Changelog: [v1.3.9...v1.4.0](https://github.com/openai/openai-python/compare/v1.3.9...v1.4.0)

### Features

* **api:** add optional `name` argument + improve docs ([#972](https://github.com/openai/openai-python/issues/972)) ([7972010](https://github.com/openai/openai-python/commit/7972010615820099f662c02821cfbd59e7d6ea44))

## 1.3.9 (2023-12-12)

Full Changelog: [v1.3.8...v1.3.9](https://github.com/openai/openai-python/compare/v1.3.8...v1.3.9)

### Documentation

* improve README timeout comment ([#964](https://github.com/openai/openai-python/issues/964)) ([3c3ed5e](https://github.com/openai/openai-python/commit/3c3ed5edd938a9333e8d2fa47cb4b44178eef89a))
* small Improvement in the async chat response code ([#959](https://github.com/openai/openai-python/issues/959)) ([fb9d0a3](https://github.com/openai/openai-python/commit/fb9d0a358fa232043d9d5c149b6a888d50127c7b))
* small streaming readme improvements ([#962](https://github.com/openai/openai-python/issues/962)) ([f3be2e5](https://github.com/openai/openai-python/commit/f3be2e5cc24988471e6cedb3e34bdfd3123edc63))


### Refactors

* **client:** simplify cleanup ([#966](https://github.com/openai/openai-python/issues/966)) ([5c138f4](https://github.com/openai/openai-python/commit/5c138f4a7947e5b4aae8779fae78ca51269b355a))
* simplify internal error handling ([#968](https://github.com/openai/openai-python/issues/968)) ([d187f6b](https://github.com/openai/openai-python/commit/d187f6b6e4e646cca39c6ca35c618aa5c1bfbd61))

## 1.3.8 (2023-12-08)

Full Changelog: [v1.3.7...v1.3.8](https://github.com/openai/openai-python/compare/v1.3.7...v1.3.8)

### Bug Fixes

* avoid leaking memory when Client.with_options is used ([#956](https://github.com/openai/openai-python/issues/956)) ([e37ecca](https://github.com/openai/openai-python/commit/e37ecca04040ce946822a7e40f5604532a59ee85))
* **errors:** properly assign APIError.body ([#949](https://github.com/openai/openai-python/issues/949)) ([c70e194](https://github.com/openai/openai-python/commit/c70e194f0a253409ec851607ae5219e3b5a8c442))
* **pagination:** use correct type hint for .object ([#943](https://github.com/openai/openai-python/issues/943)) ([23fe7ee](https://github.com/openai/openai-python/commit/23fe7ee48a71539b0d1e95ceff349264aae4090e))


### Chores

* **internal:** enable more lint rules ([#945](https://github.com/openai/openai-python/issues/945)) ([2c8add6](https://github.com/openai/openai-python/commit/2c8add64a261dea731bd162bb0cca222518d5440))
* **internal:** reformat imports ([#939](https://github.com/openai/openai-python/issues/939)) ([ec65124](https://github.com/openai/openai-python/commit/ec651249de2f4e4cf959f816e1b52f03d3b1017a))
* **internal:** reformat imports ([#944](https://github.com/openai/openai-python/issues/944)) ([5290639](https://github.com/openai/openai-python/commit/52906391c9b6633656ec7934e6bbac553ec667cd))
* **internal:** update formatting ([#941](https://github.com/openai/openai-python/issues/941)) ([8e5a156](https://github.com/openai/openai-python/commit/8e5a156d555fe68731ba0604a7455cc03cb451ce))
* **package:** lift anyio v4 restriction ([#927](https://github.com/openai/openai-python/issues/927)) ([be0438a](https://github.com/openai/openai-python/commit/be0438a2e399bb0e0a94907229d02fc61ab479c0))


### Documentation

* fix typo in example ([#950](https://github.com/openai/openai-python/issues/950)) ([54f0ce0](https://github.com/openai/openai-python/commit/54f0ce0000abe32e97ae400f2975c028b8a84273))

## 1.3.7 (2023-12-01)

Full Changelog: [v1.3.6...v1.3.7](https://github.com/openai/openai-python/compare/v1.3.6...v1.3.7)

### Bug Fixes

* **client:** correct base_url setter implementation ([#919](https://github.com/openai/openai-python/issues/919)) ([135d9cf](https://github.com/openai/openai-python/commit/135d9cf2820f1524764bf536a9322830bdcd5875))
* **client:** don't cause crashes when inspecting the module ([#897](https://github.com/openai/openai-python/issues/897)) ([db029a5](https://github.com/openai/openai-python/commit/db029a596c90b1af4ef0bfb1cdf31f54b2f5755d))
* **client:** ensure retried requests are closed ([#902](https://github.com/openai/openai-python/issues/902)) ([e025e6b](https://github.com/openai/openai-python/commit/e025e6bee44ea145d948869ef0c79bac0c376b9f))


### Chores

* **internal:** add tests for proxy change ([#899](https://github.com/openai/openai-python/issues/899)) ([71a13d0](https://github.com/openai/openai-python/commit/71a13d0c70d105b2b97720c72a1003b942cda2ae))
* **internal:** remove unused type var ([#915](https://github.com/openai/openai-python/issues/915)) ([4233bcd](https://github.com/openai/openai-python/commit/4233bcdae5f467f10454fcc008a6e728fa846830))
* **internal:** replace string concatenation with f-strings ([#908](https://github.com/openai/openai-python/issues/908)) ([663a8f6](https://github.com/openai/openai-python/commit/663a8f6dead5aa523d1e8779e75af1dabb1690c4))
* **internal:** replace string concatenation with f-strings ([#909](https://github.com/openai/openai-python/issues/909)) ([caab767](https://github.com/openai/openai-python/commit/caab767156375114078cf8d85031863361326b5f))


### Documentation

* fix typo in readme ([#904](https://github.com/openai/openai-python/issues/904)) ([472cd44](https://github.com/openai/openai-python/commit/472cd44e45a45b0b4f12583a5402e8aeb121d7a2))
* **readme:** update example snippets ([#907](https://github.com/openai/openai-python/issues/907)) ([bbb648e](https://github.com/openai/openai-python/commit/bbb648ef81eb11f81b457e2cbf33a832f4d29a76))

## 1.3.6 (2023-11-28)

Full Changelog: [v1.3.5...v1.3.6](https://github.com/openai/openai-python/compare/v1.3.5...v1.3.6)

### Bug Fixes

* **client:** add support for streaming binary responses ([#866](https://github.com/openai/openai-python/issues/866)) ([2470d25](https://github.com/openai/openai-python/commit/2470d251b751e92e8950bc9e3026965e9925ac1c))


### Chores

* **deps:** bump mypy to v1.7.1 ([#891](https://github.com/openai/openai-python/issues/891)) ([11fcb2a](https://github.com/openai/openai-python/commit/11fcb2a3cd4205b307c13c65ad47d9e315b0084d))
* **internal:** send more detailed x-stainless headers ([#877](https://github.com/openai/openai-python/issues/877)) ([69e0549](https://github.com/openai/openai-python/commit/69e054947d587ff2548b101ece690d21d3c38f74))
* revert binary streaming change ([#875](https://github.com/openai/openai-python/issues/875)) ([0a06d6a](https://github.com/openai/openai-python/commit/0a06d6a078c5ee898dae75bab4988e1a1936bfbf))


### Documentation

* **readme:** minor updates ([#894](https://github.com/openai/openai-python/issues/894)) ([5458457](https://github.com/openai/openai-python/commit/54584572df4c2a086172d812c6acb84e3405328b))
* **readme:** update examples ([#893](https://github.com/openai/openai-python/issues/893)) ([124da87](https://github.com/openai/openai-python/commit/124da8720c44d40c083d29179f46a265761c1f4f))
* update readme code snippet ([#890](https://github.com/openai/openai-python/issues/890)) ([c522f21](https://github.com/openai/openai-python/commit/c522f21e2a685454185d57e462e74a28499460f9))

## 1.3.5 (2023-11-21)

Full Changelog: [v1.3.4...v1.3.5](https://github.com/openai/openai-python/compare/v1.3.4...v1.3.5)

### Bug Fixes

* **azure:** ensure custom options can be passed to copy ([#858](https://github.com/openai/openai-python/issues/858)) ([05ca0d6](https://github.com/openai/openai-python/commit/05ca0d68e84d40f975614d27cb52c0f382104377))


### Chores

* **package:** add license classifier ([#826](https://github.com/openai/openai-python/issues/826)) ([bec004d](https://github.com/openai/openai-python/commit/bec004d030b277e05bdd51f66fae1e881291c30b))
* **package:** add license classifier metadata ([#860](https://github.com/openai/openai-python/issues/860)) ([80dffb1](https://github.com/openai/openai-python/commit/80dffb17ff0a10b0b9ea704c4247521e48b68408))

## 1.3.4 (2023-11-21)

Full Changelog: [v1.3.3...v1.3.4](https://github.com/openai/openai-python/compare/v1.3.3...v1.3.4)

### Bug Fixes

* **client:** attempt to parse unknown json content types ([#854](https://github.com/openai/openai-python/issues/854)) ([ba50466](https://github.com/openai/openai-python/commit/ba5046611029a67714d5120b9cc6a3c7fecce10c))


### Chores

* **examples:** fix static types in assistants example ([#852](https://github.com/openai/openai-python/issues/852)) ([5b47b2c](https://github.com/openai/openai-python/commit/5b47b2c542b9b4fb143af121022e2d5ad0890ef4))

## 1.3.3 (2023-11-17)

Full Changelog: [v1.3.2...v1.3.3](https://github.com/openai/openai-python/compare/v1.3.2...v1.3.3)

### Chores

* **internal:** update type hint for helper function ([#846](https://github.com/openai/openai-python/issues/846)) ([9a5966c](https://github.com/openai/openai-python/commit/9a5966c70fce620a183de580938556730564a405))

## 1.3.2 (2023-11-16)

Full Changelog: [v1.3.1...v1.3.2](https://github.com/openai/openai-python/compare/v1.3.1...v1.3.2)

### Documentation

* **readme:** minor updates ([#841](https://github.com/openai/openai-python/issues/841)) ([7273ad1](https://github.com/openai/openai-python/commit/7273ad1510043d3e264969c72403a1a237401910))

## 1.3.1 (2023-11-16)

Full Changelog: [v1.3.0...v1.3.1](https://github.com/openai/openai-python/compare/v1.3.0...v1.3.1)

### Chores

* **internal:** add publish script ([#838](https://github.com/openai/openai-python/issues/838)) ([3ea41bc](https://github.com/openai/openai-python/commit/3ea41bcede374c4e5c92d85108281637c3382e12))

## 1.3.0 (2023-11-15)

Full Changelog: [v1.2.4...v1.3.0](https://github.com/openai/openai-python/compare/v1.2.4...v1.3.0)

### Features

* **api:** add gpt-3.5-turbo-1106 ([#813](https://github.com/openai/openai-python/issues/813)) ([9bb3c4e](https://github.com/openai/openai-python/commit/9bb3c4ed88c890db2605a793aa39fffa1d84e8ef))
* **client:** support reading the base url from an env variable ([#829](https://github.com/openai/openai-python/issues/829)) ([ca5fdc6](https://github.com/openai/openai-python/commit/ca5fdc6ca006a3550cc5eeea70dd3d96b9ba305a))


### Bug Fixes

* **breaking!:** correct broken type names in moderation categories  ([#811](https://github.com/openai/openai-python/issues/811)) ([0bc211f](https://github.com/openai/openai-python/commit/0bc211fd46f4fcc1f7687bdfdce26894b679cb4f))


### Chores

* fix typo in docs and add request header for function calls ([#807](https://github.com/openai/openai-python/issues/807)) ([cbef703](https://github.com/openai/openai-python/commit/cbef7030c7b21a0c766fe83c62657cea1cd8d31c))
* **internal:** fix devcontainer interpeter path ([#810](https://github.com/openai/openai-python/issues/810)) ([0acc07d](https://github.com/openai/openai-python/commit/0acc07dd8281ba881f91689b8a5e4254e8743fbc))


### Documentation

* add azure env vars ([#814](https://github.com/openai/openai-python/issues/814)) ([bd8e32a](https://github.com/openai/openai-python/commit/bd8e32a380218d0c9ff43643ccc1a25b3c35120d))
* fix code comment typo ([#790](https://github.com/openai/openai-python/issues/790)) ([8407a27](https://github.com/openai/openai-python/commit/8407a27e848ae611eb087c8d10632447d7c55498))
* **readme:** fix broken azure_ad notebook link ([#781](https://github.com/openai/openai-python/issues/781)) ([3b92cdf](https://github.com/openai/openai-python/commit/3b92cdfa5490b50a72811bec2f6e54e070847961))

## 1.2.4 (2023-11-13)

Full Changelog: [v1.2.3...v1.2.4](https://github.com/openai/openai-python/compare/v1.2.3...v1.2.4)

### Bug Fixes

* **client:** retry if SSLWantReadError occurs in the async client ([#804](https://github.com/openai/openai-python/issues/804)) ([be82288](https://github.com/openai/openai-python/commit/be82288f3c88c10c9ac20ba3b8cb53b5c7a4e2f9))

## 1.2.3 (2023-11-10)

Full Changelog: [v1.2.2...v1.2.3](https://github.com/openai/openai-python/compare/v1.2.2...v1.2.3)

### Bug Fixes

* **cli/audio:** file format detection failing for whisper ([#733](https://github.com/openai/openai-python/issues/733)) ([01079d6](https://github.com/openai/openai-python/commit/01079d6dca13e0ec158dff81e0706d8a9d6c02ef))
* **client:** correctly flush the stream response body ([#771](https://github.com/openai/openai-python/issues/771)) ([0d52731](https://github.com/openai/openai-python/commit/0d5273165c96286f8456ae04b9eb0de5144e52f8))
* **client:** serialise pydantic v1 default fields correctly in params ([#776](https://github.com/openai/openai-python/issues/776)) ([d4c49ad](https://github.com/openai/openai-python/commit/d4c49ad2be9c0d926eece5fd33f6836279ea21e2))
* **models:** mark unknown fields as set in pydantic v1 ([#772](https://github.com/openai/openai-python/issues/772)) ([ae032a1](https://github.com/openai/openai-python/commit/ae032a1ba4efa72284a572bfaf0305af50142835))
* prevent IndexError in fine-tunes CLI ([#768](https://github.com/openai/openai-python/issues/768)) ([42f1633](https://github.com/openai/openai-python/commit/42f16332cf0f96f243f9797d6406283865254355))


### Documentation

* reword package description ([#764](https://github.com/openai/openai-python/issues/764)) ([9ff10df](https://github.com/openai/openai-python/commit/9ff10df30ca2d44978eb5f982ccf039c9f1bf1bf))

## 1.2.2 (2023-11-09)

Full Changelog: [v1.2.1...v1.2.2](https://github.com/openai/openai-python/compare/v1.2.1...v1.2.2)

### Bug Fixes

* **client:** correctly assign error properties ([#759](https://github.com/openai/openai-python/issues/759)) ([ef264d2](https://github.com/openai/openai-python/commit/ef264d2293b77784f69039291ca2a17a454851cb))


### Documentation

* **readme:** link to migration guide ([#761](https://github.com/openai/openai-python/issues/761)) ([ddde839](https://github.com/openai/openai-python/commit/ddde8392be19e7ad77280374806667ecaef612da))

## 1.2.1 (2023-11-09)

Full Changelog: [v1.2.0...v1.2.1](https://github.com/openai/openai-python/compare/v1.2.0...v1.2.1)

### Documentation

* **readme:** fix nested params example ([#756](https://github.com/openai/openai-python/issues/756)) ([ffbe5ec](https://github.com/openai/openai-python/commit/ffbe5eca0f8790ebcdb27ffe845da178a3ef4c45))


### Refactors

* **client:** deprecate files.retrieve_content in favour of files.content ([#753](https://github.com/openai/openai-python/issues/753)) ([eea5bc1](https://github.com/openai/openai-python/commit/eea5bc173466f63a6e84bd2d741b4873ca056b4c))

## 1.2.0 (2023-11-08)

Full Changelog: [v1.1.2...v1.2.0](https://github.com/openai/openai-python/compare/v1.1.2...v1.2.0)

### Features

* **api:** unify function types ([#741](https://github.com/openai/openai-python/issues/741)) ([ed16c4d](https://github.com/openai/openai-python/commit/ed16c4d2fec6cf4e33235d82b05ed9a777752204))
* **client:** support passing chunk size for binary responses ([#747](https://github.com/openai/openai-python/issues/747)) ([c0c89b7](https://github.com/openai/openai-python/commit/c0c89b77a69ef098900e3a194894efcf72085d36))


### Bug Fixes

* **api:** update embedding response object type ([#739](https://github.com/openai/openai-python/issues/739)) ([29182c4](https://github.com/openai/openai-python/commit/29182c4818e2c56f46e961dba33e31dc30c25519))
* **client:** show a helpful error message if the v0 API is used ([#743](https://github.com/openai/openai-python/issues/743)) ([920567c](https://github.com/openai/openai-python/commit/920567cb04df48a7f6cd2a3402a0b1f172c6290e))


### Chores

* **internal:** improve github devcontainer setup ([#737](https://github.com/openai/openai-python/issues/737)) ([0ac1abb](https://github.com/openai/openai-python/commit/0ac1abb07ec687a4f7b1150be10054dbd6e7cfbc))


### Refactors

* **api:** rename FunctionObject to FunctionDefinition ([#746](https://github.com/openai/openai-python/issues/746)) ([1afd138](https://github.com/openai/openai-python/commit/1afd13856c0e586ecbde8b24fe4f4bad9beeefdf))

## 1.1.2 (2023-11-08)

Full Changelog: [v1.1.1...v1.1.2](https://github.com/openai/openai-python/compare/v1.1.1...v1.1.2)

### Bug Fixes

* **api:** accidentally required params, add new models & other fixes ([#729](https://github.com/openai/openai-python/issues/729)) ([03c3e03](https://github.com/openai/openai-python/commit/03c3e03fc758cf4e59b81edf73a2618d80b560b7))
* asssitant_deleted -&gt; assistant_deleted ([#711](https://github.com/openai/openai-python/issues/711)) ([287b51e](https://github.com/openai/openai-python/commit/287b51e4f7cede9667c118007de1275eb04772c6))


### Chores

* **docs:** fix github links ([#719](https://github.com/openai/openai-python/issues/719)) ([0cda8ca](https://github.com/openai/openai-python/commit/0cda8cab718d53d7dc0604d9fac52838c9391565))
* **internal:** fix some typos ([#718](https://github.com/openai/openai-python/issues/718)) ([894ad87](https://github.com/openai/openai-python/commit/894ad874aaa5d74530f561896ff31f68693418da))
