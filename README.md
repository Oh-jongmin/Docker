# 🐳 Docker Practice

> 이 저장소는 Docker를 활용한 컨테이너 실습을 정리한 공간입니다.  
> 이미지 빌드, 컨테이너 실행, Dockerfile 작성 등 실습 내용을 포함합니다.

---

## 📁 실습 디렉토리

| 디렉토리 | 설명 |
|----------|------|
| `basic/` | Docker CLI 명령어 실습 (`docker pull`, `run`, `ps`, `logs` 등) |
| `flask-app/` | Flask 웹 앱 컨테이너 빌드 및 실행 실습 (`app.py`, `Dockerfile`) |
| `hello-world/` | Docker 기본 테스트 이미지 실습 |

---

## 📄 주요 파일 설명

| 파일명 | 역할 |
|--------|------|
| `Dockerfile` | Flask 앱을 위한 이미지 빌드 설정 |
| `app.py` | Flask 웹 애플리케이션 |
| `basic.md` | 기본 Docker 명령어 실습 문서 정리 |

---

## 🧪 주요 학습 내용

- `docker pull`, `docker run`, `docker ps`, `docker logs` 등 기본 명령어
- `Dockerfile`을 통한 이미지 커스터마이징
- 포트 매핑 (`-p 8080:80`) 및 백그라운드 실행 (`-d`)
- 컨테이너 삭제, 이미지 관리 (`prune`, `rmi`, `rm`)
- Flask 앱 컨테이너화 실습

---

## ⚙️ 환경 정보

- Docker Desktop (Windows / macOS)
- VSCode + Docker Extension
- PowerShell or Bash

---

## 📌 참고

`Dockerfile`, `.py` 등 실습 코드만 포함
실제 컨테이너 실행은 터미널에서 수동 실행 권장
Docker Hub와 연동은 추후 별도 진행  
[Docker 참고 사이트]  
[Docker 블로그](https://brotherdan.tistory.com/category/%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4%20%EA%B0%9C%EB%B0%9C/Docker)

---

## ✍️ 작성자

**Jongmin Oh**  
📧 dhwhdals2637@gmail.com  
🌐 [GitHub Profile](https://github.com/Oh-jongmin)
