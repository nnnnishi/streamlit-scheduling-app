# DSの結果をアプリで確認

## ディレクトリ、ファイルの説明
- **data**: アプリで利用するカレンダー、スタッフの入力データ例を格納しています
- **src**: シフトスケジューリングのための数理最適化モジュールを配置します
- **work**: アプリを以下のディレクトリ内で実装することを想定しています
- **ans**: アプリの実装例を格納しています
- **requirements.txt**: アプリで利用するPythonライブラリ、Streamlit Cloudにアップロードする際には本ファイルもGitHub上に配置することが必要です

## インストール手順
1. Pythonをインストールします（推奨バージョン: 3.8以上）
2. 必要なライブラリをインストールします
```bash
pip install -r requirements.txt
```

## プログラムの実行例
以下のコマンドでアプリを実行します
```bash
streamlit run work/app_8_2.py
```

## アプリの概要
このアプリは、数理最適化を用いたシフトスケジューリングを行うためのツールです。ユーザーはカレンダーとスタッフのデータを入力し、数理モデルのもとでの最適なシフトスケジュールを生成することができます

## 使用方法
- dataディレクトリにあるサンプルデータを参考に、カレンダーとスタッフのデータを準備します
- 上記の「プログラムの実行例」に従ってアプリを起動します
- アプリのインターフェースに従って、データをアップロードし、シフト表作成タブの最適化実行ボタンを押すとシフトスケジュールが生成されます
