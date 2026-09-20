# marzipano-pano-tiler

This script produces the same output as [Google's Marzipano Tool](https://www.marzipano.net/tool/).

[Google's Marzipano Tool](https://www.marzipano.net/tool/) can only be run within a browser on the client side & the tools soruce code in not publically available.
This is a simple node.js script that produces the same output as Google's tool.

This scripts output can be read by the Marzipano viewer in your application.

## Prerequisites

- Node.js 16 or later
- npm

## Installation

```sh
npm install
```

The command installs `sharp`, `join-images`, and `panorama-to-cubemap` from `package.json`.

## Usage

1. Place your equirectangular image in the `./input/` directory.
2. Run `node index.js`.
