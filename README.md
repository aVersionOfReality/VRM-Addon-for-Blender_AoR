<a name="en" />

[ English / [日本語](#ja_JP) ]

# VRM Add-on for Blender <a href="https://github.com/saturday06/VRM-Addon-for-Blender/actions"><img alt="CI status" src="https://github.com/saturday06/VRM-Addon-for-Blender/actions/workflows/test.yml/badge.svg?branch=main"></a> <a href="https://github.com/psf/black"><img alt="Code style is black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>

VRM Add-on for Blender is an add-on to add VRM-related functions into Blender.

## Download

Please download the add-on from this website: [https://vrm-addon-for-blender.info](https://vrm-addon-for-blender.info)

## Tutorials

| [Installation](https://vrm-addon-for-blender.info/en/installation?locale_redirection) | [Create Simple VRM](https://vrm-addon-for-blender.info/en/create-simple-vrm-from-scratch?locale_redirection) | [Create Humanoid VRM](https://vrm-addon-for-blender.info/en/create-humanoid-vrm-from-scratch?locale_redirection) |
| :---: | :---: | :---: |
| <a href="https://vrm-addon-for-blender.info/en/installation?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/installation.gif"></a> | <a href="https://vrm-addon-for-blender.info/en/create-simple-vrm-from-scratch?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/simple.gif"></a> | <a href="https://vrm-addon-for-blender.info/en/create-humanoid-vrm-from-scratch?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/humanoid.gif"></a> |
| **[Create Physics Based Material](https://vrm-addon-for-blender.info/en/material-pbr?locale_redirection)** | **[Create Anime Style Material](https://vrm-addon-for-blender.info/en/material-mtoon?locale_redirection)** | **[Automation with Python Scripts](https://vrm-addon-for-blender.info/en/scripting-api?locale_redirection)** |
| <a href="https://vrm-addon-for-blender.info/en/material-pbr?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/material_pbr.gif"></a> | <a href="https://vrm-addon-for-blender.info/en/material-mtoon?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/material_mtoon.gif"></a> | <a href="https://vrm-addon-for-blender.info/en/scripting-api?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/scripting_api.png"></a> |

## Overview

This add-on adds VRM-related functions to Blender, such as importing and exporting VRM, adding VRM Humanoid and setting MToon shaders. Bug reports, feature requests, pull requests, etc. are welcome. I have taken over the development after [Version 0.79](https://github.com/iCyP/VRM_IMPORTER_for_Blender2_8/releases/tag/0.79) from the author, [@iCyP](https://github.com/iCyP).

## Development

The source code for development is in the <a href="https://github.com/saturday06/VRM-Addon-for-Blender/tree/main">`main`</a> branch. Its <a href="https://github.com/saturday06/VRM-Addon-for-Blender/tree/main/io_scene_vrm">`io_scene_vrm`</a> folder is a main body of the add-on. For efficient development, you can create a link to that folder in the Blender `addons` folder.

For more advanced development, such as running tests, please use [Poetry](https://python-poetry.org/).

```text
git checkout main
git submodule update --init

# Linux
ln -s "$PWD/io_scene_vrm" "$HOME/.config/blender/BLENDER_VERSION/scripts/addons/io_scene_vrm"
# macOS
ln -s "$PWD/io_scene_vrm" "$HOME/Library/Application Support/Blender/BLENDER_VERSION/scripts/addons/io_scene_vrm"
# Windows PowerShell
New-Item -ItemType Junction -Path "$Env:APPDATA\Blender Foundation\Blender\BLENDER_VERSION\scripts\addons\io_scene_vrm" -Value "$(Get-Location)\io_scene_vrm"
# Windows Command Prompt
mklink /j "%APPDATA%\Blender Foundation\Blender\BLENDER_VERSION\scripts\addons\io_scene_vrm" io_scene_vrm
```

-----

<a name="ja_JP" />

[ [English](#en) / 日本語 ]

# VRM Add-on for Blender <a href="https://github.com/saturday06/VRM-Addon-for-Blender/actions"><img alt="CI status" src="https://github.com/saturday06/VRM-Addon-for-Blender/actions/workflows/test.yml/badge.svg?branch=main"></a> <a href="https://github.com/psf/black"><img alt="Code style is black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>

BlenderにVRM関連機能を追加するアドオンです。

## ダウンロード

こちらのWebサイトからダウンロードしてください: [https://vrm-addon-for-blender.info](https://vrm-addon-for-blender.info)

## チュートリアル

| [インストール方法](https://vrm-addon-for-blender.info/en/installation?locale_redirection) | [シンプルなVRMを作る](https://vrm-addon-for-blender.info/en/create-simple-vrm-from-scratch?locale_redirection) | [人型のVRMを作る](https://vrm-addon-for-blender.info/en/create-humanoid-vrm-from-scratch?locale_redirection) |
| :---: | :---: | :---: |
| <a href="https://vrm-addon-for-blender.info/en/installation?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/installation.gif"></a> | <a href="https://vrm-addon-for-blender.info/en/create-simple-vrm-from-scratch?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/simple.gif"></a> | <a href="https://vrm-addon-for-blender.info/en/create-humanoid-vrm-from-scratch?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/humanoid.gif"></a> |
| **[物理ベースのマテリアル設定](https://vrm-addon-for-blender.info/ja/material-pbr?locale_redirection)** | **[アニメ風のマテリアル設定](https://vrm-addon-for-blender.info/ja/material-mtoon?locale_redirection)** | **[Pythonスクリプトによる自動化](https://vrm-addon-for-blender.info/en/scripting-api?locale_redirection)** |
| <a href="https://vrm-addon-for-blender.info/en/material-pbr?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/material_pbr.gif"></a> | <a href="https://vrm-addon-for-blender.info/en/material-mtoon?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/material_mtoon.gif"></a> | <a href="https://vrm-addon-for-blender.info/en/scripting-api?locale_redirection"><img width="200" src="https://vrm-addon-for-blender.info/images/scripting_api.png"></a> |

## 概要

BlenderにVRMのインポートやエクスポート、VRM Humanoidの追加やMToonシェーダーの設定などのVRM関連機能を追加するアドオンです。バグ報告、機能要望、Pull Request等歓迎します。[バージョン 0.79](https://github.com/iCyP/VRM_IMPORTER_for_Blender2_8/releases/tag/0.79)以降の開発を作者である[@iCyP](https://github.com/iCyP)さんから引き継ぎました。

## 開発するには

開発用のソースコードは<a href="https://github.com/saturday06/VRM-Addon-for-Blender/tree/main">`main`</a>ブランチにあります。ブランチ内の <a href="https://github.com/saturday06/VRM-Addon-for-Blender/tree/main/io_scene_vrm">`io_scene_vrm`</a> フォルダがアドオン本体です。
`io_scene_vrm` フォルダへのリンクをBlenderの `addons` フォルダ内に作ることで効率的に開発をすることができます。

テストの実行など、より高度な開発をする場合は[Poetry](https://python-poetry.org/)をご利用ください。

```text
git checkout main
git submodule update --init

# Linux
ln -s "$PWD/io_scene_vrm" "$HOME/.config/blender/BLENDER_VERSION/scripts/addons/io_scene_vrm"
# macOS
ln -s "$PWD/io_scene_vrm" "$HOME/Library/Application Support/Blender/BLENDER_VERSION/scripts/addons/io_scene_vrm"
# Windows PowerShell
New-Item -ItemType Junction -Path "$Env:APPDATA\Blender Foundation\Blender\BLENDER_VERSION\scripts\addons\io_scene_vrm" -Value "$(Get-Location)\io_scene_vrm"
# Windows Command Prompt
mklink /j "%APPDATA%\Blender Foundation\Blender\BLENDER_VERSION\scripts\addons\io_scene_vrm" io_scene_vrm
```
