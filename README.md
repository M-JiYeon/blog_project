# Django blog
---
## 1. 목표와 기능
### 1.1. 목표
- Django를 활용하여 blog의 CRUD 기능 구현을 목표로 합니다.
### 1.2. 기능
- 회원가입 기능
- 로그인 기능
- 로그아웃 기능
- 게시글 작성
- 게시글 전체 목록 조회
- 게시글 상세 조회
- 게시글 수정
- 게시글 삭제
- 댓글 작성
- 댓글 삭제
---
## 2. 개발 환경 및 개발 일정
### 2.1. 개발 환경
- Django 4.2.2
- Python 3.11.3
### 2.2. 개발 일정
- 2023.07.17 ~ 2023.07.20
---
## 3. 프로젝트 구조
```
├── README.md
├── app
│   ├── __init__.py
│   ├── __pycache__
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   └── wsgi.py
├── blog
│   ├── __init__.py
│   ├── __pycache__
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── migrations
│   ├── models.py
│   ├─templates
│  		└─blog
│          ├──form_error.html
│          ├──post_detail.html
│          ├──post_edit.html
│          ├──post_form.html
│          └──post_list.html
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── db.sqlite3
├── manage.py
├── templates
│   ├── base.html
│   └── index.html
├── user
│   ├── __init__.py
│   ├── __pycache__
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── migrations
│   ├── models.py
│   ├── templates
│   	├──user
│          ├──user_login.html
│          └── user_register.html
│   ├── tests.py
│   ├── urls.py
│   └── views.py
└── venv
```

---
## 4. 데이터베이스 모델링(ERD)
![](https://velog.velcdn.com/images/seatrea/post/0279c49c-5c2e-4129-b484-d6cda1ea70c0/image.png)

---
## 5. 실행 화면
- 메인 페이지

![](https://velog.velcdn.com/images/seatrea/post/dbf1ec98-2e1c-42a7-b242-aec2889c3548/image.png)

- 회원가입 페이지

![](https://velog.velcdn.com/images/seatrea/post/fefc9d45-5229-4c5d-b10c-73775648d3b8/image.png)

- 로그인 페이지

![](https://velog.velcdn.com/images/seatrea/post/d966680b-a6fa-49b2-b51b-f8a409ee50c6/image.png)

- 게시글 전체 목록 페이지

![](https://velog.velcdn.com/images/seatrea/post/7dd95b0f-4a22-46e8-ab4a-37346c48d922/image.png)

- 게시글 작성 페이지

![](https://velog.velcdn.com/images/seatrea/post/a43ce001-ef44-4bf1-8332-e45018f11336/image.png)

- 게시글 상세 조회 페이지

![](https://velog.velcdn.com/images/seatrea/post/bbcf490b-763b-4538-91b8-2cec480c02f9/image.png)

- 게시글 수정 페이지

![](https://velog.velcdn.com/images/seatrea/post/67fb9c75-8e72-4146-a9ce-6e3a3d636449/image.png)

---

## 6. 느낀점
- 처음 계획할 때에는 실제 개인 블로그처럼 개발하고 싶었는데, 개발 범위의 욕심을 너무 크게 내서 기한 내에 제대로 된 구현을 하지 못해 기한 내에 보여지는 부분이 적어 아쉬웠습니다.
- 시간에 쫓기다 보니 코드가 지저분해져서 후에 리팩토링이나 다시 진행해보고 싶습니다.
- 다음에 프로젝트 계획을 진행할 때에는 기한 내에 개발을 완료할 수 있도록 범위 설정을 잘 해야 겠다는 생각을 했습니다.
