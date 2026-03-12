# nodejs-security [![Run CI](https://github.com/kkamara/nodejs-security/actions/workflows/node.js.yml/badge.svg)](https://github.com/kkamara/nodejs-security/actions/workflows/node.js.yml)

Hash, Encrypt and Decrypt with the NodeJS Crypto module.

## Installation

* [NodeJS](https://nodejs.org/en/)
* [Yarn](https://yarnpkg.com/).

```bash
  npm install --global yarn
  cp .env.example .env
  yarn install
```

## Usage

```bash
  yarn start # Runs Start-script `yarn node src/index.js`
```

```
  MacBook-Air:nodejs-security kel$ yarn node src/index.js
  yarn node v1.22.19
  Hash: 5e884898da28047151d0e56f8dc6292773603d0d6aabbdd62a11ef721d1542d8
  Random string: de94d6855635e70caa5caac5709303a3ddc85cffd814d3ddacf0080c6f8129f4
  Encrypt 'This is a secret message': d20b70bce1bd1e943a110c8c22d8e1e51fa4e837bddccdf16158f4c9c83b7e50
  Decrypt 'd20b70bce1bd1e943a110c8c22d8e1e51fa4e837bddccdf16158f4c9c83b7e50': This is a secret message
  ✨  Done in 0.16s.
  MacBook-Air:nodejs-security kel$
```

## To run api tests

```bash
  yarn test
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[BSD](https://opensource.org/licenses/BSD-3-Clause)
