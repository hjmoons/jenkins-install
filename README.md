# jenkins-install
root 권한을 사용하지 못하여 개인계정으로 jenkins를 실행할 필요가 있는 경우 아래와 같이 진행하여 사용할 수 있다.

### jenkins version
```
2.462.2
```

### jenkins 계정 생성
```
useradd jenkins
passwd jenkins
```

### 어플리케이션 디렉토리 권한 설정
```
chown jenkins:jenkins /app
chown jenkins:jenkins /app_log
```
