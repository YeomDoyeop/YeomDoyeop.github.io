# AI 엔지니어 염도엽 (@YeomDoyeop)

PyTorch·YOLO 모델 학습부터 LLM 서비스 풀스택 개발까지 경험한 AI 엔지니어입니다.
프로젝트 기획과 프롬프트 설계, DB 연동을 맡아 영상 요약 서비스와 커리어 포트폴리오 서비스를 팀 프로젝트로 완성했습니다.

**관심 분야:** LLM 에이전트 · 컴퓨터 비전(YOLO, OCR) · AI 서비스 풀스택

[GitHub](https://github.com/YeomDoyeop) · 📄 [이력서 PDF 다운로드](resume.pdf) · 🎓 부산대학교 정보컴퓨터공학부

---

## 기술 스택

| 분류 | 기술 |
|---|---|
| Language | Python, C, C++, Kotlin, JavaScript, TypeScript |
| Framework | PyTorch, TensorFlow Lite, React, Next.js, FastAPI |
| AI | Gemini, Codex, Claude Code |
| DB | Supabase, Firebase |
| Infra | Vercel |

## 핵심 역량

- **LLM 활용:** 문맥 요약 프롬프트 설계
- **백엔드:** FastAPI·Next.js, Supabase DB 연동
- **문제 해결:** 서버리스 환경의 PDF 변환을 별도 워커로 해결
- **협업:** GitHub 이슈·PR 기반 팀 개발 (3인, 6인 팀)
- **기획:** 졸업과제와 학교 프로젝트에서 아이디어 제시 및 구상

---

## 대표 프로젝트

### AI 라이브 스트리밍 롱폼 요약 서비스
`2026.05.01 ~ 2026.10.01` · 3인 팀 · 졸업과제

긴 YouTube 방송의 핵심 구간을 AI로 추천해, 자막이 포함된 롱폼 영상으로 만들어 주는 서비스입니다.

**문제 정의**

수 시간 길이의 라이브 방송은 다시 보기 부담이 커서, 시청자는 핵심 장면을 찾기 어렵고 편집자는 하이라이트 영상을 만드는 데 많은 시간을 씁니다.
방송의 문맥을 이해해 볼 만한 구간을 자동으로 골라내는 것이 목표였습니다.

**역할**

- 서비스 기획
- LLM 프롬프트 설계 (문맥 요약)
- 영상 길이 파라미터 튜닝
- Supabase DB 연동
- 편집 에이전트 구성

**기술**

Python · JavaScript · FastAPI · React · Supabase · LLM API

**결과**

긴 방송 URL을 입력하면 AI가 핵심 구간을 추천하고, 자막이 포함된 롱폼 영상까지 생성하는 흐름을 3인 팀으로 완성했습니다.

"3시간 방송 → 30분 롱폼 영상 자동 생성"

**링크**

[스트리밍 자동 편집 서비스 소스 코드](https://github.com/pnucse-capstone2026/capstone-2026-team-10)

· [데모 영상](https://www.youtube.com/watch?v=EX_gG5MmzW8)

---

## 그 외 프로젝트

### KodeKorea BP Project
`2026.09.18 ~ 2026.11.27 (예정)` · 1인

도면의 주요 치수 BBOX를 추출하고 OCR로 읽어 치수성적서를 자동으로 만드는 서비스

- **기술:** Python, PyTorch, YOLO, LLM API
- **역할:** YOLO 모델 학습, LLM API 연동, 에이전트 구현
- [GitHub](https://github.com/YeomDoyeop/KodeKorea__BP_Project)

### Myfitfolio — 직무 맞춤형 포트폴리오 서비스
`2026.06.29 ~ 2026.07.10` · 6인

활동 자료를 AI로 분석해 직무 맞춤형 포트폴리오와 활동 추천을 제공하는 웹 서비스

- **기술:** Next.js, React, Express, Supabase, OpenAI API
- **역할:** 포트폴리오 관리·DB 연동, PDF 변환 워커(서버리스 한계를 별도 워커로 해결), Google OAuth 인증
- [GitHub](https://github.com/pnu-camp-2026-S/team3_career)

### 이미지 분석을 통한 식당 추천 모바일 앱
`2025.05.01 ~ 2025.06.20` · 2인

음식 사진을 넣으면 어떤 음식인지 분석하고, 해당 음식을 파는 주변 식당을 추천하는 모바일 앱

- **기술:** Kotlin, XML, TensorFlow Lite, Firebase, Google Maps API
- **역할:** 기획, Firebase DB 연동, Google Maps API 연동
- [GitHub](https://github.com/HSHwan/eat-play-together)
