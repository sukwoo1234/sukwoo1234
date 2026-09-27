# Shin Suk-Woo

**Security Researcher**

AI Security · Vulnerability Research · Fuzzing

AI 모델 공급망 보안과 소프트웨어 취약점을 연구합니다.  
신뢰할 수 없는 입력이 실제 런타임에서 어떤 문제를 만드는지 직접 재현하고,
원인을 분석해 반복 가능한 검증 도구와 절차로 만드는 데 관심이 있습니다.

[Portfolio](https://balsam-handsaw-01b.notion.site/3d376f9245f9815682d7d8d1be0663c5) · [Email](mailto:wind6712@hanmail.net)

---

## 주요 프로젝트

### [FuzzGate](https://github.com/sukwoo1234/fuzzgate)

외부 AI 모델 파일의 파싱·로딩 경로를 검증하는 Format-Aware Fuzzing 도구입니다.

`Rust` · `AFL++` · `libFuzzer` · `gdb`

- ONNX / safetensors / GGUF 포맷 지원
- 퍼징 실행 → 재현 검증 → triage → report 파이프라인
- ONNX 로더·shape inference 크래시 후보 2건 분석, huntr 심사 중(보안 영향 검토 중)
- 재현 절차와 영향 분석 자료를 포함해 huntr에 제보, 현재 검토 중
- CISC-S 2026 제1저자 연구

### [청대 시그널](https://github.com/sukwoo1234/cheongdae-signal)

청주대학교 학생을 대상으로 직접 기획·개발·배포한 교내 매칭 웹 서비스입니다.

`Next.js` · `TypeScript` · `Supabase` · `PostgreSQL`

- 학교 이메일 기반 가입 자격 검증
- 인증·인가 및 관리자 권한 분리
- PostgreSQL RLS / column-level permissions 설계
- `SECURITY DEFINER` RPC를 이용한 민감 데이터 접근 경계 구성
- 공개 anon key와 사용자 JWT를 이용한 직접 PostgREST 보안 검증
- Vercel 기반 실제 배포·운영

---

## 연구

**2026**  
AI 모델 공급망 보안을 위한 Format-Aware Fuzzing 기반 검증 아키텍처 FuzzGate  
*CISC-S 2026 · 제1저자*

**2026**  
유무선 네트워크 환경에 따른 Google reCAPTCHA v2의 취약점 분석  
*CISC-S 2026 · 제1저자*

**2026**  
상수시간으로 구현된 BCH 기반 퍼지추출기의 타이밍 공격 취약성 실험 분석  
*JKIISC · 공저*

---

## 관심 분야

- AI Model Supply Chain Security
- Fuzzing / Vulnerability Research
- Application Security
- Authentication / Authorization
- Security Automation
