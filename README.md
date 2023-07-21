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
![](https://velog.velcdn.com/images/seatrea/post/9fbf028f-1c4a-4b04-8269-5571e0c059b4/image.png)

---
## 5. 실행 화면
- 메인 페이지
![](https://velog.velcdn.com/images/seatrea/post/e2480544-5e24-4e33-b79e-f16c5163df00/image.png)

- 회원가입 페이지
![](https://velog.velcdn.com/images/seatrea/post/36260a5d-1f18-49b4-a777-8940e2bdb4ab/image.png)

- 로그인 페이지
![](https://velog.velcdn.com/images/seatrea/post/7262d0e2-42e6-4cf5-98a1-ba0830b748ed/image.png)

- 게시글 전체 목록 페이지
![](https://velog.velcdn.com/images/seatrea/post/f6525611-c28f-41f5-8164-e1d9bc7197f4/image.png)

- 게시글 작성 페이지
![](https://velog.velcdn.com/images/seatrea/post/3668f66d-e974-49a9-8a4e-4eb242cc15c2/image.png)

- 게시글 상세 조회 페이지
![](https://velog.velcdn.com/images/seatrea/post/4676e6ea-e06e-48ac-bf6e-6826a9091141/image.png)

---

## 6. 느낀점
- 처음 계획할 때에는 실제 개인 블로그처럼 개발하고 싶었는데, 개발 범위의 욕심을 너무 크게 내서 기한 내에 제대로 된 구현을 하지 못해 기한 내에 보여지는 부분이 적어 아쉬웠습니다.
- 시간에 쫓기다 보니 코드가 지저분해져서 후에 리팩토링이나 다시 진행해보고 싶습니다.
- 다음에 프로젝트 계획을 진행할 때에는 기한 내에 개발을 완료할 수 있도록 범위 설정을 잘 해야 겠다는 생각을 했습니다.
