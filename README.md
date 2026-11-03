# Jadu AI — 더 똑똑한 자두

자두 데스크톱 캐릭터의 **Gemma 3 1B PC 대화 추가팩**입니다.

자두 메뉴 → **더 똑똑한 자두 만나볼래? → 다운로드·설치**
처음 한 번 GitHub에서 내려받고 이후 대화는 PC에서 처리합니다. API 키는 필요 없습니다. 캐드별 자두가 모델 한 벌을 함께 사용합니다.

- Windows x64, CPU 실행
- 다운로드 약 805 MB / 설치 약 853 MB
- 기본 대화·동작·도움말은 유지하고 모르는 일상 질문을 Gemma가 보충합니다.
- 작은 모델이므로 한국어 문맥·농담에 엉뚱하게 답할 수 있습니다.
- 자두를 종료하면 전용 AI 프로세스도 종료합니다.
- AI 추가팩만 배포하며 자두 본체·KTOOL 소스·사용자 설정·자료는 포함하지 않습니다.

[추가팩 내려받기](https://github.com/KT-SOFT/Jadu-AI/releases/download/gemma3-1b-v1/Jadu-AI-Gemma3-1B-Windows-x64.zip) · [릴리스](https://github.com/KT-SOFT/Jadu-AI/releases/tag/gemma3-1b-v1)

## 구성과 이용 조건

- 변경하지 않은 Google Gemma 3 1B IT Q4_K_M GGUF 가중치
- llama.cpp b11960 Windows CPU 구성요소
- 각 구성요소의 약관·사용 정책·라이선스·NOTICE를 ZIP에 포함합니다.
- Gemma 이용·재배포에는 [Gemma 이용약관](https://ai.google.dev/gemma/terms)과 [사용 정책](https://ai.google.dev/gemma/prohibited_use_policy)이 적용되며 본 배포의 이용·재배포 조건에 포함됩니다.
- [원 모델](https://huggingface.co/google/gemma-3-1b-it) · [GGUF 변환 출처](https://huggingface.co/unsloth/gemma-3-1b-it-GGUF) · [실행 엔진](https://github.com/ggml-org/llama.cpp/releases/tag/b11960)

ZIP SHA-256: `e32341859c12349128491430157c2b4a46ce096979ad13a5c879290e4da0eba9`
