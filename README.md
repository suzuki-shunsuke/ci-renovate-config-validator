# ci-renovate-config-validator

[![GitHub last commit](https://img.shields.io/github/last-commit/suzuki-shunsuke/ci-renovate-config-validator.svg)](https://github.com/suzuki-shunsuke/ci-renovate-config-validator)
[![License](http://img.shields.io/badge/license-mit-blue.svg?style=flat-square)](https://raw.githubusercontent.com/suzuki-shunsuke/ci-renovate-config-validator/master/LICENSE)

script to validate Renovate configuration file with renovate-config-validator

## Requirement

* environment variables of [ci-info](https://github.com/suzuki-shunsuke/ci-info)
  * CI_INFO_TEMP_DIR/pr_all_filenames.txt
* renovate-config-validator or npm
  * if renovate-config-validator isn't installed, it's installed with npm

## How to use

```console
$ curl -sSfL https://raw.githubusercontent.com/suzuki-shunsuke/ci-renovate-config-validator/v0.1.0-0/ci-renovate-config-validator | sh
```

## LICENSE

[MIT](LICENSE)
