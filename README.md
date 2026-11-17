# E1-1codyssey

## 📌 프로젝트 소개
codyssey1-1 과제를 위한 웹 서버 프로젝트입니다.
## 💻 실행 환경
- OS: Windows 11
- Shell: PowerShell / WSL(Ubuntu)
- Python: 3.14
- **Git (Windows)**: 2.55.0.windows.3
- **Git (Ubuntu/WSL)**: 2.53.0

## ⚙️ 환경 설치
1. Git 설치
   - https://git-scm.com 에서 다운로드 후 설치

2. Python 설치
   - https://python.org 에서 다운로드 후 설치

3. 저장소 클론
4. Git 사용자 정보 설정
## 📁 폴더 구조
E1-1codyssey/
├── src/          # 소스 코드
├── logs/         # 로그 파일
├── screenshots/  # 스크린샷
└── README.md     # 프로젝트 설명

## ✅ 진행 현황
-  GitHub 저장소 생성
-  폴더 구조 생성 (src, logs, screenshots)
-  README.md 작성
-  학교/집 컴퓨터 Git 환경 설정
-  GitHub 연동 완료
-  웹 서버 구현 (예정)
  ## 터미널 조작 실습
1. 환경 확인 단계 진

- [x]Windows에서 WSL2 Ubuntu가 실행되는지 확인한다.
- [X] 현재 사용 중인 리눅스 배포판이 Ubuntu인지 확인한다.
- [X] Shell 종류를 확인한다.
- [X] 터미널 프로그램을 확인한다. 예: Windows Terminal, VSCode Terminal.
- [X] Git이 설치되어 있는지 확인한다.
- [X] Docker가 WSL2에서 동작하는지 확인한다.
- [x] Docker 데몬이 정상 실행 중인지 확인한다.
- [x] 확인 결과를 README의 “실행 환경” 섹션에 기록한다.
  ## 실행 환경

### 시스템 정보
- **OS**: Windows 11 (WSL2)
- **Linux 배포판**: Ubuntu 26.04.1 LTS
- **Shell**: Bash (/bin/bash)
- **Terminal**: VS Code 통합 터미널 / Windows PowerShell
- **IDE**: Visual Studio Code

### 개발 도구

- **Python**: 3.14.4
- **Git (Ubuntu)**: 2.53.0
- **Docker**: 29.9.2 (build a82e528)
- **Docker Desktop**: 실행 중
- **Docker Engine**: 정상 연결 확인

### 확인 명령어

실행 환경 확인을 위해 다음 명령어를 사용하였다.

**1. Ubuntu 버전 확인**

```bash
lsb_release -a
```

확인 결과: Ubuntu 26.04.1 LTS

**2. Shell 확인**

```bash
echo $SHELL
```

확인 결과: /bin/bash

**3. Python 버전 확인**

```bash
python3 --version
```

확인 결과: Python 3.14.4

**4. Git 버전 확인**

```bash
git --version
```

확인 결과: git version 2.53.0

**5. Docker 버전 확인**

```bash
docker --version
```

확인 결과: Docker version 29.9.2, build a82e528

**6. Docker Engine 연결 확인**

```bash
docker info
```

확인 결과:
- Docker Client 정상 확인
- Docker Server 정보 출력 확인
- Docker Engine 연결 확인

####  Git 병합 충돌 해결
- **상황**: 로컬과 GitHub에서 동시에 README.md 수정
- **원인**: 협업 환경에서 같은 파일을 두 곳에서 수정
- **해결 방법**:
  1. VS Code에서 충돌 부분 확인
  2. 중복 내용 정리 및 수동 병합
  3. `git add README.md` 실행
  4. `git commit -m "fix: README.md 병합 충돌 해결"` 커밋
  5. `git push origin main` 푸시
- **결과**: ✅ 로컬-GitHub 동기화 완료

####  학습 내용
-Git 충돌은 협업 과정에서 발생할 수 있다.
-충돌 해결은 로컬에서 수정한 후 커밋 및 푸시하는 순서로 진행한다.
-향후 예방을 위해 수정 전 원격 저장소와 동기화한다.
---

### ✅ 환경 설정 체크리스트
- [x] Windows에서 WSL2 Ubuntu 설정 확인
- [x] 현재 사용 중인 리눅스 배포판이 Ubuntu 확인
- [x] Git 설치 및 버전 확인
- [x] Python 설치 및 버전 확인
- [x] Docker 설치 및 실행 확인
- [x] GitHub 저장소 생성 및 연동
- [x] README.md 작성
- [x] Git 병합 충돌 해결

####터미널 기본 조작 실습
본 실습은 Windows PowerShell을 사용하여 프로젝트 디렉토리 확인, 파일 목록 조회, 디렉토리 이동, 파일 생성 및 파일 내용 확인을 진행하였다.

 1️⃣ 현재 위치 확인 (pwd)
pwd
실행결과
C:\Users\yeppy829155\Desktop\E1-1codyssey

 2️⃣ 일반 파일 목록 확인 (ls)
 ls
 실행결과
디렉터리: C:\Users\yeppy829155\Desktop\E1-1codyssey
docs
logs
src
README.md

 3️⃣ 숨김 파일 포함 목록 확인 (ls -Hidden)
 ls -Hidden

디렉터리: C:\Users\yeppy829155\Desktop\E1-1codyssey

Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d--h--  2026-11-16  오후 8:24                   .git

 4️⃣ src 폴더로 이동 (cd src)
cd src
pwd
실행결과
C:\Users\yeppy829155\Desktop\E1-1codyssey\src

 5️⃣ 파일 생성 (New-Item hello.txt -ItemType File)
New-Item hello.txt -ItemType File

디렉터리: C:\Users\yeppy829155\Desktop\E1-1codyssey\src

Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----  2026-11-16  오후 8:46                0 hello.txt


  6️⃣ 파일에 내용 작성 (echo & 리다이렉션)

**파일에 텍스트 작성:**
 echo "Hello, WSL2!" > hello.txt

 7️⃣ 파일 내용 확인 (cat)

**파일 내용 출력:**
cat hello.txt
Hello, WSL2!


  8. 실습 결과 및 학습 내용

| 명령어 | 기능 |
|---|---|
| pwd | 현재 작업 위치 확인 |
| ls | 파일 및 디렉토리 목록 확인 |
| ls -Hidden | 숨김 파일 확인 |
| cd | 디렉토리 이동 |
| New-Item | 새 파일 생성 |
| echo | 문자열 출력 및 파일 기록 |
| > | 출력 결과를 파일에 저장 |
| cat | 파일 내용 확인 |

실습을 통해 PowerShell의 기본 파일 및 디렉토리 관리 명령어를 익혔다.