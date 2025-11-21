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

## 使用技術
Python 3
Flask
Flask-SQLAlchemy
SQLite
HTML / CSS
Bootstrap

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

## 起動方法
pip install -r requirements.txt
python app.py

## ウェブアプリの画像
<img width="1864" height="891" alt="スクリーンショット 2025-11-21 151805" src="https://github.com/user-attachments/assets/089b5191-a1b5-46e0-a614-fbe7ac5e1f35" />
<img width="1882" height="763" alt="スクリーンショット 2025-11-21 151821" src="https://github.com/user-attachments/assets/f3752973-84a3-4068-8d67-31abc706fdb8" />
<img width="1826" height="739" alt="スクリーンショット 2025-11-21 151835" src="https://github.com/user-attachments/assets/79178669-dcfe-4117-baab-4bd584664526" />
<img width="1895" height="780" alt="スクリーンショット 2025-11-21 151858" src="https://github.com/user-attachments/assets/c4274fe0-9abb-4901-8ea6-da1eb132ad82" />


