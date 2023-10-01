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
- drf에서 지원하는 라이브러리를 사용했습니다. 지원하는 라이브러리를 사용하면 좋은점이 간단하게 사용할수있기 때문입니다.

4. rest_framework.authtoken의 토큰과 jwt의 토큰의 차이점
- drf_token은 서버측에서 토큰을 관리하고 jwt는 모든 정보가 토큰 자체에 포함되어있어 서버측에서 관리를 안해도 되어서 서버 부담이 안됩니다.


5. django_ratelimit를 사용한 이유는 뭔가요?
- 특정 뷰 함수에 대해서 요청 제한을 설정해야되는 상황이여서 사용하였습니다.

6. apscheduler를 사용한이유
- Schedule 라이브러리도 있긴하지만 apscheduler이 더 유연한 스케줄링 라이브러리라서 apscheduler를 사용했습니다.

# 출처
- 블로그: https://hyun-am-coding.tistory.com/entry/%EC%99%9C-Django%EC%97%90%EC%84%9C-PostgreSQL%EC%9D%84-DB%EB%A1%9C-%EC%82%AC%EC%9A%A9%ED%95%A0%EA%B9%8C
- django.contrib.postgres: https://docs.djangoproject.com/en/3.0/ref/contrib/postgres/