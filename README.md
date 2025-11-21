# Todolist アプリ

## 概要
このアプリは、タスクの管理・記録を行うためのシンプルな Web アプリです。  
タスクの作成・編集・削除や、期限付きタスクの管理が可能です。

## 機能
- タスクの追加（タイトル、詳細、期限）
- タスクの一覧表示
- タスクの編集・更新
- タスクの削除（削除時に確認ダイアログ表示）
- タスクの期限順ソート

## ファイル構成
webapp_td$
├── Procfile
├── README.md
├── __pycache__
│   └── app.cpython-312.pyc
├── app.py
├── instance
│   └── todo.db
├── static
│   └── css
│       ├── bootstrap-grid.css
│       ├── bootstrap-grid.css.map
│       ├── bootstrap-grid.css.map:Zone.Identifier
│       ├── bootstrap-grid.css:Zone.Identifier
│       ├── bootstrap-grid.min.css
│       ├── bootstrap-grid.min.css.map
│       ├── bootstrap-grid.min.css.map:Zone.Identifier
│       ├── bootstrap-grid.min.css:Zone.Identifier
│       ├── bootstrap-grid.rtl.css
│       ├── bootstrap-grid.rtl.css.map
│       ├── bootstrap-grid.rtl.css.map:Zone.Identifier
│       ├── bootstrap-grid.rtl.css:Zone.Identifier
│       ├── bootstrap-grid.rtl.min.css
│       ├── bootstrap-grid.rtl.min.css.map
│       ├── bootstrap-grid.rtl.min.css.map:Zone.Identifier
│       ├── bootstrap-grid.rtl.min.css:Zone.Identifier
│       ├── bootstrap-reboot.css
│       ├── bootstrap-reboot.css.map
│       ├── bootstrap-reboot.css.map:Zone.Identifier
│       ├── bootstrap-reboot.css:Zone.Identifier
│       ├── bootstrap-reboot.min.css
│       ├── bootstrap-reboot.min.css.map
│       ├── bootstrap-reboot.min.css.map:Zone.Identifier
│       ├── bootstrap-reboot.min.css:Zone.Identifier
│       ├── bootstrap-reboot.rtl.css
│       ├── bootstrap-reboot.rtl.css.map
│       ├── bootstrap-reboot.rtl.css.map:Zone.Identifier
│       ├── bootstrap-reboot.rtl.css:Zone.Identifier
│       ├── bootstrap-reboot.rtl.min.css
│       ├── bootstrap-reboot.rtl.min.css.map
│       ├── bootstrap-reboot.rtl.min.css.map:Zone.Identifier
│       ├── bootstrap-reboot.rtl.min.css:Zone.Identifier
│       ├── bootstrap-utilities.css
│       ├── bootstrap-utilities.css.map
│       ├── bootstrap-utilities.css.map:Zone.Identifier
│       ├── bootstrap-utilities.css:Zone.Identifier
│       ├── bootstrap-utilities.min.css
│       ├── bootstrap-utilities.min.css.map
│       ├── bootstrap-utilities.min.css.map:Zone.Identifier
│       ├── bootstrap-utilities.min.css:Zone.Identifier
│       ├── bootstrap-utilities.rtl.css
│       ├── bootstrap-utilities.rtl.css.map
│       ├── bootstrap-utilities.rtl.css.map:Zone.Identifier
│       ├── bootstrap-utilities.rtl.css:Zone.Identifier
│       ├── bootstrap-utilities.rtl.min.css
│       ├── bootstrap-utilities.rtl.min.css.map
│       ├── bootstrap-utilities.rtl.min.css.map:Zone.Identifier
│       ├── bootstrap-utilities.rtl.min.css:Zone.Identifier
│       ├── bootstrap.css
│       ├── bootstrap.css.map
│       ├── bootstrap.css.map:Zone.Identifier
│       ├── bootstrap.css:Zone.Identifier
│       ├── bootstrap.min.css
│       ├── bootstrap.min.css.map
│       ├── bootstrap.min.css.map:Zone.Identifier
│       ├── bootstrap.min.css:Zone.Identifier
│       ├── bootstrap.rtl.css
│       ├── bootstrap.rtl.css.map
│       ├── bootstrap.rtl.css.map:Zone.Identifier
│       ├── bootstrap.rtl.css:Zone.Identifier
│       ├── bootstrap.rtl.min.css
│       ├── bootstrap.rtl.min.css.map
│       ├── bootstrap.rtl.min.css.map:Zone.Identifier
│       └── bootstrap.rtl.min.css:Zone.Identifier
└── templates
    ├── base.html
    ├── create.html
    ├── detail.html
    ├── index.html
    └── update.html

起動方法
pip install -r requirements.txt
python app.py




