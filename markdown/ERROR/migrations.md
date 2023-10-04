- django와 postgreSQL 연결후 migrate에러
- 원인 : 아래와 같은 오류 발생
```
django.db.migrations.exceptions.InconsistentMigrationHistory: Migration admin.0001_initial is applied before its dependency user.0001_initial on database 'default'.
```

- 해결방법 : SQL문으로 삭제
```
DROP SCHEMA public CASCADE;
CREATE SCHEMA public;
```