# spring-auth
sparta-spring-auth

## 버전 정보

| 항목 | 버전 |
|------|------|
| Java | 17 |
| Spring Boot | 3.4.1 |
| MySQL | 8.0 |
| JWT (jjwt) | 0.11.5 |

### MySQL 컨테이너 실행

```bash
docker run -d \
  --name mysql \
  -e MYSQL_ROOT_PASSWORD=1234 \
  -e MYSQL_DATABASE=auth \
  -p 3306:3306 \
  mysql:8.0
```