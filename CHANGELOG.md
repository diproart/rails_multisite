## 2.0.4 - 12-02-2018

  * Fix bug where calling `RailsMultisite::ConnectionManagement.current_hostname`
    with a `default` connection would throw an undefined method error.

## 2.0.3 - yanked

  * Base `RailsMultisite::ConnectionManagement.current_hostname` on `@host_spec_cache`.

## 2.0.2

  * with_connection should return result of block

## 1.1.2

  * raise error if RAILS_DB is specified yet missing

## 1.1.1

  * allows db_lookup callback for middleware, this allows you to whitelist paths in multisite

## 1.0.6

  * Revert deprecation fix because it can break multisite in subtle ways.
  * Allow `db` to be passed as a symbol to `RailsMultisite::ConnectionManagement.establish_connection`.

## 1.0.5

  * Fix deprecation warnings.
