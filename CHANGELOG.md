# Change Log

## [1.2.3](https://github.com/grisp/rebar3_grisp/tree/1.2.3) (2018-08-07)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.2.2...1.2.3)

**Implemented enhancements:**

- Print a proper error for missing template keys [\#37](https://github.com/grisp/rebar3_grisp/issues/37)

**Fixed bugs:**

- Default GRiSP sources overwrite custom sources [\#38](https://github.com/grisp/rebar3_grisp/issues/38)

## [1.2.2](https://github.com/grisp/rebar3_grisp/tree/1.2.2) (2018-08-01)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.2.1...1.2.2)

**Fixed bugs:**

- Templates do not work when deploying [\#36](https://github.com/grisp/rebar3_grisp/issues/36)

## [1.2.1](https://github.com/grisp/rebar3_grisp/tree/1.2.1) (2018-08-01)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.2.0...1.2.1)

**Fixed bugs:**

- Templates do not work when building [\#35](https://github.com/grisp/rebar3_grisp/issues/35)

## [1.2.0](https://github.com/grisp/rebar3_grisp/tree/1.2.0) (2018-07-31)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.1.5...1.2.0)

**Implemented enhancements:**

- Re-introduce GRISP\_TOOLCHAIN environment variable [\#34](https://github.com/grisp/rebar3_grisp/pull/34) ([eproxus](https://github.com/eproxus))
- Add version task that prints version number [\#33](https://github.com/grisp/rebar3_grisp/pull/33) ([eproxus](https://github.com/eproxus))
- Include environment variables in templates [\#32](https://github.com/grisp/rebar3_grisp/pull/32) ([eproxus](https://github.com/eproxus))

## [1.1.5](https://github.com/grisp/rebar3_grisp/tree/1.1.5) (2018-06-25)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.1.4...1.1.5)

**Fixed bugs:**

- Weird directory with name " created during deploy [\#30](https://github.com/grisp/rebar3_grisp/issues/30)

## [1.1.4](https://github.com/grisp/rebar3_grisp/tree/1.1.4) (2018-06-21)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.1.3...1.1.4)

## [1.1.3](https://github.com/grisp/rebar3_grisp/tree/1.1.3) (2018-06-21)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.1.2...1.1.3)

## [1.1.2](https://github.com/grisp/rebar3_grisp/tree/1.1.2) (2018-06-06)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.1.1...1.1.2)

**Merged pull requests:**

- deploy: added support for whitespaces in source and deployment directories [\#28](https://github.com/grisp/rebar3_grisp/pull/28) ([lwehmeier](https://github.com/lwehmeier))
- Remove references to old versions [\#27](https://github.com/grisp/rebar3_grisp/pull/27) ([nextl00p](https://github.com/nextl00p))
- consistency of the instructions for release name [\#26](https://github.com/grisp/rebar3_grisp/pull/26) ([CrowdHailer](https://github.com/CrowdHailer))
- Add support for OTP 21.0-rc1 [\#25](https://github.com/grisp/rebar3_grisp/pull/25) ([sylane](https://github.com/sylane))

## [1.1.1](https://github.com/grisp/rebar3_grisp/tree/1.1.1) (2018-05-25)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.1.0...1.1.1)

**Fixed bugs:**

- Freshly generated grispapp fails to deploy the first time its run [\#23](https://github.com/grisp/rebar3_grisp/issues/23)

## [1.1.0](https://github.com/grisp/rebar3_grisp/tree/1.1.0) (2018-05-24)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.0.1...1.1.0)

**Closed issues:**

- Start Erlang runtime when source dependencies are included [\#21](https://github.com/grisp/rebar3_grisp/issues/21)
- Wrong warning about Erlang version mismatch [\#14](https://github.com/grisp/rebar3_grisp/issues/14)
- Make deploy destination available via command-line flag [\#5](https://github.com/grisp/rebar3_grisp/issues/5)
- Confusing error message, when no toolchain root is set [\#4](https://github.com/grisp/rebar3_grisp/issues/4)

**Merged pull requests:**

- Prebuilt toolchain [\#20](https://github.com/grisp/rebar3_grisp/pull/20) ([nextl00p](https://github.com/nextl00p))
- Add version to OTP xcomp files [\#18](https://github.com/grisp/rebar3_grisp/pull/18) ([sylane](https://github.com/sylane))
- Allow deploy without grisp runtime and fix version warning [\#17](https://github.com/grisp/rebar3_grisp/pull/17) ([sylane](https://github.com/sylane))
- Refactor build configuration [\#16](https://github.com/grisp/rebar3_grisp/pull/16) ([sylane](https://github.com/sylane))

## [1.0.1](https://github.com/grisp/rebar3_grisp/tree/1.0.1) (2017-12-20)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/1.0.0...1.0.1)

## [1.0.0](https://github.com/grisp/rebar3_grisp/tree/1.0.0) (2017-12-19)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/0.1.1...1.0.0)

**Fixed bugs:**

- With default profile section ERTS does not get included [\#8](https://github.com/grisp/rebar3_grisp/issues/8)

**Closed issues:**

- Document rebar3 grisp build [\#3](https://github.com/grisp/rebar3_grisp/issues/3)

**Merged pull requests:**

- Make SMP the default and add support for OTP 20.2 [\#13](https://github.com/grisp/rebar3_grisp/pull/13) ([sylane](https://github.com/sylane))
- Make OTP version branch customizable [\#12](https://github.com/grisp/rebar3_grisp/pull/12) ([eproxus](https://github.com/eproxus))

## [0.1.1](https://github.com/grisp/rebar3_grisp/tree/0.1.1) (2017-12-05)
[Full Changelog](https://github.com/grisp/rebar3_grisp/compare/0.1.0...0.1.1)

## [0.1.0](https://github.com/grisp/rebar3_grisp/tree/0.1.0) (2017-10-20)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*