# Linux CLI Development Workstation

## 1. 프로젝트 소개
Linux CLI, Docker, Git, GitHub를 활용하여 개발 워크스테이션 환경을 구축하고 실습한 프로젝트입니다.

## 2. 개발 환경
- OS: Windows 11
- Linux: Ubuntu on WSL
- Docker: Docker Desktop
- Docker Image: Ubuntu, Nginx Alpine
- Git: 2.53.0
- GitHub CLI: 2.46.0
- GitHub Account: gitmin45

## 3. 프로젝트 구조
- app/: Dockerfile 및 웹페이지 실습
- bind-mount/: Docker Bind Mount 및 Volume 실습
- cli-practise/: Linux CLI 명령어 및 권한 실습

## 4. 실습 진행 현황
- [x] Linux CLI 파일 및 디렉터리 관리
- [x] Linux 파일 및 디렉터리 권한 변경
- [x] Docker 설치 및 실행 확인
- [x] Docker Hello World 실행
- [x] Ubuntu 컨테이너 실행 및 명령어 실습
- [x] Docker 이미지 생성 및 실행
- [x] Docker Bind Mount 실습
- [x] Docker Volume 데이터 지속성 확인
- [x] Docker 포트 매핑 및 웹브라우저 접속
- [x] Git 설치 및 사용자 설정
- [x] GitHub CLI 설치 및 로그인
- [x] Git 저장소 초기화 및 main 브랜치 설정
- [x] README 작성 및 GitHub 업로드
- [x] VS Code 연동 확인

## 5. Docker 실습 결과

### Custom Docker Image
- Image: my-first-image
- Container: my-first-container
- 실행 결과: Hello from my custom Docker image!

### Bind Mount
- WSL 파일과 Docker 컨테이너 간 파일 공유 확인

### Docker Volume
- 컨테이너 삭제 후 새 컨테이너에서 기존 데이터 확인

### Port Mapping
- Windows Port: 8080
- Container Port: 80
- URL: http://localhost:8080
- 실행 결과: Hello from Docker Port Mapping!

## 6. 문제 해결 기록
1. Docker 명령어 실행 시 Docker 데몬 연결 오류
   - Docker Desktop의 WSL Integration 설정을 확인하여 해결

2. Dockerfile 파일명 오류
   - Docker-file을 Dockerfile로 변경하여 해결

3. Linux 파일 경로 입력 오류
   - 상대 경로와 파일명을 다시 확인하여 해결

4. Git 기본 브랜치 이름
   - master 브랜치를 main으로 변경하여 해결

## 7. 향후 작업
- GitHub 원격 저장소 생성 및 업로드
- VS Code와 GitHub 연동
- 실습 화면 및 결과 자료 정리
