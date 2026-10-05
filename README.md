<!-- tyhp-readme:start -->
# tyhpdef/pestphp-pest-plugin-arch

Tyhp type definitions for `pestphp/pest-plugin-arch` `4.0.2`.

```bash
composer require --dev tyhpdef/pestphp-pest-plugin-arch:4.0.2
```

This is a metapackage. Composer also installs `tyhpdef/pestphp-pest-plugin-arch-impl` (type files).
Require **this** name, not `tyhpdef/pestphp-pest-plugin-arch-impl`.

See https://tyhplang.com.

## Maintain `pestphp/pest-plugin-arch`? Ship the types yourself

If you are a Packagist maintainer of `pestphp/pest-plugin-arch`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/pestphp-pest-plugin-arch-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `pestphp/pest-plugin-arch` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/pestphp-pest-plugin-arch": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `pestphp/pest-plugin-arch` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `pestphp/pest-plugin-arch` with a real constraint,
   `"replace": { "tyhpdef/pestphp-pest-plugin-arch": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `pestphp/pest-plugin-arch` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/pestphp-pest-plugin-arch` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
