
```bash
docker build -t hsboo/market-app:1.0 .
docker push hsboo/market-app:1.0

# health 체크 기능을 추가한 후에 이미지 다시 build 해서 push 하기
docker build -t hsboo/market-app:1.1 .
docker push hsboo/market-app:1.1

```