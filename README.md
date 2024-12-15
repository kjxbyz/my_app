# my_app

Related issue: https://github.com/rustwasm/wasm-pack/issues/1456

1. `git clone https://github.com/kjxbyz/my_app && cd my_app`
2. `wasm-pack build -t no-modules -d ./web/pkg --no-typescript --out-name rust_lib_my_app rust -- -Z build-std=std,panic_abort`
