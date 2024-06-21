# Python-on-Docker
DockerでPythonの仮想環境を立てる際の基本的な構成

# 方法
1. GithubでこのリポジトリをDownload zipする。
1. zipファイルを展開
1. 使うライブラリをrequirements.txtに追加
1. Dockerfileを自分が使いたい環境に設定を変更
1. Dockerfileを使ってDocker環境をビルド

# ファイル構成
```
Python-on-Docker/
    ├─Dockerfile
    ├─requirements.txt
    ├─README.md
    │
    └─src/
        └─Run.py
```

# 備考
Dockerを使って仮想環境を作るのは私の趣味です