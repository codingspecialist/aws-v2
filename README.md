# AWS 초급 강의 두번째 배포

### Springboot 2.6.6, JDK 11
- devtools
- springweb
- lombok

### 배포 위치 EC2

### 배포 방법
- 개발환경(집컴퓨터)에서 github 업로드
- var.sh check-and-restart.sh deploy.sh 3개 파일 deploy.tar로 압축되어 있음(실행권한 이미 부여됨).
- EC2의 /home/ubuntu 경로로 전송
- tar -xvf deploy.tar
- 프로덕션(EC2)에서 deploy.sh 파일 실행

### 재배포 방법
- 개발환경(집컴퓨터)에서 github 업로드
- 프로덕션(EC2)에서 deploy.sh 파일 실행