# Graphviz Extension for Freedesktop SDK

## About
This repository contains a flatpak manifest for building a Graphviz extension for the Freedesktop SDK.

## Building and installing
```sh
flatpak-builder --install ./build org.freedesktop.Sdk.Extension.graphviz.yml
```
## How to enable
In order to enable the Graphviz commands in a Freedesktop SDK Application (e.g. Visual Studio Code Flatpak), add `graphviz` to the environment variable `FLATPAK_ENABLE_SDK_EXT`.
