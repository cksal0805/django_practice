# Django Prectice

## ๐ฑ Django ๊ธฐ์ด ์ฐ์ต์ฉ ๋ ํ์งํ ๋ฆฌ ์๋๋ค

- ๋๋ถ๋ถ์ ๋ด์ฉ์ [Django๋ฌธ์](https://docs.djangoproject.com/ko/3.2/intro/)์ [์ฅ๊ณ ๊ฑธ์คํํ ๋ฆฌ์ผ](https://tutorial.djangogirls.org/ko/django_start_project/) ๋ฅผ ์ฐธ๊ณ ํ์ฌ ์์ฑํฉ๋๋ค.

### ๋ชฉ์ 

์๋ฒ์ชฝ์ ๋ Node๋ฅผ ์จ์๋๋ฐ, Django๋ฅผ ์ ๊น ์ธ์ผ์ด ์๊ฒจ ์ฐ๋๊น์ ์ ๋ฆฌํด ๋ก๋๋ค.

### ๊ธฐ๋ก

- [x] **[5/19์ผ] Django ๊ฐ๋๊ณผ ๊ธฐ๋ณธ์ํ ๋ฐ ์๋ฒ์คํ**
- [x] **[5/20์ผ] Django ๋ชจ๋ธ๋ง**

### Django๋ ๋ฌด์์ธ๊ฐ?

python์ผ๋ก ๋ง๋ค์ด์ง ๋ฌด๋ฃ ์ดํ๋ฆฌ์ผ์ด์ ํ๋ ์์ํฌ ์๋๋ค.
์ฅ์ ์ผ๋ก๋ ์ด๋ณด์ ๋ถ๋ค์ด ๋ฐฐ์ฐ๊ธฐ ์ฌ์ด python์ผ๋ก ๋์ด์๋ค๋ ์ ์ด๊ณ , ๋ก๊ทธ์ธ, ํ์๊ฐ์, ์ธ์ฆ,cors๋ฑ์ ๋ฐ๋ณต์ ์ผ๋ก ๊ตฌํํด์ผ ํ๋ ๋ถ๋ถ์ ์ด๋ฏธ ๋ง๋ค์ด์ก๋ค ๋ผ๋ ์ ์์ ๊ฐ๋ฐ ์๊ฐ์ ๋จ์ถ ์ํฌ ์ ์์ ๊ฒ ๊ฐ์ต๋๋ค.

### Django์์ ๊ฐ์ง๊ณ  ๊ฐ๋ ํจํด

๋ณดํต MVC ํจํด์ ๋ง์ด ์ฌ์ฉํฉ๋๋ค.(ํนํ ๋ํ์ ์ผ๋ก spring)
ํ์ง๋ง Django๋ MVT(mobile-view-templates) ๊ธฐ๋ฐ ์๋๋ค.

## ๊ฐ์ํ๊ฒฝ (Virtual environment)

์ฅ๊ณ ๋ ๊ฐ์ํ๊ฒฝ์ ์ค์นํด์ ๋๋ฆฝ์  ํ๊ฒฝ์์ ๊ฐ๋ฐํฉ๋๋ค.
๊ฐ์ ๋ ์๋๋๋ค. ํ์ง๋ง ๊ฐ์ํ๊ฒฝ์์ ๊ฐ๋ฐ์ ์ ๊ทน ๊ถํฉ๋๋ค.
์? ๊ฐ์ํ๊ฒฝ์์ ์ค์นํด์ผ ํ๋? ์ ์ญ์ ์ธ ๊ณต๊ฐ์ ์ค์นํด ๊ฐ๋ฐ์ ์งํ ํ  ๊ฒฝ์ฐ
ํ ์ปดํจํฐ์์ ํ๋์ ์ฅ๊ณ  ๋ฒ์ ๋ง์ ์ฌ์ฉํ  ์ ์์ต๋๋ค. a๋ฒ์ ์์ ํ๋ก์ ํธ๋ฅผ ์งํํ๋ค๊ฐ ๋ค๋ฅธ ํ๋ก์ ํธ์์ c๋ฒ์ ์ ์ฌ์ฉํ๋ ค๊ณ  ํ๋ค๋ฉด ํ ์ปดํจํฐ์์ ํ๋์ ์ฅ๊ณ  ๋ฒ์ ๋ง์ ์ฌ์ฉํ  ์ ์๊ธฐ์ ๋ฒ์ ์์ ์์ผ์ผ ํ๋๋ฐ ์ถฉ๋์ด๋๊ฑฐ๋ ๋ฌธ์ ๊ฐ ์๊ธธ ์ ์์ฃ .

### Node.js ์ Django์ ๋น๊ต

CRUD์ ์ง์ค๋์ด์๋ ํ๋ก์ ํธ๋ผ๋ฉด Django ๋ฅผ ์ฌ์ฉํ  ๊ฒ ๊ฐ๊ณ ,
์ปค์คํฐ๋ง์ด์ง์ด ๋ง์ด ํ์ํ๋ค๋ฉด, Node.js๋ฅผ ์ ํ ํ  ๊ฒ ๊ฐ์๋ฐ,
๊ฐ์ธ์ ์ผ๋ก๋ js๋ฅผ ์ฃผ ์ธ์ด๋ก ์ฐ๋ ์์ฅ์์ Node.js๊ฐ ํธํ  ๊ฒ ๊ฐ์ต๋๋ค.
์๋๋ฉด์์๋ ๊ทธ๋ ๊ณ ์.

## ๊ฐ์ํ๊ฒฝ ๋ฐ ์ฅ๊ณ  ์ค์น ๋ฐ ์ํ

mac os ๊ธฐ์ค **prectice_venv** ์ด๋ผ๋ ์ด๋ฆ์ ๊ฐ์ํ๊ฒฝ ์ค์น(์ด๋ฆ์ ๋ง์๋๋ก)

```shell
python3 -m venv prectice_venv
```

์ฅ๊ณ  ์ค์น (๋น์ฐํ ํ์ด์ฌ์ ์ค์น ๋์ด์๋ค๋ ๊ฐ์ ํ์)

1. ๊ฐ์ํ๊ฒฝ ํ์ฑํ

```shell (prectice_venv๋ ์ฌ๋ฌ๋ถ์ด ๋ง๋  ๊ฐ์ํ๊ฒฝ ์ด๋ฆ)
source prectice_venv/bin/activate
```

2. ์ฅ๊ณ  ์ค์น

```shell
pip install django~=2.0.0
```
---
๐ฅ **ModuleNotFoundError: No module named 'pip' ๋ผ๊ณ  ๋ ์!!!** ๐ฅ 

๋ง์ฝ ModuleNotFoundError: No module named 'pip' ๋ผ๊ณ  ๋ฌ๋ค๋ฉด,
์๋์ ๊ฐ์ด ์ฅ๊ณ ๋ฅผ ์ค์นํ๋๋ฐ ํ์ํ pip๋ฒ์ ์ด ์ต์ ์ธ์ง ํ์ธํ๊ณ  install์ ์งํ

```shell
python3 -m pip install --upgrade pip
```

๋ง์ฝ ๊ธฐ์กด์ ์ค์นํ์๋๋ฐ ์๋๋ค๋ฉด ์๊ทธ๋ ์ด๋ ํ๊ณ  ์ญ์  ํ ์ฌ์ค์น ํ๋ ๊ณผ์ ์์ ๊ถํ ๋ฌธ์ ๋ก pip๊ฐ ์ญ์ ๋ ์ํ๋ก ๋จ์ ์ด๋ฐ ํ์์ด ๋ฐ์ ํ  ์ ์์ผ๋ฏ๋ก pypa๋ฅผ ํตํด pip๋ฅผ ์ฌ์ค์น ํด์ค๋๋ค.

```shell
//curl์ ์ด์ฉํด ๋ค์ด
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

//์ค์น
python get-pip.py
```

์ฑ๊ณต์ ์ผ๋ก ๋๋ค๋ฉด?

```shell
pip3 -V // ๋ฒ์  ํ์ธ ๋ฒ์ ์ด ์๋จ๋ฉด ์ฑ๊ณต์ ์ผ๋ก ์ค์น ๋๊ฑฐ์
```

---

## ๊ฐ๋จํ ํ๋ก์ ํธ ๋ง๋ค์ด๋ณด๊ธฐ

**โ๐ป ์๋ ๋ชจ๋  ์ํ์ ๋ฐ๋์ ๊ฐ์ํ๊ฒฝ์์ ์งํํด์ฃผ์ธ์!!!**

> ๐บ **๊ฐ์ํ๊ฒฝ ํ์ฑํ ๋ฐฉ๋ฒ**
(prectice_venv์๋ ์ฌ๋ฌ๋ถ์ด ๋ง๋  ๊ฐ์ํ๊ฒฝ ์ด๋ฆ)
mac os (shell์์) - source prectice_venv/bin/activate
window (cmd์์) - prectice_venv\Scripts\activat

#### 1. ์ฅ๊ณ ํ๋ก์ ํธ ์์ํ๊ธฐ(๊ณจ๊ฒฉ์ ๋ง๋ค์ด์ฃผ๋ ์คํฌ๋ฆฝํธ ์คํ)

- mysite ๋ ๊ทธ๋ฅ ์ด๋ฆ์ ์ฌ๋ฌ๋ถ ๋ง์๋๋ก ํ๋ฉด ๋จ
- .์ ํ์ฌ ๋๋ ํ ๋ฆฌ์ ๋ถ๋ฌ์ค๊ฒ ๋ค๋ ์๋ฆฌ

```shell
django-admin startproject mysite .
```

์ฑ๊ณต์ ์ผ๋ก ๋ง๋ค์ด ์ก๋ค๋ฉด ์๋์ ๊ฐ์ ํ์ด์ฌ ํ์ผ์ด ์๊ธธ ๊ฒ๋๋ค.
์ ๋ backํด๋ ์์์ ์์ ์ค์น๋ค์ ๋ชจ๋ ์งํํ์ต๋๋ค.

```bash
.
โโโ ๐ back
โโโ ๐ manage.py            # Django ํ๋ก์ ํธ์ ๋ค์ํ ๋ฐฉ๋ฒ์ผ๋ก ์ํธ์์ฉ ํ๋ ์ปค๋งจ๋๋ผ์ธ์ ์ ํธ๋ฆฌํฐ
โ   โโโ ๐ __ init __.py
โ   โโโ ๐ settings.py      # ์น์ฌ์ดํธ ์ค์ ์ด ์๋ ํ์ผ
โ   โโโ ๐ asgi.py
โ   โโโ ๐ wsgi.py
โ   โโโ ๐ urls.py           # urlresolver๊ฐ ์ฌ์ฉํ๋ ํ์ผ
โโโ ...
```

**๐ asgi, wsgi ์ ๋ญ๊น?**

Django ์น ์ดํ๋ฆฌ์ผ์ด์ ์๋ฒ ์ํคํ์ณ์์๋ Django ํ๋ ์์ํฌ ๋ด๋ถ์ url๊ณผ web server๊ฐ ํต์ ํฉ๋๋ค.

์ฌ๊ธฐ์ web server๋ก ๋ง์ด ์ฌ์ฉ๋๋ Apach HTTP Server์ Tomcat์ JAVA๊ธฐ๋ฐ์ด๋ฏ๋ก ํ์ด์ฌ ์ฝ๋๋ฅผ ์ฝ์ ์ ์๋ค. ๊ทธ๋ ๊ธฐ ๋๋ฌธ์ ์ฌ์ฉํ  ์ ์๋ ์น์๋ฒ๋ ๋งค์ฐ ํ์ ์ ์๋๋ค.

์ฑ๋ฅ๋ฉด์์ ๊ฒ์ฆ๋์ด์๋ apach์ชฝ์ ์น์๋ฒ๋ฅผ ์ด์ฉํ๋ฉด ์ข์๋ฐ,

์ด๋ ์ต์ ์ ์๋ฃจ์์ด Apach ์ฌ๋จ์ ์น ์๋ฒ ๋ฟ๋ง ์๋๋ผ ๋ชจ๋  ์น ์๋ฒ์ Python ๊ณ์ด์ ํ๋ ์ ์ํฌ๊ฐ ํต์ ํ  ์ ์๊ฒ ํด์ฃผ๋ ๋ฏธ๋ค ์จ์ด๋ฅผ ์ฌ์ฉํ๋ ๊ฒ์๋๋ค. ์ด๊ฒ ๋ฐ๋ก asgi,wsgi ์๋๋ค.

- asgi๋ web server์ ํ๋ ์์ํฌ(django) ์ ํ๋ฆฌ์ผ์ด์์ ์ฐ๊ฒฐํด ์ฃผ๋ python์ ํ์ค api, wsgi์์ ์์ํธํ

- wsgi๋ ASGI์ด์ ์ Python์ ํ์ค ๋น๋๊ธฐ ๋ฐฉ์ ๊ธฐ๋ฅ์ ๊ตฌํ์ ์์ด์ ๋ฌธ์ ๊ฐ ๋ง์๋ wsgi๋ผ asgi๊ฐ ๋์๋ค.

**์์ธํ ์ฌํญ์ ์๋ ๋งํฌ ์ฐธ์กฐ**
https://nitro04.blogspot.com/2020/01/django-python-asgi-wsgi-analysis-of.html

#### 2. ์ค์ ๋ณ๊ฒฝ

- mysite/settings.py์ ์กฐ๊ธ ๊ณ ์ณ ๋ณผ๊ฒ์. ์ค์นํ ์ฝ๋ ์๋ํฐ๋ฅผ ์ด์ด ํ์ผ์ ์ด์ด์ฃผ์ธ์

**์๊ฐ ๋ฐ๊พธ๊ธฐ**

> TIME_ZONE = 'UTC' -> TIME_ZONE = 'Asia/Seoul'

**์ ์ ํ์ผ ๊ฒฝ๋ก ์ถ๊ฐํ๊ธฐ**

> STATIC_URL = '/static/'
STATIC_ROOT = BASE_DIR, 'static'

**ํธ์คํธ์ค์ **

๋๋ฒ๊น ๋ชจ๋์์ ALLOWED_HOSTS ๋ณ์๊ฐ ๋น ๋ฆฌ์คํธ์ผ ๊ฒฝ์ฐ ['localhost', '127.0.0.1', '[::1]'] ์๋ฏธ๊ฐ ๋ฉ๋๋ค. ์ฆ, **๋ก์ปฌ ํธ์คํธ์์๋ง ์ ์**์ด ๊ฐ๋ฅํฉ๋๋ค.
์ ํ๋ฆฌ์ผ์ด์์ ๋ฐฐํฌํ  ๋ PythonAnywhere์ ํธ์คํธ ์ด๋ฆ๊ณผ ์ผ์นํ์ง ์์ผ๋ฏ๋ก ๋ค์ ์ค์ ์ ์๋์ ๊ฐ์ด ๋ณ๊ฒฝํด์ค์ผ ํฉ๋๋ค.
> ALLOWED_HOSTS = ['127.0.0.1', '.pythonanywhere.com']

**DB์ค์ **

๋ฐ์ดํฐ ๋ฒ ์ด์ค๋ฅผ ์์ฑํ๊ธฐ ์ํด ์๋์ ๊ฐ์ ๋ช๋ น์ด๋ฅผ ์๋ ฅํฉ๋๋ค.
python๋ถํฐ ์๋ ฅํ์๋ฉด ๋ฉ๋๋ค. (์๋ ๋ช๋ น์ด๋ฅผ ์คํํ๊ธฐ ์ํด manage.py์ด ํ์)

```shell
 (prectice_venv) back$ python manage.py migratepython manage.py migrate
```

#### 3. ์น์๋ฒ ์์ํ๊ธฐ

python๋ถํฐ ์๋ ฅํ์๋ฉด ๋ฉ๋๋ค. (์๋ ๋ช๋ น์ด๋ฅผ ์คํํ๊ธฐ ์ํด manage.py์ด ํ์)

```shell
 (prectice_venv) back$ python manage.py runserver
```

๋ธ๋ผ์ฐ์ ์์
http://127.0.0.1:8000/ ๋ฅผ ์๋ ฅํด ์ด์ด๋ณด์ธ์!

```shell
Django version 3.2.3, using settings 'mysite.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
[19/May/2021 23:00:19] "GET / HTTP/1.1" 200 10697
[19/May/2021 23:00:19] "GET /static/admin/css/fonts.css HTTP/1.1" 200 423
[19/May/2021 23:00:19] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 200 86184
[19/May/2021 23:00:19] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 200 85876
[19/May/2021 23:00:19] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 200 85692
Not Found: /favicon.ico
```

๐คฉ ์ฑ๊ณต!

#### ์ด๋ฐ๊ฒฝ์ฐ๋ ์ด๋ป๊ฒํ์ฃ ?

**๐ฅ Error: That port is already in use.**
์ด๋ด ๊ฒฝ์ฐ port 8000๊ณผ ๊ด๋ จ๋ ๋ชจ๋  ํ๋ก์ธ์ค๋ฅผ ์ฃฝ์ด๊ณ  ๋ค์ ์คํ์ํค๋ฉด ๋๋ค.

```shell
sudo lsof -t -i tcp:8000 | xargs kill -9
```

**๐ฅ File "manage.py", line 17 from exc SyntaxError: invalid syntax**
python manage.py runserver์์ ์์ ๊ฐ์ ๋ฌธ์ ๊ฐ ์๊ธด๋ค๋ฉด,

1.ํ์ฌ ๊ฐ์ํ๊ฒฝ๋ด๋ถ์์ ์งํํ๊ณ  ์๋์ง ์ฒดํฌํ๋ค.
> ๐บ **๊ฐ์ํ๊ฒฝ ํ์ฑํ ๋ฐฉ๋ฒ**
(prectice_venv์๋ ์ฌ๋ฌ๋ถ์ด ๋ง๋  ๊ฐ์ํ๊ฒฝ ์ด๋ฆ)
mac os (shell์์) - source prectice_venv/bin/activate
window (cmd์์) - prectice_venv\Scripts\activat

2. ํ์ฌ ์ฌ์ฉํ๋ ํ์ด์ฌ์ ๋ฒ์ ์ ์ง์ ํด์ ์คํํ๋ค.

```shell
python3 manage.py runserver
```

---------------------

### ์ฅ๊ณ ๋ชจ๋ธ

ํน์ง: ๊ฐ์ฒด์งํฅ์  ์ค๊ณ, ์ฅ๊ณ ์์ ์๋ ๋ชจ๋ธ์ ๊ฐ์ฒด์ ํน๋ณํ ์ข๋ฅ, ์ด ๋ชจ๋ธ์ ์ ์ฅํ๋ฉด ๊ทธ ๋ด์ฉ์ด ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ์ ์ฅ๋ฉ๋๋ค.

๋ฐ์ดํฐ๋ฒ ์ด์ค๋ ์ํ๋ ๊ฑธ๋ก ์ฌ์ฉํ๋ฉด ๋ฉ๋๋ค. ํ์ง๋ง ์ด๋ฒ ๋ ํฌ์์๋ ์ฐ์ต์ฉ์ด๋ฏ๋ก SQLite(๊ธฐ๋ณธ ์ฅ๊ณ  ๋ฐ์ดํฐ๋ฒ ์ด์ค ์ด๋ํฐ)๋ฅผ ์ฌ์ฉํ๋๋ก ํ๊ฒ ์ต๋๋ค.

#### ์ดํ๋ฆฌ์ผ์ด์ ๋ง๋ค๊ธฐ

์๋์ ๊ฐ์ด ์๋ ฅํด์ฃผ๋ฉด ์๋์ผ๋ก ํ์ด์ฌ ํจํค์ง๊ฐ ๊ตฌ์ฑ๋ฉ๋๋ค.
์ฑ์ ๊ธฐ๋ณธ ๋๋ ํฐ๋ฆฌ ๊ตฌ์กฐ๋ฅผ ์๋์ผ๋ก ์์ฑํ  ์ ์๋ ๋๊ตฌ๋ฅผ ์ ๊ณตํ๊ธฐ ๋๋ฌธ์, ์ฝ๋์๋ง ๋์ฑ ์ง์คํ  ์ ์์ต๋๋ค.

```bash
  python3 manage.py startapp blog
```

๊ทธ๋ฌ๋ฉด ์๋์ ๊ฐ์ ํด๋ ๊ตฌ์กฐ๋ฅผ ๋ณด์ค ์ ์์ ๊ฒ๋๋ค.

```bash
.
โโโ ๐ blog
โ   โโโ ๐ migrations 
โ     โโโ  ๐ __ init __.py
โ   โโโ ๐ __init__.py
โ   โโโ ๐ admin.py
โ   โโโ ๐ models.py
โ   โโโ ๐ tests.py
โ   โโโ ๐ views.py
โโโ 
```

์ ํ๋ฆฌ์ผ์ด์์ ์์ฑ ํ ์ฅ๊ณ ์๊ฒ ์ฌ์ฉํ๋ค๊ณ  ์๋ ค์ฃผ๊ฒ ์ต๋๋ค.
**mysite/settings.py** ์์ ์์ ํด์ฃผ๋๋ก ํ๊ฒ ์ต๋๋ค.
INSTALLED_APPS์ ์ฐ๋ฆฌ๊ฐ ๋ง๋  ์ฑ์ ํด๋๋ค์์ ์ถ๊ฐํด์ฃผ์๋ฉด ๋ฉ๋๋ค.

```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'blog', // ์ฌ๊ธฐ ์ถ๊ฐ
]
```

#### ๋ชจ๋ธ

model.pyํ์ผ์ ๋ชจ๋ธ์ ์ ์ํด๋ณด๋๋ก ํ๊ฒ ์ต๋๋ค.

์ฝ๋๋ ๐๐ป [์ฝ๋๋ก๋ฐ๋ก๊ฐ๊ธฐ(ํด๋ฆญ)](https://github.com/cksal0805/django_practice/blob/main/back/blog/models.py) ๋๋ ์  ๋ ํ์งํ ๋ฆฌ back/blog/model.py์์ ํ์ธํ์๋ฉด ๋ฉ๋๋ค.

- Class๋ก ๊ฐ์ฒด์ ์๋ฅผ ํด์ค ์ ์๋ค.
- Class ๋ชจ๋ธ์ด๋ฆ ->  ์ ๊ฐ์ ํ์์ผ๋ก ๋ชจ๋ธ์ด๋ฆ์ ์ ์ ํ  ์ ์๋๋ฐ, ํญ์ ์ฒซ ๊ธ์๋ ๋๋ฌธ์ ์ฌ์ผํฉ๋๋ค.
- models๋ ์ฅ๊ณ ๋ชจ๋ธ์์ ์๋ ค์ค -> ํด๋น ๋ชจ๋ธ์ด DB์ ์ ์ฅ๋์ด์ผ ํจ์ ์๋ ค์ค๋๋ค.
- ์์ฑ์ ์ ์ํ๊ณ  ๋ฐ์ดํฐ ํ์์ ์๋ ค์ฃผ์ด์ผ ํฉ๋๋ค.

```python
title = models.CharField(max_length=200)
```

- def๋ก ๋ฉ์๋๋ฅผ ์ ์ํ  ์ ์์ต๋๋ค.

#### ํ์ด๋ธ

์ฅ๊ณ ๋ชจ๋ธ์ ์ฐ๋ฆฌ๊ฐ ๋ฐฉ๊ธ ๋ชจ๋ธ ๋ง๋ค์๊ณ , ์์ ํ๋ค๊ณ  ์๋ ค์ค๋ค.

```bash
python3 manage.py makemigrations blog
```

์ค์  ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ์ถ๊ฐํ๋ค.

```bash
python3 manage.py migrate blog

// ํ๋ฉด ์๋์ ๊ฐ์ด ๋ฌ๋ค.
Operations to perform:
  Apply all migrations: blog
Running migrations:
  Applying blog.0001_initial... OK
```
