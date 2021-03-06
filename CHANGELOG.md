# Changelog

## [0.16.1](https://github.com/saltstack-formulas/iptables-formula/compare/v0.16.0...v0.16.1) (2019-10-10)


### Bug Fixes

* **init.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/iptables-formula/commit/65369c5))
* **service.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/iptables-formula/commit/49a2c62))


### Continuous Integration

* **kitchen:** change `log_level` to `debug` instead of `info` ([](https://github.com/saltstack-formulas/iptables-formula/commit/21844a9))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([](https://github.com/saltstack-formulas/iptables-formula/commit/02b5b59))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([](https://github.com/saltstack-formulas/iptables-formula/commit/79c98ed))
* **kitchen+travis:** replace EOL pre-salted images ([](https://github.com/saltstack-formulas/iptables-formula/commit/98ee968))
* **platform:** add `arch-base-latest` ([](https://github.com/saltstack-formulas/iptables-formula/commit/2ba3a7c))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([](https://github.com/saltstack-formulas/iptables-formula/commit/8d94551))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/iptables-formula/commit/4f0c67b))
* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([](https://github.com/saltstack-formulas/iptables-formula/commit/dccab80))

# [0.16.0](https://github.com/saltstack-formulas/iptables-formula/compare/v0.15.0...v0.16.0) (2019-08-10)


### Continuous Integration

* **kitchen:** add remaining platforms from `template-formula` ([0d7e08d](https://github.com/saltstack-formulas/iptables-formula/commit/0d7e08d))


### Features

* **yamllint:** include for this repo and apply rules throughout ([9721448](https://github.com/saltstack-formulas/iptables-formula/commit/9721448))

# [0.15.0](https://github.com/saltstack-formulas/iptables-formula/compare/v0.14.0...v0.15.0) (2019-06-25)


### Documentation

* fix rst formatting ([1318502](https://github.com/saltstack-formulas/iptables-formula/commit/1318502))


### Features

* allow to configure the firewall using a rules' dict ([e851e4f](https://github.com/saltstack-formulas/iptables-formula/commit/e851e4f))


### Styles

* improve empty lines management ([be3a96a](https://github.com/saltstack-formulas/iptables-formula/commit/be3a96a))


### Tests

* improve travis matrix, remove unneeded gem entry ([6861fe0](https://github.com/saltstack-formulas/iptables-formula/commit/6861fe0))

# [0.14.0](https://github.com/saltstack-formulas/iptables-formula/compare/v0.13.0...v0.14.0) (2019-06-11)


### Features

* semver-release ([32a7ba6](https://github.com/saltstack-formulas/iptables-formula/commit/32a7ba6)), closes [/github.com/saltstack-formulas/iptables-formula/pull/35#issuecomment-500583112](https://github.com//github.com/saltstack-formulas/iptables-formula/pull/35/issues/issuecomment-500583112)
