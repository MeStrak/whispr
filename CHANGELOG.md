## [2.0.2](https://github.com/Sanofi-IADC/whispr/compare/v2.0.1...v2.0.2) (2021-01-02)


### Bug Fixes

* **index:** add compound index on timestamp and type ([02ae7d8](https://github.com/Sanofi-IADC/whispr/commit/02ae7d86fc43a31fc7fac59a9464feb800d70596))

## [2.0.1](https://github.com/Sanofi-IADC/whispr/compare/v2.0.0...v2.0.1) (2020-12-04)


### Bug Fixes

* **subscriptions:** added parser to Redis to handle Dates ([f95bf85](https://github.com/Sanofi-IADC/whispr/commit/f95bf8508f707b0c08e288be645249ecd4f02375))

# [2.0.0](https://github.com/Sanofi-IADC/whispr/compare/v1.8.2...v2.0.0) (2020-12-04)


### Bug Fixes

* **server-port:** reverted port of the server to 3000 ([b4f84ff](https://github.com/Sanofi-IADC/whispr/commit/b4f84ffedebb57a6db8e1f7845394a013ed965fd))
* **timestamp:** fixed multiple bugs related to timestamp ([3bbcff6](https://github.com/Sanofi-IADC/whispr/commit/3bbcff67c421f3e545fb16fa093e915c8d7c4b45))
* add access keys to test.env ([7c58ee0](https://github.com/Sanofi-IADC/whispr/commit/7c58ee0ad6280116c331cceeb341c6f2f2a578b0))
* save timestamp and updated as dates ([c2df52d](https://github.com/Sanofi-IADC/whispr/commit/c2df52d68480c56beb6cf67665df01503750b845))
* **dependency maintenance:** manually update some non-major dependencies ([f5d8ed6](https://github.com/Sanofi-IADC/whispr/commit/f5d8ed6b5905cc52229eaef33bd6b2922b80df42))
* **dependency maintenance:** update all non-major dependencies ([efa12ed](https://github.com/Sanofi-IADC/whispr/commit/efa12ed911deea49acdb72a35c327e60aa46392c))
* **dependency maintenance:** update all non-major dependencies ([d608abc](https://github.com/Sanofi-IADC/whispr/commit/d608abc333792e2c7ec7de66a5ba9fb3dbd7e3b3))
* **dependency maintenance:** update dependency @apollo/gateway to v0.21.3 ([7470f66](https://github.com/Sanofi-IADC/whispr/commit/7470f66eba205444d29559e822fb198422250a8a))
* **dependency maintenance:** update dependency @nestjs/graphql to v7.8.2 ([0ffe628](https://github.com/Sanofi-IADC/whispr/commit/0ffe6287b1b2343f95cd0981e960aebe062507d5))
* **dependency maintenance:** update dependency @nestjs/mongoose to v7.1.0 ([ea18eaa](https://github.com/Sanofi-IADC/whispr/commit/ea18eaac5d4e7155b1fd43ddc4162c84f8b804b1))
* **dependency maintenance:** update dependency @nestjs/mongoose to v7.1.1 ([e1f6e6a](https://github.com/Sanofi-IADC/whispr/commit/e1f6e6add01ca334e0aa5f7fb3387bc32bff66de))
* **dependency maintenance:** update dependency amazon-cognito-identity-js to v4.5.5 ([8e5d867](https://github.com/Sanofi-IADC/whispr/commit/8e5d8675a28ed33f5ca0997c8d5161a56ab7c5c4))
* **dependency maintenance:** update dependency aws-sdk to v2.797.0 ([7852f99](https://github.com/Sanofi-IADC/whispr/commit/7852f999231522ebcfd05a012ec6e7a335e7c751))
* **dependency maintenance:** update dependency mongoose to v5.10.10 ([a5a4e63](https://github.com/Sanofi-IADC/whispr/commit/a5a4e635911fff30b44318d32a66bc9dabccf8d4))
* **webhook:** added CA_CERTIFICATE_PATH to validationSchema ([7cc6460](https://github.com/Sanofi-IADC/whispr/commit/7cc64603c0eed9a1a26713a9aff12d3c1df49555))
* **webhook:** allow communication without a proxy ([9faa436](https://github.com/Sanofi-IADC/whispr/commit/9faa4363b0a8d1b072f5f2db0f3b0827094b1527))
* **webhook:** fixed ca-array in tunnel ([4d09565](https://github.com/Sanofi-IADC/whispr/commit/4d0956554b625fcba78bce9a70024efa3b587ae6))
* **webhooks:** read ca-file from filesystem instead of env ([5f59a25](https://github.com/Sanofi-IADC/whispr/commit/5f59a25605ea81620b3d9176460ac33afdf25079))
* fix linting issues with prettier-eslint ([18a999f](https://github.com/Sanofi-IADC/whispr/commit/18a999fd466093354c830786a87073c3fc11d125))
* **webhook:** flatten error-log of webhook calls, because they are circular objects ([69dd670](https://github.com/Sanofi-IADC/whispr/commit/69dd67056368bcd9cca529136e9b6dc8d41e38eb))
* **webhooks:** set https-Agent to correctly use Proxy & CA_Certificate for Webhook calls ([d0521bb](https://github.com/Sanofi-IADC/whispr/commit/d0521bb0d6a2b220c2a7e187bd1f740548340f4b))
* fix linting issues with prettier-eslint ([a0fccdf](https://github.com/Sanofi-IADC/whispr/commit/a0fccdf28e3cadcab83a1efedfe1dc3d16f154b7))
* **webhooks:** set https-Agent to correctly use Proxy & CA_Certificate for Webhook calls ([f513f85](https://github.com/Sanofi-IADC/whispr/commit/f513f857017718eaf18b855f9f7f8e1229bbd9e1))
* reverted dependencies to last working release ([201f390](https://github.com/Sanofi-IADC/whispr/commit/201f390284e5817cd116b99b19aab7ec09a6ee28))
* **dependency maintenance:** update dependency graphql-tools to v6.2.6 ([c73b024](https://github.com/Sanofi-IADC/whispr/commit/c73b02488b3c6698590709a2273fe9f2b3089be7))
* **whisp:** convert timestamp to ISO-Timestamp when provided in new whisp ([95b35ea](https://github.com/Sanofi-IADC/whispr/commit/95b35ea9eb4b6b2b51b21462b8a2818aad4a4ece))
* **whisp:** convert timestamp to ISO-Timestamp when provided in new whisp ([5a98d81](https://github.com/Sanofi-IADC/whispr/commit/5a98d81c48bca2c24d6db745496f0b0ea9910301))


### Features

* **dev:** expose localstack port for debugging purpose ([e6c6a4e](https://github.com/Sanofi-IADC/whispr/commit/e6c6a4e24a357ab1da9ba56d4deee34bb697c9a4))
* **index:** add compound index to applicationID and closed ([e5747e0](https://github.com/Sanofi-IADC/whispr/commit/e5747e0cb657d6cc906eea4df29cded9cdedc22e))
* **webhook:** multiple CAs can be added by using a comma separated list ([acda58f](https://github.com/Sanofi-IADC/whispr/commit/acda58fc7faa801919af980b0d1a6d9209c31913))


### Performance Improvements

* whispsCount uses mongo documentCount ([2e2a0d5](https://github.com/Sanofi-IADC/whispr/commit/2e2a0d515ad1ea5bc80ee26b15a420370fdb0508))


### BREAKING CHANGES

* **whisp:** When a timestamp is provided in createWhisp, it will be converted to ISO-Timestamp instead of UTC-Timestamp

## [1.8.2](https://github.com/Sanofi-IADC/whispr/compare/v1.8.1...v1.8.2) (2020-12-02)


### Bug Fixes

* assign default values ([5e5e6ac](https://github.com/Sanofi-IADC/whispr/commit/5e5e6ac5025bfb72486c3fbe09e53944241c52ed))

## [1.8.1](https://github.com/Sanofi-IADC/whispr/compare/v1.8.0...v1.8.1) (2020-12-01)


### Bug Fixes

* revert test.env ([edc53e5](https://github.com/Sanofi-IADC/whispr/commit/edc53e551fe1b64f9ad15d6b501669b07e57edb1))
* test.env ([df56000](https://github.com/Sanofi-IADC/whispr/commit/df56000b3293b87fbad7301fcd4c9e60a0779771))

# [1.8.0](https://github.com/Sanofi-IADC/whispr/compare/v1.7.6...v1.8.0) (2020-11-30)


### Features

* add tags to whisps ([f3a4ee9](https://github.com/Sanofi-IADC/whispr/commit/f3a4ee993272f2ecf18ff6eaf877297e9a580a55))
* changed linting rules & fixed linting warning ([7c488a9](https://github.com/Sanofi-IADC/whispr/commit/7c488a91c0e4d5ff81760da6a2b2b57f52d61bfb))
* create own tag collection ([d06ae7a](https://github.com/Sanofi-IADC/whispr/commit/d06ae7a09c94f71bff7926f6f8e430c3949dd8d5))
* **tagGroup:** added closed, closedBy and ClosedById to TagGroup ([00eca58](https://github.com/Sanofi-IADC/whispr/commit/00eca58a6ae6b8389c7a0acad856d8ff7271494b))

## [1.7.6](https://github.com/Sanofi-IADC/whispr/compare/v1.7.5...v1.7.6) (2020-11-26)


### Bug Fixes

* **file-upload:** removed custom FileUpload-Scalar and use the one from apollo-server ([3380ab9](https://github.com/Sanofi-IADC/whispr/commit/3380ab931d3fd353a3f270fe8c4abb084049bec1))

## [1.7.5](https://github.com/Sanofi-IADC/whispr/compare/v1.7.4...v1.7.5) (2020-11-23)


### Bug Fixes

* **dependency maintenance:** update dependency @nestjs/mongoose to v7.1.1 ([d98a4c6](https://github.com/Sanofi-IADC/whispr/commit/d98a4c6c11f29247b67f192fb8a5196d6beb73ca))

## [1.7.4](https://github.com/Sanofi-IADC/whispr/compare/v1.7.3...v1.7.4) (2020-11-22)


### Bug Fixes

* **dependency maintenance:** update dependency @apollo/gateway to v0.21.3 ([49f18f9](https://github.com/Sanofi-IADC/whispr/commit/49f18f97353ad6695cce959915d9b5727bf8255e))
* **dependency maintenance:** update dependency @nestjs/graphql to v7.8.2 ([ec734a6](https://github.com/Sanofi-IADC/whispr/commit/ec734a6ff3243e989568c797c1283baf50b29cdc))

## [1.7.3](https://github.com/Sanofi-IADC/whispr/compare/v1.7.2...v1.7.3) (2020-11-22)


### Bug Fixes

* **dependency maintenance:** update dependency @nestjs/mongoose to v7.1.0 ([6f44c46](https://github.com/Sanofi-IADC/whispr/commit/6f44c46dfc8f771bf611e9be3cf5c1018cb55bfd))
* **dependency maintenance:** update dependency amazon-cognito-identity-js to v4.5.5 ([55c20bf](https://github.com/Sanofi-IADC/whispr/commit/55c20bf3535dd67b91a3020b12108892f1c55737))
* **dependency maintenance:** update dependency aws-sdk to v2.797.0 ([d3c8171](https://github.com/Sanofi-IADC/whispr/commit/d3c8171cb3e85dfaf727f3df16216c0d52648013))

## [1.7.2](https://github.com/Sanofi-IADC/whispr/compare/v1.7.1...v1.7.2) (2020-11-19)


### Bug Fixes

* **dependency maintenance:** manually update some non-major dependencies ([c7e3f6a](https://github.com/Sanofi-IADC/whispr/commit/c7e3f6ace6a22573515ec22f31aaf4e025b13fb1))

## [1.7.1](https://github.com/Sanofi-IADC/whispr/compare/v1.7.0...v1.7.1) (2020-11-17)


### Bug Fixes

* **webhook:** fixed ca-array in tunnel ([348da19](https://github.com/Sanofi-IADC/whispr/commit/348da19fc98f69a377fe7e76ca290a7270244d79))

# [1.7.0](https://github.com/Sanofi-IADC/whispr/compare/v1.6.0...v1.7.0) (2020-11-16)


### Bug Fixes

* **webhook:** allow communication without a proxy ([387280c](https://github.com/Sanofi-IADC/whispr/commit/387280c32fec18ea093e169bd8d209b8449ca26f))


### Features

* **webhook:** multiple CAs can be added by using a comma separated list ([c1c6073](https://github.com/Sanofi-IADC/whispr/commit/c1c6073edccea2f67958b4ab51577495d8b59860))

# [1.6.0](https://github.com/Sanofi-IADC/whispr/compare/v1.5.0...v1.6.0) (2020-11-16)


### Features

* **dev:** expose localstack port for debugging purpose ([e497962](https://github.com/Sanofi-IADC/whispr/commit/e497962923f9acf57e644adf9f0456942fa836ec))

# [1.5.0](https://github.com/Sanofi-IADC/whispr/compare/v1.4.17...v1.5.0) (2020-11-12)


### Features

* **index:** add compound index to applicationID and closed ([f8adce2](https://github.com/Sanofi-IADC/whispr/commit/f8adce2dcccf4a104a4812b0105baae784f30d9f))

## [1.4.17](https://github.com/Sanofi-IADC/whispr/compare/v1.4.16...v1.4.17) (2020-11-09)


### Bug Fixes

* **webhook:** added CA_CERTIFICATE_PATH to validationSchema ([7730bcc](https://github.com/Sanofi-IADC/whispr/commit/7730bccdb7801d06be666eff16658d3dcc610668))

## [1.4.16](https://github.com/Sanofi-IADC/whispr/compare/v1.4.15...v1.4.16) (2020-11-06)


### Bug Fixes

* **webhooks:** read ca-file from filesystem instead of env ([e1d654a](https://github.com/Sanofi-IADC/whispr/commit/e1d654a706e3adbc42dfca2fada4031bb475bbf7))

## [1.4.15](https://github.com/Sanofi-IADC/whispr/compare/v1.4.14...v1.4.15) (2020-11-06)


### Bug Fixes

* **webhook:** flatten error-log of webhook calls, because they are circular objects ([3af072b](https://github.com/Sanofi-IADC/whispr/commit/3af072bb1830a79c6dc57ba52f63ff3ac58c1830))
* fix linting issues with prettier-eslint ([f697231](https://github.com/Sanofi-IADC/whispr/commit/f697231f3a70f52f7d22051e7751ab5f8134cade))
* **webhooks:** set https-Agent to correctly use Proxy & CA_Certificate for Webhook calls ([2d732a8](https://github.com/Sanofi-IADC/whispr/commit/2d732a8fb9b136c6eb47983e2a34ad7ded6cd17a))

## [1.4.14](https://github.com/Sanofi-IADC/whispr/compare/v1.4.13...v1.4.14) (2020-11-05)


### Bug Fixes

* fix linting issues with prettier-eslint ([f3c4b20](https://github.com/Sanofi-IADC/whispr/commit/f3c4b201e538e93e5209bbc28194b52cc658e43e))
* **webhooks:** set https-Agent to correctly use Proxy & CA_Certificate for Webhook calls ([d8e4baf](https://github.com/Sanofi-IADC/whispr/commit/d8e4bafa1855f42a696d34712ca8b21e31fcb2c6))

## [1.4.13](https://github.com/Sanofi-IADC/whispr/compare/v1.4.12...v1.4.13) (2020-11-02)


### Bug Fixes

* reverted dependencies to last working release ([93b92a1](https://github.com/Sanofi-IADC/whispr/commit/93b92a152e3b5f64875f29d56512a537783c5f4f))
* **dependency maintenance:** update all non-major dependencies ([f5bac54](https://github.com/Sanofi-IADC/whispr/commit/f5bac54a5252eecc69fa2fb1bcc7fb20e5c04ea4))
* **dependency maintenance:** update all non-major dependencies ([345988a](https://github.com/Sanofi-IADC/whispr/commit/345988a2eb35d8f0e43559f4faf8516a1112450a))
* **dependency maintenance:** update all non-major dependencies ([1fcad2b](https://github.com/Sanofi-IADC/whispr/commit/1fcad2b341b8c81387416190e9e9e4395ec90087))
* **dependency maintenance:** update all non-major dependencies ([0218274](https://github.com/Sanofi-IADC/whispr/commit/0218274eb3e2d0d3bd83148e2fe198d4b454ed69))
* **dependency maintenance:** update all non-major dependencies ([1fde00f](https://github.com/Sanofi-IADC/whispr/commit/1fde00f3460e4153d587d6fab8acc6a7f41a1458))
* **dependency maintenance:** update all non-major dependencies ([29e4d69](https://github.com/Sanofi-IADC/whispr/commit/29e4d69e2a2446fe2d8dfecac8acbce6bb359859))
* **dependency maintenance:** update dependency @apollo/gateway to v0.20.1 ([2898ed9](https://github.com/Sanofi-IADC/whispr/commit/2898ed985c770beebc0b4c63609665f5fc3f7513))
* **dependency maintenance:** update dependency @apollo/gateway to v0.20.4 ([6ecbecd](https://github.com/Sanofi-IADC/whispr/commit/6ecbecd98afd307576991bc1a3baff7b62bb8a90))
* **dependency maintenance:** update dependency amazon-cognito-identity-js to v4.3.5 ([4053fe4](https://github.com/Sanofi-IADC/whispr/commit/4053fe4849c1a6168cd81c3dfc2819c9f8326306))
* **dependency maintenance:** update dependency apollo-server-fastify to v2.18.2 ([343df48](https://github.com/Sanofi-IADC/whispr/commit/343df484e8a65d1663ff2dcb12353e06cf16ced3))
* **dependency maintenance:** update dependency cross-fetch to v3.0.6 ([cb5fc7f](https://github.com/Sanofi-IADC/whispr/commit/cb5fc7f23dd29ff6e381138fa7db687660dc4f81))
* **dependency maintenance:** update dependency graphql-tools to v6.2.3 ([27843bc](https://github.com/Sanofi-IADC/whispr/commit/27843bc0af3bf69f4d69aa073154c7afb8972498))
* **dependency maintenance:** update dependency graphql-tools to v6.2.4 ([7d365e5](https://github.com/Sanofi-IADC/whispr/commit/7d365e5e6cdcf91109dbe4ce3fcd8e74ef648de1))
* **dependency maintenance:** update dependency graphql-tools to v6.2.6 ([dc0396b](https://github.com/Sanofi-IADC/whispr/commit/dc0396bf90e3241bc9a8c3f1cc66fca39ec9671a))
* **dependency maintenance:** update dependency mongoose to v5.10.10 ([c20d808](https://github.com/Sanofi-IADC/whispr/commit/c20d808fb5b06bd9ce6256d81bea8833cf6228a0))
* **dependency maintenance:** update dependency mongoose to v5.10.2 ([91f29f1](https://github.com/Sanofi-IADC/whispr/commit/91f29f1974c9f8e09cac58d9888cea5b0e354ef3))
* **dependency maintenance:** update dependency mongoose to v5.10.3 ([0d7e207](https://github.com/Sanofi-IADC/whispr/commit/0d7e207600d72549ca9fb58884b12b75375cb0da))
* **dependency maintenance:** update dependency mongoose to v5.10.5 ([f621ae5](https://github.com/Sanofi-IADC/whispr/commit/f621ae57e6fe3a9aceceb6cc8b942bfef971a2c8))
* **dependency maintenance:** update dependency mongoose to v5.10.6 ([ec803ff](https://github.com/Sanofi-IADC/whispr/commit/ec803ff12071b41d7ae3fdfa9dbce0aeca7b17e5))
* **dependency maintenance:** update dependency mongoose to v5.10.7 ([362dd55](https://github.com/Sanofi-IADC/whispr/commit/362dd55410c88f3223ed854ea076dca6ff84089a))
* **dependency maintenance:** update dependency mongoose to v5.10.9 ([515cc5d](https://github.com/Sanofi-IADC/whispr/commit/515cc5dc520cf6c85c9883e8ecb23759d5973814))
* **dependency maintenance:** update dependency rxjs to v6.6.3 ([59b97ef](https://github.com/Sanofi-IADC/whispr/commit/59b97ef88c05353795f3708affb073a5f9e2193d))
* **dependency maintenance:** update nest monorepo to v7.4.3 ([bb95005](https://github.com/Sanofi-IADC/whispr/commit/bb9500525d41a66c38bd3845cf6ad5864511a42c))
* **dependency maintenance:** update nest monorepo to v7.4.4 ([70eeca5](https://github.com/Sanofi-IADC/whispr/commit/70eeca51ef21a329ce4925e03cf1992f31413a5a))


### Performance Improvements

* whispsCount uses mongo documentCount ([9b7cb4e](https://github.com/Sanofi-IADC/whispr/commit/9b7cb4eb081f987f50528dfa17b284628b0cd0fa))

## [1.4.12](https://github.com/Sanofi-IADC/whispr/compare/v1.4.11...v1.4.12) (2020-08-24)


### Bug Fixes

* **dependency maintenance:** update dependency vuepress to v1.5.4 ([7e03161](https://github.com/Sanofi-IADC/whispr/commit/7e031614ba6611623b214fa6aab88ccb79f3e9af))

## [1.4.11](https://github.com/Sanofi-IADC/whispr/compare/v1.4.10...v1.4.11) (2020-08-24)


### Bug Fixes

* **dependency maintenance:** update dependency mongoose to v5.9.29 ([a59b023](https://github.com/Sanofi-IADC/whispr/commit/a59b0234f6c86124f354e5bc07edebfd542a777e))

## [1.4.10](https://github.com/Sanofi-IADC/whispr/compare/v1.4.9...v1.4.10) (2020-08-24)


### Bug Fixes

* **dependency maintenance:** update dependency amazon-cognito-identity-js to v4.3.4 ([01fe4ab](https://github.com/Sanofi-IADC/whispr/commit/01fe4ab3fc7316fe257c8083fc147ee16534662f))

## [1.4.9](https://github.com/Sanofi-IADC/whispr/compare/v1.4.8...v1.4.9) (2020-08-17)


### Bug Fixes

* **dependency maintenance:** update dependency lodash to v4.17.20 ([352d41a](https://github.com/Sanofi-IADC/whispr/commit/352d41a1e3a2af60d7a22963956fa95261b0a685))

## [1.4.8](https://github.com/Sanofi-IADC/whispr/compare/v1.4.7...v1.4.8) (2020-08-17)


### Bug Fixes

* **dependency maintenance:** update dependency graphql-tools to v6.0.18 ([73d6c66](https://github.com/Sanofi-IADC/whispr/commit/73d6c66c136d549eedef3e8b8af73252688cbac2))

## [1.4.7](https://github.com/Sanofi-IADC/whispr/compare/v1.4.6...v1.4.7) (2020-08-10)


### Bug Fixes

* **dependency maintenance:** update dependency vuepress to v1.5.3 ([ffe34a5](https://github.com/Sanofi-IADC/whispr/commit/ffe34a5519b04e99bf3ba282919314d6f1f57ce9))

## [1.4.6](https://github.com/Sanofi-IADC/whispr/compare/v1.4.5...v1.4.6) (2020-08-10)


### Bug Fixes

* **dependency maintenance:** update dependency mongoose to v5.9.28 ([360030c](https://github.com/Sanofi-IADC/whispr/commit/360030c5332078cbfb4676c0c2cea0be0d6a4baf))

## [1.4.5](https://github.com/Sanofi-IADC/whispr/compare/v1.4.4...v1.4.5) (2020-08-10)


### Bug Fixes

* **dependency maintenance:** update dependency graphql-tools to v6.0.16 ([acf6832](https://github.com/Sanofi-IADC/whispr/commit/acf6832240a0b35bcb424efcb325e27f68028aa8))

## [1.4.4](https://github.com/Sanofi-IADC/whispr/compare/v1.4.3...v1.4.4) (2020-08-10)


### Bug Fixes

* **dependency maintenance:** update dependency graphql-redis-subscriptions to v2.2.2 ([7d16656](https://github.com/Sanofi-IADC/whispr/commit/7d166568e3654d01f37ea4229320f1771fc741e3))

## [1.4.3](https://github.com/Sanofi-IADC/whispr/compare/v1.4.2...v1.4.3) (2020-08-03)


### Bug Fixes

* **dependency maintenance:** pin dependencies ([6b86d17](https://github.com/Sanofi-IADC/whispr/commit/6b86d178b86d86ef38cb8532d18b52d8dadec8d9))

## [1.4.2](https://github.com/Sanofi-IADC/whispr/compare/v1.4.1...v1.4.2) (2020-07-31)


### Bug Fixes

* **file-upload:** fixed file-upload for GQL-Requests ([b65cb15](https://github.com/Sanofi-IADC/whispr/commit/b65cb15cb4d1e87f918644b285da7c5f10a1abab))

## [1.4.1](https://github.com/Sanofi-IADC/whispr/compare/v1.4.0...v1.4.1) (2020-07-27)


### Bug Fixes

* **dependency maintenance:** update dependency mongoose to v5.9.25 ([092fd0b](https://github.com/Sanofi-IADC/whispr/commit/092fd0b019a8dbf72a2ac7fbd43bfea3b54f8931))

# [1.4.0](https://github.com/Sanofi-IADC/whispr/compare/v1.3.9...v1.4.0) (2020-07-27)


### Features

* added simple logging for webhook ([3247198](https://github.com/Sanofi-IADC/whispr/commit/32471987459e7755f5b8a1d3c3bc5c875c0bdb2e))

## [1.3.9](https://github.com/Sanofi-IADC/whispr/compare/v1.3.8...v1.3.9) (2020-07-27)


### Bug Fixes

* **dependency maintenance:** update dependency graphql-tools to v6.0.15 ([83cfa86](https://github.com/Sanofi-IADC/whispr/commit/83cfa864c2ebff6e83671f8efecf81bbeb03baf9))

## [1.3.8](https://github.com/Sanofi-IADC/whispr/compare/v1.3.7...v1.3.8) (2020-07-20)


### Bug Fixes

* **dependency maintenance:** update dependency graphql-tools to v6.0.14 ([ce2d6e8](https://github.com/Sanofi-IADC/whispr/commit/ce2d6e8146dc42bf39c7c47a6e51156cfe30609f))

## [1.3.7](https://github.com/Sanofi-IADC/whispr/compare/v1.3.6...v1.3.7) (2020-07-20)


### Bug Fixes

* **dependency maintenance:** update dependency apollo-server-fastify to v2.15.1 ([04c134c](https://github.com/Sanofi-IADC/whispr/commit/04c134c7041f650c6f71db1fe230445c953da381))

## [1.3.6](https://github.com/Sanofi-IADC/whispr/compare/v1.3.5...v1.3.6) (2020-07-19)


### Bug Fixes

* **dependency maintenance:** update dependency lodash to v4.17.19 [security] ([ce5feed](https://github.com/Sanofi-IADC/whispr/commit/ce5feedbe491ad5ced92f3107f191a1a24bf1f67))

## [1.3.5](https://github.com/Sanofi-IADC/whispr/compare/v1.3.4...v1.3.5) (2020-07-13)


### Bug Fixes

* **dependency maintenance:** update dependency @nestjs/mongoose to v7.0.2 ([985a127](https://github.com/Sanofi-IADC/whispr/commit/985a127d78f2ca7c1aa1ca6cc432733d90b1e00d))

## [1.3.4](https://github.com/Sanofi-IADC/whispr/compare/v1.3.3...v1.3.4) (2020-07-13)


### Bug Fixes

* **dependency maintenance:** update dependency @apollo/gateway to v0.16.11 ([765a248](https://github.com/Sanofi-IADC/whispr/commit/765a2489d314c66cdde08d107afda795859888c0))

## [1.3.3](https://github.com/Sanofi-IADC/whispr/compare/v1.3.2...v1.3.3) (2020-07-09)


### Bug Fixes

* docDB SSL_VALIDATE option ([f7f123b](https://github.com/Sanofi-IADC/whispr/commit/f7f123baf5fcc6aa48170e5e3bc2e1d3e5561992))

## [1.3.2](https://github.com/Sanofi-IADC/whispr/compare/v1.3.1...v1.3.2) (2020-07-08)


### Bug Fixes

* **dependency maintenance:** update dependency amazon-cognito-identity-js to v4 ([0526e9a](https://github.com/Sanofi-IADC/whispr/commit/0526e9a40eb119bba668dff3d278846f0f963441))

## [1.3.1](https://github.com/Sanofi-IADC/whispr/compare/v1.3.0...v1.3.1) (2020-07-06)


### Bug Fixes

* **dependency maintenance:** pin dependencies ([0751ddd](https://github.com/Sanofi-IADC/whispr/commit/0751ddd770ce01915c832b9ba9a735c4caa8b501))

# [1.3.0](https://github.com/Sanofi-IADC/whispr/compare/v1.2.0...v1.3.0) (2020-07-03)


### Features

* **taggroup-whisp:** enable validation pipe for whisp and tagGroup ([11e0d3f](https://github.com/Sanofi-IADC/whispr/commit/11e0d3f82b2be278bb2c6e5f30eea0faacdc2168))

# [1.2.0](https://github.com/Sanofi-IADC/whispr/compare/v1.1.0...v1.2.0) (2020-07-03)


### Features

* **plugin:** add plugin system ([e58703f](https://github.com/Sanofi-IADC/whispr/commit/e58703fbfec8fb80cc888d93a156d4cfcd960acc))

# [1.1.0](https://github.com/Sanofi-IADC/whispr/compare/v1.0.0...v1.1.0) (2020-07-01)


### Features

* **event:** Add packages ([e94f6e1](https://github.com/Sanofi-IADC/whispr/commit/e94f6e11d039f58052b90b42794336ea9063a749))
* **event-webhook:** Add event and webhook module ([c88c322](https://github.com/Sanofi-IADC/whispr/commit/c88c322228c8926efc07a8ed8aa5dbe25e490b01))
* **whisp:** make delete whisp function return boolean ([2a99daf](https://github.com/Sanofi-IADC/whispr/commit/2a99daf1cf1829c3aed823c98120590c4a2b0619))
* **whisp:** update whisp interface ([36ae346](https://github.com/Sanofi-IADC/whispr/commit/36ae346b1965984857afb5d1976b41b4c92e0d8b))

# 1.0.0 (2020-06-30)


### Bug Fixes

* **deps:** update dependency aws-sdk to v2.706.0 ([f6d8496](https://github.com/Sanofi-IADC/whispr/commit/f6d849605b2293cd6a0e45e465be4c22823ca1d4))
* **deps:** update dependency aws-sdk to v2.707.0 ([bfbd940](https://github.com/Sanofi-IADC/whispr/commit/bfbd94030f7b77f8be80e6a5679eed59ec966398))
* **deps:** update dependency graphql to v15.2.0 ([7010fd1](https://github.com/Sanofi-IADC/whispr/commit/7010fd1bb1076e8d2f66be2cf7bd229c1535bbdd))
* **deps:** update dependency graphql-tools to v6.0.11 ([a714876](https://github.com/Sanofi-IADC/whispr/commit/a714876b716f076487c5160a44c8cd7093b2e407))
* **renovate:** force renovate semantic commits ([#95](https://github.com/Sanofi-IADC/whispr/issues/95)) ([8a8e351](https://github.com/Sanofi-IADC/whispr/commit/8a8e351431cc7a2a7a605c27ad70152f3e826c01))


### Features

* perform release 1 and update badges ([241838d](https://github.com/Sanofi-IADC/whispr/commit/241838d0b9573b791b0f0e2ea038245020efd5fa))
* set token for release 1.0.0 ([fe111b9](https://github.com/Sanofi-IADC/whispr/commit/fe111b9bc5e47002667f5ddb9d96c6695d931adf))
