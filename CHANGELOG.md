# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](Https://conventionalcommits.org) for commit guidelines.

<!-- changelog -->

## [v0.1.1-rc.12](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.11...v0.1.1-rc.12) (2024-04-26)




### Improvements:

* better type casting logic

## [v0.1.1-rc.11](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.10...v0.1.1-rc.11) (2024-04-23)




### Bug Fixes:

* ensure tenant is properly set in aggregates

* properly pass context through when expanding calculations in aggregates

## [v0.1.1-rc.10](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.9...v0.1.1-rc.10) (2024-04-22)




### Improvements:

* optimize `contains` when used with literal strings

## [v0.1.1-rc.9](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.8...v0.1.1-rc.9) (2024-04-22)




### Bug Fixes:

* make `strpos_function` overridable (sqlite uses `instr`)

## [v0.1.1-rc.8](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.7...v0.1.1-rc.8) (2024-04-22)




### Bug Fixes:

* handle non-literal lists in string join

## [v0.1.1-rc.7](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.6...v0.1.1-rc.7) (2024-04-20)




### Bug Fixes:

* ensure that `from_many?` is properly honored

* ensure applied query gets joined

* apply related filter inside of related subquery

## [v0.1.1-rc.6](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.5...v0.1.1-rc.6) (2024-04-12)




### Improvements:

* apply aggregate filters on first join aggregates

## [v0.1.1-rc.5](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.4...v0.1.1-rc.5) (2024-04-11)




### Bug Fixes:

* don't use to_tenant

* loosen elixir requirements

### Improvements:

* automatically wrap fragments in parenthesis

* remove unnecessary parenthesis from builtin fragments

## [v0.1.1-rc.4](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.3...v0.1.1-rc.4) (2024-04-05)




### Improvements:

* loosen ash rc restriction

## [v0.1.1-rc.3](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.2...v0.1.1-rc.3) (2024-04-01)




### Bug Fixes:

* fixes for `ash_postgres`

## [v0.1.1-rc.2](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.1...v0.1.1-rc.2) (2024-04-01)




### Improvements:

* refactoring out and parameterization to support ash_sqlite

## [v0.1.1-rc.1](https://github.com/ash-project/ash_sql/compare/v0.1.1-rc.0...v0.1.1-rc.1) (2024-04-01)




### Improvements:

* remove postgres-specific copy-pasta

## [v0.1.1-rc.0](https://github.com/ash-project/ash_sql/compare/v0.1.0...v0.1.1-rc.0) (2024-04-01)




## [v0.1.0](https://github.com/ash-project/ash_sql/compare/v0.1.0...v0.1.0) (2024-04-01)




### Improvements:

* extract a bunch of things out of AshPostgres
