# troubleshooting-for-aa

### 상황
- `troubleshooting` 앱 이미지를 빌드하여 `cepgbaseacr.azurecr.io` ACR에 푸시를 완료했습니다.
- 이제 `troubleshooting` 이미지를 쿠버네티스 환경에 파드로 배포하고, 웹 URL을 통해 접속을 확인하려고 합니다.
  

### 목표
1. 자신의 사번 네임스페이스에 `cepgbaseacr.azurecr.io/troubleshooting:latest` 이미지를 배포하세요.
2. 웹 URL을 통해 자신이 배포한 애플리케이션에 접속할 수 있도록 구성하세요.

### 방법
- 현재 저장소의 매니페스트 파일을 받아서 진행해 주세요.
- 문제 상황이 발생하면 매니페스트 파일을 수정하여 해결해 주세요.
