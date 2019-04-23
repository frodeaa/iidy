### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).

#### [v1.7.0](https://github.com/unbounce/iidy/compare/v1.6.6-rc4...v1.7.0)

> 14 March 2019

- SEC-1441: Adding SonarCloud SAST [`#172`](https://github.com/unbounce/iidy/pull/172)
- bump deps as far as we can go (and tweak a few types to fit) [`#171`](https://github.com/unbounce/iidy/pull/171)
- Use laundry as CloudFormation template linter [`#159`](https://github.com/unbounce/iidy/pull/159)
- Show warning when unknown stack-args properties are added [`#152`](https://github.com/unbounce/iidy/pull/152)
- Refactor Visitor functions to allow extending it's behaviour [`#150`](https://github.com/unbounce/iidy/pull/150)
- Ignore unused imports when running  template approval commands [`#151`](https://github.com/unbounce/iidy/pull/151)
- fix bug in s3 url parsing due to inconsistent regexes [`#164`](https://github.com/unbounce/iidy/issues/164)
- Don't filter out vars required by resolved vars [`#167`](https://github.com/unbounce/iidy/issues/167)
- Preserve stackargs array values [`#155`](https://github.com/unbounce/iidy/issues/155)
- Show warning for invalid argsfile properties [`#131`](https://github.com/unbounce/iidy/issues/131)
- fix #142: display region / profile in suggested cli commands [`#142`](https://github.com/unbounce/iidy/issues/142)
- continue refactoring module structure [`92de8b6`](https://github.com/unbounce/iidy/commit/92de8b6c35ddb63c81e7b1240be922539febf2f8)
- update deps and tests [`4588e09`](https://github.com/unbounce/iidy/commit/4588e09c9cf4aa654840749d1085b75aea4ab413)
- Use https://github.com/jpb/laundry [`d842b59`](https://github.com/unbounce/iidy/commit/d842b595a9971f5d5749b5814b4767c25641995d)

#### [v1.6.6-rc4](https://github.com/unbounce/iidy/compare/v1.6.6-rc3...v1.6.6-rc4)

> 24 September 2018

- Add ability to render a directory of templates [`#138`](https://github.com/unbounce/iidy/pull/138)

#### [v1.6.6-rc3](https://github.com/unbounce/iidy/compare/v1.6.6-rc2...v1.6.6-rc3)

> 24 September 2018

- Cache assumed role credentials on disk [`#137`](https://github.com/unbounce/iidy/pull/137)
- Prevent configureAWS from being called multiple times for create-stack [`#136`](https://github.com/unbounce/iidy/pull/136)
- [WIP] Support rendering multiple documents in one file [`#133`](https://github.com/unbounce/iidy/pull/133)
- Prevent configureAWS from being called multiple times for create-stack [`#134`](https://github.com/unbounce/iidy/issues/134)
- Support rendering multiple documents in one file [`7eacc3e`](https://github.com/unbounce/iidy/commit/7eacc3e0a7b44b1e7b9866f93c68f833f71a588b)

#### [v1.6.6-rc2](https://github.com/unbounce/iidy/compare/v1.6.6-rc1...v1.6.6-rc2)

> 22 August 2018

- Allow rendering from STDIN [`#130`](https://github.com/unbounce/iidy/pull/130)
- Fix non-octal numeric strings in the middle of string [`#126`](https://github.com/unbounce/iidy/issues/126)
- Allow rendering from STDIN [`#127`](https://github.com/unbounce/iidy/issues/127)
- Upgrade to latest official aws-sdk [`cb38ffe`](https://github.com/unbounce/iidy/commit/cb38ffebd07601d7a8b035459164acf3af6cdbaf)
- update readme for new release [`62470ed`](https://github.com/unbounce/iidy/commit/62470eda8fdb269e220aeaaf7f3085636e2fc022)
- disable the ora spinner in terms that don't support it [`b00f35e`](https://github.com/unbounce/iidy/commit/b00f35e8b70848232843a2856d7bd4422cd71b2d)

#### [v1.6.6-rc1](https://github.com/unbounce/iidy/compare/v1.6.4...v1.6.6-rc1)

> 12 July 2018

- refactor usage of ora spinner - extract to module [`#116`](https://github.com/unbounce/iidy/pull/116)
- Improve stack-args:CommandsBefore [`#114`](https://github.com/unbounce/iidy/pull/114)
- Parameter change approval [`#104`](https://github.com/unbounce/iidy/pull/104)
- Rename RoleARN -> ServiceRoleARN in docs [`#97`](https://github.com/unbounce/iidy/pull/97)
- Visit concat elements before flattening [`#94`](https://github.com/unbounce/iidy/pull/94)
- Supporting new region: Paris eu-west-3 [`#95`](https://github.com/unbounce/iidy/pull/95)
- Minor spelling update 'is has' to 'has' [`#89`](https://github.com/unbounce/iidy/pull/89)
- add create-or-update command. Fixes #55 [`#55`](https://github.com/unbounce/iidy/issues/55)
- Visit concat elements before flattening [`#93`](https://github.com/unbounce/iidy/issues/93)
- add `--watch` to `create-changeset`. Fixes #16 [`#16`](https://github.com/unbounce/iidy/issues/16)
- Add iidy.environment and iidy.region in Template: render:... [`#82`](https://github.com/unbounce/iidy/issues/82)
- Show helpful error message on create if temlpate needs approval [`#71`](https://github.com/unbounce/iidy/issues/71)
- update most outdate deps and refactor code & types to match [`b5d1ac7`](https://github.com/unbounce/iidy/commit/b5d1ac72b0370e5b0692915310b505dce07e9e43)
- bump dependencies [`eb7ca78`](https://github.com/unbounce/iidy/commit/eb7ca78117a56d5d6dc227fbf0ec7b9e250f2615)
- bump deps [`19acd4a`](https://github.com/unbounce/iidy/commit/19acd4aa5abde34e1c2e05c0f1b44117f59078dc)

#### [v1.6.4](https://github.com/unbounce/iidy/compare/v1.6.2...v1.6.4)

> 14 February 2018

- Allow 'override' region to be specified in cfn imports [`#78`](https://github.com/unbounce/iidy/pull/78)
- fix #73 - allow !GetAtt in pre-processed templates to accept arrays [`#77`](https://github.com/unbounce/iidy/pull/77)
- fix the !$expand implementation to match CFN resource templates [`#61`](https://github.com/unbounce/iidy/pull/61)
- fix #68 - region initialization out of order on create/update stack [`#70`](https://github.com/unbounce/iidy/pull/70)
- fix #73 - allow !GetAtt in pre-processed templates to accept arrays [`#73`](https://github.com/unbounce/iidy/issues/73)
- fix #68 - region initialization out of order on create/update stack [`#68`](https://github.com/unbounce/iidy/issues/68)
- Don't consider an empty changeset an error [`#66`](https://github.com/unbounce/iidy/issues/66)
- Fix property visiblities [`0f031cc`](https://github.com/unbounce/iidy/commit/0f031cc2a6f43f84f932750aeebcc4c335c480c1)
- workaround CloudFormation bug re non-octal strings with leading 0s [`eeab864`](https://github.com/unbounce/iidy/commit/eeab864a755d60a8d15ca59dd5339ef2d004790c)
- add iidy.region and iidy.environment to `iidy render` for all files [`02602d0`](https://github.com/unbounce/iidy/commit/02602d0565a3a4ecb31727abdc06d8904cd28108)

#### [v1.6.2](https://github.com/unbounce/iidy/compare/v1.6.1...v1.6.2)

> 29 January 2018

- Use consistent, identifiable status code when command is cancelled by user [`#59`](https://github.com/unbounce/iidy/pull/59)
- beef up the pre-processor unit tests [`#57`](https://github.com/unbounce/iidy/pull/57)
- Handle split delimiter at end of string better [`#56`](https://github.com/unbounce/iidy/pull/56)
- improve the detection of stack-args.yaml in `iidy render` [`#58`](https://github.com/unbounce/iidy/pull/58)
- update docs in the README [`#53`](https://github.com/unbounce/iidy/pull/53)
- prevent js-yaml.dump from line-wrapping strings [`#51`](https://github.com/unbounce/iidy/pull/51)
- Add $split function [`#49`](https://github.com/unbounce/iidy/pull/49)
- Recursively $merge [`#48`](https://github.com/unbounce/iidy/pull/48)
- support arn formatted roles, refactor AWS configuration [`#32`](https://github.com/unbounce/iidy/issues/32)
- add option to sort map keys in convert-stack-to-iidy (default=true) [`68a2694`](https://github.com/unbounce/iidy/commit/68a2694bf1dff4f9ae3815807b7a24f28d935b3a)
- add unit tests for aws configuration [`c477eda`](https://github.com/unbounce/iidy/commit/c477eda7194fe08e494ec661d172b529b24015cd)
- fix formatting issues (tsfmt) [`ee9d818`](https://github.com/unbounce/iidy/commit/ee9d8180348b46cf51837a81e8e010c7fdca59ca)

#### [v1.6.1](https://github.com/unbounce/iidy/compare/v1.6.0...v1.6.1)

> 19 January 2018

- Release process [`47913d2`](https://github.com/unbounce/iidy/commit/47913d2f4b90ff37a3d0cdda3c5d8a13e183fd0a)
- Update package-lock in release [`f837d28`](https://github.com/unbounce/iidy/commit/f837d2892f4be23cda8ef9a6c28ef74c090ea103)
- Update changelog [`d39257d`](https://github.com/unbounce/iidy/commit/d39257db2da87b05dd02ec5da6f11b0ddf543e08)

#### [v1.6.0](https://github.com/unbounce/iidy/compare/v1.6.0-rc7...v1.6.0)

> 18 January 2018

- Ignore all of lib [`f81113e`](https://github.com/unbounce/iidy/commit/f81113e2cb9d7cf362e5da4b01eb2ae6f09a71e9)
- Update package lock [`973c39a`](https://github.com/unbounce/iidy/commit/973c39a276e0451ea53419e820d5f72adc6cb433)

#### [v1.6.0-rc7](https://github.com/unbounce/iidy/compare/v1.6.0-rc6...v1.6.0-rc7)

> 17 January 2018

- Create approve templates [`#43`](https://github.com/unbounce/iidy/pull/43)
- Replace template URL when ApprovedTemplateLocation is in use [`#45`](https://github.com/unbounce/iidy/pull/45)
- Add support for auto-signing S3 HTTP template URLs [`#39`](https://github.com/unbounce/iidy/pull/39)
- add initial .travis.yml - fix #34 [`#38`](https://github.com/unbounce/iidy/pull/38)
- preprocess the second argument to !Sub. Fixes #20. [`#20`](https://github.com/unbounce/iidy/issues/20)
- refactor: mv src/index.ts to src/preprocess/ and update imports [`a98f6d0`](https://github.com/unbounce/iidy/commit/a98f6d0acd1ef3d6b5be8d0bf24642278f2b2264)
- Template approval commands [`16bf034`](https://github.com/unbounce/iidy/commit/16bf034ae99d52aa8703b897f321bef649f26b93)
- Use approved template for create/update stack [`835f14e`](https://github.com/unbounce/iidy/commit/835f14e0b973927874a2b3fd09f3b2c0b6debf53)

#### [v1.6.0-rc6](https://github.com/unbounce/iidy/compare/v1.6.0-rc5...v1.6.0-rc6)

> 11 December 2017

- add !$merge, !$mergeMap, !$mapValues, !$groupBy [`#29`](https://github.com/unbounce/iidy/pull/29)
- add !$if, !$not, !$eq [`#28`](https://github.com/unbounce/iidy/pull/28)
- add `filter:` argument to !$map (!$concatMap, !$mergeMap, etc.) [`#27`](https://github.com/unbounce/iidy/pull/27)
- Smarter !$ var lookups [`#26`](https://github.com/unbounce/iidy/pull/26)
- support !$ or '{{}}' inside custom cfn !tags that `iidy` rewrites [`#25`](https://github.com/unbounce/iidy/pull/25)
- allow `$merge` entries in cfn `Resources:` [`#24`](https://github.com/unbounce/iidy/pull/24)
- String case handlebars helpers [`#23`](https://github.com/unbounce/iidy/pull/23)
- allow key names in maps to contain '{{variables}}' [`#22`](https://github.com/unbounce/iidy/pull/22)
- add cfn-template yaml with overwrite options [`27436e7`](https://github.com/unbounce/iidy/commit/27436e7442bec7ed0b917c46a3b9ae3c38e4026e)
- initialize stack args file [`19e6f51`](https://github.com/unbounce/iidy/commit/19e6f5125f710d53d08dbac000053a6b79689460)
- check if file already exists [`09792a5`](https://github.com/unbounce/iidy/commit/09792a5b0589b3d82b0fbb6ad7b178313bef8d4a)

#### [v1.6.0-rc5](https://github.com/unbounce/iidy/compare/v1.6.0-rc4...v1.6.0-rc5)

> 22 November 2017

- add experimental support for using the aws cli sts role cache [`#14`](https://github.com/unbounce/iidy/issues/14)
- fix #17: when AWS_SDK_LOAD_CONFIG is set and ~/.aws doesn't exist BOOM [`#17`](https://github.com/unbounce/iidy/issues/17)

#### [v1.6.0-rc4](https://github.com/unbounce/iidy/compare/v1.6.0-rc3...v1.6.0-rc4)

> 20 November 2017

- fix #15 unhandle promise rejection for create-changeset on new stack [`#15`](https://github.com/unbounce/iidy/issues/15)
- add support for `cfn:export:exportName` in $imports [`c78cbfa`](https://github.com/unbounce/iidy/commit/c78cbfa9687ce46208fb02a98ebd14fb23c9b142)
- bump aws-sdk version and iidy version to v1.6.0-rc4 [`d6ef203`](https://github.com/unbounce/iidy/commit/d6ef203864fcbca1dcb85525d5c501b6937564b6)

#### [v1.6.0-rc3](https://github.com/unbounce/iidy/compare/v1.6.0-rc2...v1.6.0-rc3)

> 8 November 2017

- add initial implemenation of `iidy convert-stack-to-iidy` [`3635411`](https://github.com/unbounce/iidy/commit/363541190ec05b4b6a25f893834196015c3166ba)
- add changesets demo [`9a1a671`](https://github.com/unbounce/iidy/commit/9a1a671a4d4fd1a038eed28925e649b07ea6d89a)
- add --format (yaml|json) and --query (jmespath) to `iidy render` [`c6eca92`](https://github.com/unbounce/iidy/commit/c6eca92945fcf68f8f1081164d4619881650451c)

#### [v1.6.0-rc2](https://github.com/unbounce/iidy/compare/v1.6.0-rc1...v1.6.0-rc2)

> 7 November 2017

- add `--diff` option to `update-stack --changeset` [`78a3857`](https://github.com/unbounce/iidy/commit/78a385718aba5d61a09b79dc1ee2444d74918337)
- further makefile tweaks for release building [`c36bcb2`](https://github.com/unbounce/iidy/commit/c36bcb26ec3a642f73432793d02309d9f401f4be)
- update README for new release package [`de86fda`](https://github.com/unbounce/iidy/commit/de86fda4a3ca892480080ea4cdd8d7a4b7e09ad6)

#### [v1.6.0-rc1](https://github.com/unbounce/iidy/compare/v1.5.0...v1.6.0-rc1)

> 5 November 2017

- Adding Homebrew installation method for MacOS [`#7`](https://github.com/unbounce/iidy/pull/7)
- add --inactivity-timeout on watch-stack. Fixes #4 [`#4`](https://github.com/unbounce/iidy/issues/4)
- update dependencies [`c968d4c`](https://github.com/unbounce/iidy/commit/c968d4c8587e03950cc0e6d5851dd9014364e5d3)
- tsfmt cosmetic cleanup [`d9af01c`](https://github.com/unbounce/iidy/commit/d9af01c081d99b05f709a451f7fa1789d4e4f25e)
- version bump all dependencies (including typescript to 2.6) [`d83d0d5`](https://github.com/unbounce/iidy/commit/d83d0d5b34dd4780e43c9e4a704bb239b514b9fa)

#### [v1.5.0](https://github.com/unbounce/iidy/compare/v1.4.0...v1.5.0)

> 1 September 2017

- update deps; flesh out package.json [`a1e9530`](https://github.com/unbounce/iidy/commit/a1e95302a9cf300f482ac9585f3cb2a4e1bdf83a)
- add --debug flag and some refactoring related to that [`1860661`](https://github.com/unbounce/iidy/commit/18606613d69175ac86a1da39b10a03ac1f0f13f0)
- update help command output in readme [`ccadc97`](https://github.com/unbounce/iidy/commit/ccadc97bd4fef0aa9dc604ef8abff7e689ff5175)

#### [v1.4.0](https://github.com/unbounce/iidy/compare/v1.3.3...v1.4.0)

> 24 August 2017

- add package-lock.json for npm 5 [`32cd698`](https://github.com/unbounce/iidy/commit/32cd6983790299970437969873b55574f9e6102b)
- remove Unbounce section from the readme [`b0b7244`](https://github.com/unbounce/iidy/commit/b0b7244907716021b8f0ee4fdf33e36fa137708c)
- add get-stack-instances command [`779fb90`](https://github.com/unbounce/iidy/commit/779fb9051883518ff9a3d0460a37a978dd77cc09)

#### [v1.3.3](https://github.com/unbounce/iidy/compare/v1.3.2...v1.3.3)

> 23 August 2017

- add yarn.lock [`c61cc66`](https://github.com/unbounce/iidy/commit/c61cc66df03b5d812d8b9fb8d452d2a5514b40ce)
- guard against users accidentally omitting 'render:' on templates [`05afb58`](https://github.com/unbounce/iidy/commit/05afb58a57b68803685f7df641af66db3191e82e)
- version bump to v1.3.3 [`9451ba7`](https://github.com/unbounce/iidy/commit/9451ba71ca3bd95d1f63f0a48d2ffb7631bed037)

#### [v1.3.2](https://github.com/unbounce/iidy/compare/v1.3.1...v1.3.2)

> 15 August 2017

- refactor large index.ts module into separate files [`b72ff3d`](https://github.com/unbounce/iidy/commit/b72ff3df44d6975608d16a5519ac745f4552b954)
- general cleanup refactoring to satisfy tslint [`624b562`](https://github.com/unbounce/iidy/commit/624b56275f08be4f400685f8dd66d1a1c74924a2)
- add tslint.json [`b85a0ca`](https://github.com/unbounce/iidy/commit/b85a0ca9497b66f50431953b8e877f01285eafb5)

#### [v1.3.1](https://github.com/unbounce/iidy/compare/v1.3.0...v1.3.1)

> 11 August 2017

- improve the ansible vs iidy demo script [`d6027a2`](https://github.com/unbounce/iidy/commit/d6027a2687ff5b437b979c457c88b15c086f12db)
- add time since last event to the event polling output [`aba1461`](https://github.com/unbounce/iidy/commit/aba146171c6f5d105790934fc4c0d15a19ee28e1)
- readme update for v1.3.0 [`b34ffd2`](https://github.com/unbounce/iidy/commit/b34ffd2a4633ea8087bb7a0f531d2ffac3abce6d)

#### [v1.3.0](https://github.com/unbounce/iidy/compare/v1.2.0...v1.3.0)

> 11 August 2017

- Alpine-based Dockerfile for running iidy [`#3`](https://github.com/unbounce/iidy/pull/3)
- refactor the demo code to support faster/slower replay [`83e230b`](https://github.com/unbounce/iidy/commit/83e230ba97148de18fbad03970aa8bc350ceb168)
- tidy up the cli help output [`daafd80`](https://github.com/unbounce/iidy/commit/daafd80bd43b425211a5de895840d97780cf6f06)
- minor tidy-up refactoring [`7246291`](https://github.com/unbounce/iidy/commit/7246291e0ad604c3d74c2102dabe082baea2cfb4)

#### [v1.2.0](https://github.com/unbounce/iidy/compare/v1.1.0...v1.2.0)

> 8 August 2017

- add 'iidy demo' for running packaged demo scripts [`1391b88`](https://github.com/unbounce/iidy/commit/1391b88a501aa55a88fc57f52fef505c03d55396)
- tweak the console output coloring, alignment, wording, etc. [`1d969b8`](https://github.com/unbounce/iidy/commit/1d969b88af295ea9e198836dab624801dced6a73)
- update asciicast and demo [`1966803`](https://github.com/unbounce/iidy/commit/196680395e4ae0116bb31e3cfee37f919cc120ae)

#### [v1.1.0](https://github.com/unbounce/iidy/compare/v1.0.0...v1.1.0)

> 3 August 2017

- add flesh to the README [`3317e49`](https://github.com/unbounce/iidy/commit/3317e498aae00ba7e31d3d4025ba39a2c55aba2c)
- extend the hello-world example and turn it into a test [`4fd826c`](https://github.com/unbounce/iidy/commit/4fd826c8c06c9130f09e913fd49b920b1c7ae7a3)
- extend examples in the README [`7d994bf`](https://github.com/unbounce/iidy/commit/7d994bffccc56190185b9933d4066ad1ea646ed2)

#### v1.0.0

> 21 July 2017

- init [`cf4f1ac`](https://github.com/unbounce/iidy/commit/cf4f1ac0c3af5eeddb81ee8ef32c1319ef92ab9a)