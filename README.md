Prusti Assistant
================

VSCode plugin to verify Rust programs with the [Prusti](http://www.pm.inf.ethz.ch/research/prusti.html) verifier.

This plugin is based on a fork of [Rust Assist](https://github.com/mooman219/rust-assist).

## Features

### Inline Code Diagnostics

This extension automatically provides inline diagnostics for Rust by calling `prusti-rustc` and parsing the output.

This can automatically run on save and on startup. See the related flag in the settings.

### Snippets

Basic code-completion snippets are provided for Prusti annotations.

## Requirements

* [Visual C++ Build Tools 2015](https://go.microsoft.com/fwlink/?LinkId=691126)
* [Rustup](https://rustup.rs/)
* [Java Runtime Environment, 64 bit](https://www.java.com/en/download/)
* [Prusti](http://www.pm.inf.ethz.ch/research/prusti.html)
* [Viper](http://viper.ethz.ch/downloads/)
* Configure the paths in the settings
