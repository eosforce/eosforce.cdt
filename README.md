# EOSFORCE.CDT (Contract Development Toolkit)

EOSFORCE.CDT is a toolchain for WebAssembly (WASM) and set of tools to facilitate contract writing for the EOSForce.

### Guided Installation (Building from Scratch)
```sh
$ git clone --recursive https://github.com/eosforce/eosforce.cdt
$ cd eosforce.cdt
$ ./build.sh
$ sudo ./install.sh
```

### Installed Tools

* diff name from eosio

---
* eosforce-cpp
* eosforce-cc
* eosforce-ld
* eosforce-init
* eosforce-abigen
* eosforce-abidiff
* eosforce-pp (post processing pass for WASM, automatically runs with eosforce-cpp and eosforce-ld)
* eosforce-wasm2wast
* eosforce-wast2wasm
* eosforce-ranlib
* eosforce-ar
* eosforce-objdump
* eosforce-readelf

## Contributing

[Contributing Guide](./CONTRIBUTING.md)

[Code of Conduct](./CONTRIBUTING.md#conduct)

## License

[MIT](./LICENSE)

## Important

See [LICENSE](./LICENSE) for copyright and license terms.

All repositories and other materials are provided subject to the terms of this [IMPORTANT](./IMPORTANT.md) notice and you must familiarize yourself with its terms.  The notice contains important information, limitations and restrictions relating to our software, publications, trademarks, third-party resources, and forward-looking statements.  By accessing any of our repositories and other materials, you accept and agree to the terms of the notice.
