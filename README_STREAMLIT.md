# TU 학습설계 AI 어시스턴트 (Streamlit 버전)

대학생을 위한 AI 기반 학습 설계 및 모듈 추천 시스템입니다.

## 🚀 로컬 실행 방법

### 1. 의존성 설치
```bash
pip install -r requirements.txt
```

### 2. 환경 변수 설정
`.env` 파일을 생성하고 Gemini API 키를 추가하세요:
```
GEMINI_API_KEY=your_api_key_here
```

### 3. 앱 실행
```bash
streamlit run app.py
```

브라우저에서 `http://localhost:8501` 로 접속하세요.

## 📦 Streamlit Cloud 배포 방법

### 1. GitHub에 업로드
```bash
git init
git add app.py requirements.txt .streamlit/
git commit -m "Initial commit"
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main
```

### 2. Streamlit Cloud 배포
1. https://streamlit.io/cloud 접속
2. "New app" 클릭
3. GitHub 저장소 연결
4. Main file: `app.py` 선택
5. Secrets에 `GEMINI_API_KEY` 추가
6. Deploy 클릭

## 🔑 API 키 발급

Google AI Studio에서 Gemini API 키를 발급받으세요:
https://aistudio.google.com/app/apikey

## 📋 주요 기능

- 📊 대시보드: 모듈 이수 현황 및 학점 관리
- 🤖 AI 추천: 개인 맞춤형 학습 경로 추천
- 🔍 모듈 탐색: 다양한 융합 모듈 검색
- 🛒 모듈 카트: 관심 모듈 저장
- ✏️ 모듈 설계: 나만의 융합 모듈 생성
- 📖 학습 이력: 수강 내역 관리

## 🛠️ 기술 스택

- Python 3.8+
- Streamlit
- Google Generative AI (Gemini)

## 📁 파일 구조

```
.
├── app.py                  # 메인 애플리케이션
├── requirements.txt        # Python 의존성
├── .streamlit/
│   └── config.toml        # Streamlit 설정
└── README_STREAMLIT.md    # 문서
```

## 💡 사용 팁

1. AI 추천 기능을 사용하려면 반드시 API 키를 설정해야 합니다
2. 프로필 정보를 상세히 입력할수록 더 정확한 추천을 받을 수 있습니다
3. 모듈 카트에 관심 모듈을 담아 학습 계획을 세워보세요

## 📞 문의

문제가 발생하면 GitHub Issues에 등록해주세요.
