# clitor-is-protocol.github.io

## KevaCoin

### Specification

* create separated namespace
* append file basename or md5file as `_KEVA_NS_` value
* append protocol version as `_CLITOR_IS_` value
* encode file content to base64 string
* split encoded string to `3072` byte pieces
* save pieces as indexed record values

### Software

* [kevacoin-cli](https://github.com/clitor-is-protocol/kevacoin-cli) - CLI tools for KevaCoin blockchain
* [kevacoin-php](https://github.com/clitor-is-protocol/kevacoin-php) - PHP 8 / Composer library