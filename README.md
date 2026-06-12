# NOO
# 🚀 Todo-FastAPI

> FastAPI와 SQLAlchemy를 활용하여 빠르고 안정적으로 동작하는 RESTful 할 일 관리(Todo) API 서버입니다.

---

## 📌 소개 (Introduction)
이 프로젝트는 **사용자의 일정을 효율적으로 관리할 수 있도록 돕는 백엔드 API 서버**입니다. 
현대적인 Python 웹 프레임워크인 FastAPI를 활용하여 비동기 처리를 지원하며, 간결한 코드 구조와 자동 생성되는 대화형 API 문서(Swagger UI)를 제공하는 것에 초점을 맞추어 개발되었습니다.

## ✨ 주요 기능 (Key Features)
* 🔐 **JWT 기반 회원가입 및 로그인**: Secure Password Hashing을 적용한 안전한 사용자 인증을 제공합니다.
* 📝 **할 일(Todo) CRUD 기능**: 할 일 등록, 조회, 수정(완료 여부 체크), 삭제가 가능합니다.
* 📅 **기한 설정 및 우선순위 필터링**: 마감일과 중요도에 따라 할 일 목록을 정렬하고 필터링할 수 있습니다.
* 📖 **자동 API 문서화**: 서버 실행 시 `/docs` 경로를 통해 Swagger UI 문서가 자동으로 생성되어 실시간 테스트가 가능합니다.

## 🛠️ 사용 방법 (Getting Started)

### 1. 요구 사항 (Prerequisites)
* Python 3.10 이상 버전이 필요합니다.

### 2. 다운로드 및 설치 (Installation)
저장소를 복제하고 필요한 패키지를 설치합니다.
```bash
git clone [https://github.com/your-username/Todo-FastAPI.git](https://github.com/your-username/Todo-FastAPI.git)
cd Todo-FastAPI

# 가상환경 생성 및 활성화 (선택 사항)
python -m venv venv
source venv/bin/activate  # Windows 환경: venv\Scripts\activate

# 의존성 라이브러리 설치
pip install -r requirements.txt
