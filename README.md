# npm-hooks

[![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)

This is a helper to create npm hooks. It will ensure that you never overwrite hooks which maybe there

# THIS IS A FORK
This is my fork of `npm-hooks` package with the (improved) feature such that it will not append the existing hook, and instead clobber it. This is much better in the case where two different scripts race to write the same install hook.

## Usage

[![NPM](https://nodei.co/npm/npm-hooks.png)](https://www.npmjs.com/package/npm-hooks)

## License

MIT, see [LICENSE.md](http://github.com/mikkoh/npm-hooks/blob/master/LICENSE.md) for details.
