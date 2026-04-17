# 🚀 고등학생 AI 교육 프로그램 (2026)

**대상**: 고등학생 (프로그래밍 초보~중급)  
**기간**: 4회차 ~ 9회차 (5월 ~ 8월)  
**환경**: GitHub Codespaces + Jupyter Notebook  
**기술 스택**: Python, Azure OpenAI SDK, LangChain  

---

## 📁 프로젝트 구조

```
ai-workshop/
├── session-04-ai-basics/          # 4회차 (5/16) — AI 기초 이론
│   ├── slides/                    #   PPT 자료
│   ├── notebooks/                 #   실습 노트북
│   └── homework/                  #   숙제: 프롬프트 마스터 챌린지
│
├── session-05-ai-programming/     # 5회차 (5/30) — AI 프로그래밍 실습
│   ├── slides/                    #   PPT 자료
│   ├── notebooks/                 #   실습 노트북
│   └── homework/                  #   숙제: 나만의 AI 챗봇 (Gradio)
│
├── session-06-agent-v1/           # 6회차 (7/11) — AI 에이전트 개발 1차
│   ├── slides/                    #   PPT 자료
│   ├── notebooks/                 #   실습 노트북
│   └── homework/                  #   숙제: 꼬맨틀 클론 만들기
│
├── session-07-agent-v2/           # 7회차 (7/18) — AI 에이전트 개발 2차
│   ├── slides/                    #   PPT 자료
│   ├── notebooks/                 #   실습 노트북
│   └── homework/                  #   숙제: AI 학교 생활 도우미
│
├── session-08-hackathon/          # 8회차 (8/8) — 해커톤
│   ├── guides/                    #   디자인 싱킹 가이드, 평가 기준
│   └── templates/                 #   해커톤 프로젝트 템플릿
│
├── session-09-pinecon/            # 9회차 (8/22) — P.I.N.E CON AI 축제
│
├── .devcontainer/                 # Codespace 환경 설정
├── assets/                        # 공용 이미지/자료
├── docs/                          # APIM 설정 가이드 등 인프라 문서
├── AI_커리큘럼_개괄자료.md          # 커리큘럼 전체 개괄
└── requirements.txt               # Python 패키지 목록
```

## 📅 회차별 요약

| 회차 | 날짜 | 주제 | 숙제 |
|------|------|------|------|
| 4회차 | 5/16 | AI 기초 이론 | 프롬프트 마스터 챌린지 |
| 5회차 | 5/30 | AI 프로그래밍 실습 | 나만의 AI 챗봇 (Gradio) |
| 6회차 | 7/11 | AI 에이전트 개발 1차 | 꼬맨틀 클론 만들기 |
| 7회차 | 7/18 | AI 에이전트 개발 2차 | AI 학교 생활 도우미 |
| 8회차 | 8/8  | 해커톤 | - |
| 9회차 | 8/22 | P.I.N.E CON AI 축제 | - |

## 🛠️ 실습 환경

- **Azure OpenAI**: APIM 프록시를 통한 Managed Identity 인증
- **Gateway**: `https://apim-ai-workshop-010.azure-api.net`
- **모델**: gpt-4.1-mini, gpt-5-mini, gpt-5.4-mini, text-embedding-3-large
