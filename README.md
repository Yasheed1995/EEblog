# EEblog

![Alt text](images/Preview.png?raw=true "Title")

## Installation

To run the server, first you need to install django. (recommend using virtualenv)

```
# use python2.7
pip install django==1.7
pip install django_markdown
```

Then you can run the server by

```
chmod +x runserver.sh
./runserver.sh
```

The server will run at localhost:8001.

## Features

### 基本功能：
- Header: The EE blog
- List of Articles
- Article Body

### 其他功能：
- 登入畫面： 點選畫面上方的"Admin"來登入管理畫面，預設帳密為guest, 1234567890。
- 線上編輯文章： 在管理畫面裡，可以使用編輯器來編輯、排版。
