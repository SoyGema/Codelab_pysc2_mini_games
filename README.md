

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![label](https://img.shields.io/github/issues-raw/badges/shields/website.svg)]()

## Codelab pysc2 structure for AI Deepmind and Blizzard workshop 

This is a repository that offers a template for a codelab structure to make minigames . 
It is based in conclussions offered by the talk "Tips and tricks for minigames design" that will be offered in Blizzcon 2017.

Please, note that this is a template .
The proposed structure might change after recieved feedback about the proposed structure .
The goal is to upload 1st iteration in 3rd and 4th of November

## Install the Polymer-CLI

[Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Install the bower dependencies

```
$ bower install
```

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```
