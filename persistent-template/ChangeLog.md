## 2.1.8.1

* fix a bad Eq instance /= definition for Key when mpsGenetric=True

## 2.1.7

* Support for GHC 8 [#556](https://github.com/yesodweb/persistent/issues/556)

## 2.1.6

* aeson 0.11
* transformers 0.5

## 2.1.3.3

By default explicitly use Int64 for foreign key references.
This avoids confusion on a 32 bit system.

## 2.1.3.1

Support foreign key references to composite primary keys

## 2.1.0.1

Support for monad-control 1.0
