# Monokai Pro

Fork of [monokai-pro](https://github.com/subtheme-dev/monokai-pro) plugin, working with latest Webstorm and Intelij (as of 24.09.2024).

## Install

[Latest release](https://github.com/krizzu/monokai-pro/releases) (v1.11) is the one built from sources and tested

## Build it yourself

Install deps

```shell
python3 -m venv ./venv
source ./venv/bin/activate
python3 -m pip install sublate
```

Build package

```shell
./build.py
```

Bundle plugin

1. Open `output/jetbrains` in Intelij
2. Select `Build -> Prepare Plugin Module For Deployment`
3. Built .jar file is located in `output/jetbrains` dir

Install plugin

1. Open IDE
2. Open Settings -> Plugins
3. Extra menu (next to Marketplace | Installed) -> Install plugin from disk
4. Select build jar
5. Restart IDE


---
## Official docs

The unofficial Monokai Pro theme, adapted by [Subtheme](https://subtheme.dev). This repository includes the default theme, classic theme, and four filters: Machine, Octagon, Ristretto, and Spectrum. Credit goes to the original creator: [https://monokai.pro](https://monokai.pro).

Download the latest build from [Releases](https://github.com/subtheme-dev/monokai-pro/releases).

Supported apps:
- [iTerm](theme/iterm)
- [JetBrains](theme/jetbrains)
- [Lapce](theme/lapce)
- [Terminal](theme/terminal)

To build, first install [sublate](https://github.com/espositocode/sublate):

    $ pip install sublate

Then, run the build script:

    $ ./build.py
