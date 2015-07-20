# lein-marginalia

A [Leiningen](https://github.com/technomancy/leiningen) plugin for [Marginalia](https://github.com/MichaelBlume/marginalia).  You would most likely use this rather than Marginalia directly.

## Fork

This is a fork of [lein-marginalia](https://github.com/gdeer81/lein-marginalia)
which fixes [compatibility with Clojure
1.7](https://github.com/gdeer81/marginalia/issues/153).

## Installation

### Leiningen 2

Add `[[michaelblume/lein-marginalia "0.9.0"]]` to the `:plugins` entry in
either your project.clj file or your `:user` profile.

### Leiningen 1

Add `[michaelblume/lein-marginalia "0.9.0"]` to your project.clj's
`:dev-dependencies` or, install lein-marginalia as a user-level
leiningen plugin by running
`$ lein plugin install michaelblume/lein-marginalia 0.9.0`.

## Usage

`$ lein marg <args>` in your project's root.

License
-------

Copyright (C) 2011-2013 Fogus and contributors.

Distributed under the Eclipse Public License, the same as Clojure.
