# ci-renovate-config-validator

script to validate Renovate configuration file with renovate-config-validator

## Requirement

* environment variables of [ci-info](https://github.com/suzuki-shunsuke/ci-info)
  * CI_INFO_TEMP_DIR/pr_all_filenames.txt
* renovate-config-validator or npm
  * if renovate-config-validator isn't installed, it's installed with npm

## How to use

```console
$ curl -sSfL https://raw.githubusercontent.com/suzuki-shunsuke/ci-renovate-config-validator/blob/v0.1.0-0/ci-renovate-config-validator | sh
```

## LICENSE

[MIT](LICENSE)
