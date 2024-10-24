## 소개

Dockerfile, docker-compose 만 이용해 Prometheus, Grafana를 컨테이너에 올리는 예제입니다.

## 방법

### 기본 정보
Grafana 에서 매개 변수를 입력받을 수 있도록 설계했습니다.

- id > admin
- pw > admin
- port > default

### docker compose
공인 이미지로 하시려면 `docker-compose-without-dockerfile.yml` 을<br>
설정 커스터마이징한 이미지를 사용하시려면 `docker-compose-custom.yml` 을 이용하시면 됩니다.

```bash
# v2 Docker engine
## original
docker compose -f docker-compose-original.yml up -d

## custom
docker compose -f docker-compose-custom.yml up -d
```