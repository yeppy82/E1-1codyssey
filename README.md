# E1-1codyssey

## 📌 프로젝트 소개
codyssey1-1 과제를 위한 웹 서버 프로젝트입니다.
## 💻 실행 환경
- OS: Windows 10/11
- Shell: PowerShell / WSL(Ubuntu)
- Python: 3.14
- Git: 2.55.0.windows .3

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

- [ ] Windows에서 WSL2 Ubuntu가 실행되는지 확인한다.
- [ ] 현재 사용 중인 리눅스 배포판이 Ubuntu인지 확인한다.
- [ ] Shell 종류를 확인한다.
- [ ] 터미널 프로그램을 확인한다. 예: Windows Terminal, VSCode Terminal.
- [ ] Git이 설치되어 있는지 확인한다.
- [ ] Docker가 WSL2에서 동작하는지 확인한다.
- [ ] Docker 데몬이 정상 실행 중인지 확인한다.
- [ ] 확인 결과를 README의 “실행 환경” 섹션에 기록한다.
  ## 실행 환경

### 시스템 정보
- **OS**: Windows (WSL2)
- **Linux 배포판**: Ubuntu 26.04.1 LTS (Codename: resolve)
- **Shell**: /bin/bash
- **Terminal**: Windows Terminal / PowerShell

### 개발 도구
- **Git**: ✅ 설치됨
- **Docker**: ✅ 29.9.3 (build 5457199)
- **Docker Desktop**: ✅ 실행 중 (RAM 2.21GB 할당)

### 확인 날짜
- 2026-03-01

### 확인 명령어
```bash
lsb_release -a          # Ubuntu 26.04.1 LTS
echo $SHELL             # /bin/bash
docker --version        # Docker version 29.9.3
docker ps               # ✅ 정상 연결
