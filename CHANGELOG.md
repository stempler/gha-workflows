## 1.0.0 (2024-03-14)


### Features

* add first version of Play framework workflows ([ae3be41](https://github.com/stempler/gha-workflows/commit/ae3be414b473969c1727ea48b619bfc449c0a333))
* add Gradle test results artifact ([fa34fd2](https://github.com/stempler/gha-workflows/commit/fa34fd2f48d957c435357c3a1363f79d391c7779))
* add shared workflows based on Dockerfiles ([836aae8](https://github.com/stempler/gha-workflows/commit/836aae8ee064bcf44ffbce2de51f7130010ce236))
* allow specifying custom Gradle tasks for service check ([161be51](https://github.com/stempler/gha-workflows/commit/161be51606b0bc1fea5efaf366dde3ff86106e82))
* configure failure on test failure for Gradle library ([0aeec1a](https://github.com/stempler/gha-workflows/commit/0aeec1a62f9edc5b193e521a77df60cef67d57f7))
* extend configuration of Gradle library workflow ([5f535f6](https://github.com/stempler/gha-workflows/commit/5f535f66c4bd31fdbe5cbf927aead441e84888ee))
* first version of shared workflow for Gradle service check ([96eaddf](https://github.com/stempler/gha-workflows/commit/96eaddf95b1a0f432c299c3ff298aded0805f81e))
* first version of shared workflow for publishing Gradle services ([9a274e3](https://github.com/stempler/gha-workflows/commit/9a274e3b9d1c1f172449e8b221d99332ca1e72eb))
* first version of shared workflows for Gradle library build ([babdc85](https://github.com/stempler/gha-workflows/commit/babdc85c68aa60fbcc4110468933dcbbf95d9b94))
* first version of workflow to scan images ([d35a70c](https://github.com/stempler/gha-workflows/commit/d35a70c8df97d80a0f32e93e2c7296485bcf985f))
* first versions of workflows for sbt libraries ([c01a8d2](https://github.com/stempler/gha-workflows/commit/c01a8d2d36a2ecee3641a35879545564550050f4))
* generate lockfiles for Gradle subprojects ([b841f71](https://github.com/stempler/gha-workflows/commit/b841f7180f42cb9fcee30a45d550c2dcb55ac706))
* make context for Docker build configurable ([85ac57e](https://github.com/stempler/gha-workflows/commit/85ac57e239e40b0ea7399f689aa59a49a9d5c44f))
* make DockerHub login optional ([2d2e709](https://github.com/stempler/gha-workflows/commit/2d2e7091e407a675e81f8e83c69c77b40a941d3a))
* pass Docker Hub credentials to Gradle library build ([2afb57a](https://github.com/stempler/gha-workflows/commit/2afb57af641186a99cd4d65541daf225d2886cd8))
* support artifact upload for Gradle library build ([5547d18](https://github.com/stempler/gha-workflows/commit/5547d18e4c4a20ccf7b93a48d044fdf33a55c287))
* support custom java options for Gradle library builds ([e836e00](https://github.com/stempler/gha-workflows/commit/e836e00f801902d96bc07219b93d60e1a91abed8))
* support custom pre-build command in play workflows ([f265b2c](https://github.com/stempler/gha-workflows/commit/f265b2c33a00307416be2e70191580306b745b63))
* support gradle library workflow w/o build ([042fc17](https://github.com/stempler/gha-workflows/commit/042fc173c7cb12e61b977f24f12180295cb05e4e))
* support multi module and custom tasks ([37c8f83](https://github.com/stempler/gha-workflows/commit/37c8f8320ff3b8a4858b86f841636a7d677d245b))
* support multi module builds for services ([a867ddb](https://github.com/stempler/gha-workflows/commit/a867ddbb5c5922133bffc7068842ecfbf19f6cfe))
* support running custom command before library build ([fd6370e](https://github.com/stempler/gha-workflows/commit/fd6370e8acc38b1fd7b428e39fbadab2fabc6673))
* support scanning multiple images ([46af370](https://github.com/stempler/gha-workflows/commit/46af37020d5e9b0ce024ce30a27edfde905b60b7))
* support setting for expecting tests in gradle service check ([17c68ad](https://github.com/stempler/gha-workflows/commit/17c68ad5d19381cf35deff1855424baeb152529f))
* support setting for expecting tests in gradle service publishing ([769b69a](https://github.com/stempler/gha-workflows/commit/769b69aa83a0e6003625cdab7588d86cc6c8967d))
* suppport passing custom environment variables ([ee341f2](https://github.com/stempler/gha-workflows/commit/ee341f2b8f03e8d7d70c94d96a7e4e6372ffe138))


### Bug Fixes

* add missing input types ([d98ffce](https://github.com/stempler/gha-workflows/commit/d98ffce2e5f501c07162a0c36cfafe6aaa842759))
* add missing secret definitions ([ebefa30](https://github.com/stempler/gha-workflows/commit/ebefa305759ee523eee89423fa51a68b4539ea07))
* attempt to fix test reports path ([de659fd](https://github.com/stempler/gha-workflows/commit/de659fdbf38e35e71ef3e1459fb2ccb54c4bef3d))
* fix configuration for pushing image ([9b93e03](https://github.com/stempler/gha-workflows/commit/9b93e030fc1b4a339cacd8be2ff0d8dd5b076677))
* fix reference to wrong base workflow ([d110e2f](https://github.com/stempler/gha-workflows/commit/d110e2ff0307f9718d2e122075de9320018bb831))
* fix test report locations for Gradle service workflows ([0c044be](https://github.com/stempler/gha-workflows/commit/0c044be912a48f84d668e193f7c2cb67a1c39fe0))
* registry credentials should only be required for pushing ([2b27cd2](https://github.com/stempler/gha-workflows/commit/2b27cd27af5d08ebf4ec5dd7733229711f948566))
* trivy scan of Gradle lockfile only supported for fs scan ([d49ffb4](https://github.com/stempler/gha-workflows/commit/d49ffb40fc69c17e59d47764cdf3ff11c14e0adf))
