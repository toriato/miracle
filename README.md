miracle
---
대충 홈 서버로 굴리는 [vmm.pw](https://vmm.pw) 호스트의 도커 컴포즈 파일

과거에 [selfhosted](https://github.com/toriato/selfhosted) 라는 이름으로 올린 적이 있었지만 수 많은 실수와 토큰, 아이피 유출 등 바보 멍청이 짓으로 상처를 입고 `.git` 디렉터리를 싹 날린 뒤 처음부터 다시 뜯어 고쳤음...

## 네트워크

### 내부 기본 CIDR
- 172.24.0.0/16 (255.255.0.0)
