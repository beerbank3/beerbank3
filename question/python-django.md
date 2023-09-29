# Python Django 이력서 질문 대비

1. Django를 사용하면서 DB로 PostgreSQL를 사용한 이유
    1. PostgreSQL이란?
    - PostgreSQL이란 확장 가능성 및 표준 준수를 강조하는 객체-관계형 데이터베이스 관리 시스템(ORDBMS)의 하나
    2. Django에서 PostgreSQL을 사용하는 이유
    - Django는 PostgreSQL에서만 작동하는 여러 데이터 유형을 제공
    - 지도를 사용하여 애플리케이션을 구축하거나 지리적 데이터를 저장하는 경우 GeoDjango는 PosgreSQL과 완벽하게 호환할 수 있어서 PostgreSQL을 사용해야 합니다.
    - Django에는 PostgreSQL에서 데이터베이스 작업을 수행하는 django.contrib.postgres

2. Toast UI Editor의 이미지 업로드가 base64형태로 변환
- 비동기로 저장후 파일 이름 반환

3. rest_framework.authtoken를 사용했을때 이점
- 

4. django_ratelimit를 사용한 이유와 다른게 있다면 뭐가있나요?
- 

5. apscheduler를 사용한이유
- 
# 출처
- 블로그: https://hyun-am-coding.tistory.com/entry/%EC%99%9C-Django%EC%97%90%EC%84%9C-PostgreSQL%EC%9D%84-DB%EB%A1%9C-%EC%82%AC%EC%9A%A9%ED%95%A0%EA%B9%8C
- django.contrib.postgres: https://docs.djangoproject.com/en/3.0/ref/contrib/postgres/