# Git 기초 정리

##  Git이란?

Git은 **분산 버전 관리 시스템(DVCS)**으로, 코드 변경 사항을 추적하고 여러 사람이 협업할 수 있게 도와줍니다.

## 설치 방법

- [Git 공식 사이트](https://git-scm.com/downloads)에서 운영체제에 맞게 다운로드 후 설치

- 설치 확인:  
  
  ```bash
  git --version
  ```

## 기본 설정

- git config --global user.name "Your Name"

- git config --global user.email "you@example.com"


## git bash

## 기본 명령어
| 기능          | 명령어                            |
| ----------- | ------------------------------ |
| Git 저장소 초기화 | `git init`                     |
| 상태 확인       | `git status`                   |
| 변경 사항 추적    | `git add .` 또는 `git add <파일명>` |
| 커밋          | `git commit -m "메시지"`          |
| 로그 보기       | `git log`                      |
| 원격 저장소 연결   | `git remote add origin <url>`  |
| 푸시          | `git push -u origin main`      |
| 클론          | `git clone <url>`              |


## Git Local and Remote Repository
![alt text](image.png)