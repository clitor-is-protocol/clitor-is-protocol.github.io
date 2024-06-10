# clitor-is-protocol

keep large objects in small blocks

## KevaCoin

### Specification

* create namespace
* append filename with extension as `_KEVA_NS_` value
* append encoder info as `_CLITOR_IS_` value
* encode file content to base64 string
* split encoded string to `3072` byte pieces
* save pieces as namespace records where `key` is part index and `value` is part data

### Software

* [kevacoin-cli](https://github.com/clitor-is-protocol/kevacoin-cli) - CLI tools for KevaCoin blockchain
* [kevacoin-php](https://github.com/clitor-is-protocol/kevacoin-php) - PHP 8 / Composer library