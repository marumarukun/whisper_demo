# whisper demo

<center>

<!-- ![image.png](docs/logo.png) -->

</center>

<div align="center">
    <img alt="python versions" src="https://img.shields.io/badge/python-3.12-blue?color=5271FF">
    <a href="https://opensource.org/licenses/MIT">
        <img alt="MIT License" src="https://img.shields.io/badge/license-MIT-green?color=5271FF">
    </a>
    <a href="https://github.com/astral-sh/uv">
        <img alt="uv" src="https://img.shields.io/badge/package%20manager-uv-blue?color=5271FF">
    </a>
    <a href="https://github.com/astral-sh/ruff">
        <img alt="ruff" src="https://img.shields.io/badge/code%20style-ruff-000000.svg?color=5271FF">
    </a>
    <a href="https://github.com/python/mypy">
        <img alt="mypy" src="https://img.shields.io/badge/typing-mypy-blue?color=5271FF">
    </a>
</div>
<br />


## Description

whisperのdemoリポジトリ

- openai-whisperを使用した音声ファイルの文字起こし
  - src/demo_openai.ipynb
- transformersを使用した音声ファイルの文字起こし
  - src/demo_transformers.ipynb

  
## How to use

### dockerコンテナ ビルド & 起動

mac環境用

```bash
docker compose up -d --build mac
```

GPU環境用

```bash
docker compose up -d --build gpu
```

### コンテナにアタッチ

次にVScode左下の`><`ボタンより`コンテナで再度開く`でコンテナにアクセス

### 拡張機能インストール

無事コンテナが開いたら, 「拡張機能の推奨事項があります」という通知が出ると思います.
この通知を許可すると, `.vscode/extensions.json`に記載されている拡張機能が自動的にインストールされます.
もし通知が出なかった場合は, 左のメニューから`拡張機能`を選択し, `フィルターアイコン`->`推奨`‐>`インストールアイコン`を押せば一括インストールできます.

