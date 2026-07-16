# Hi there, I'm Sukwoo Shin 👋

**안전한 아키텍처를 설계하고 생산성을 최적화하는 시스템 엔지니어**입니다.  
공격자의 시각으로 시스템의 취약점을 찾아내고, 이를 설계 단계에서 차단하는 견고한 백엔드 구조를 구축하는 데 관심이 많습니다.

### 💡 About Me
- 🛡️ **Security & Engineering:** 단순한 기능 구현을 넘어 메모리 안전성과 논리적 결함 방지를 고려한 로우레벨 시스템을 설계합니다.
- ⚙️ **Automation & Productivity:** Rust와 AI CLI 에이전트를 적극 활용하여 개발 생산성을 높이고, 핵심 로직 검증에 집중합니다.
- 🎯 **Interest:** Format-Aware Fuzzing, Post-Quantum Cryptography (PQC), Side-Channel Analysis (TVLA), CTF
- 🚀 **Build & Ship:** 도구든 서비스든, 설계 문서부터 배포·운영까지 직접 끝냅니다.

---

### 🛠️ Tech Stack

**Languages**  
<img src="https://img.shields.io/badge/C%2F%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
<img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)]()

**Infrastructure & Tools**  
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Linux_WSL-FCC624?style=for-the-badge&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">

---

### 🚀 Key Projects

- **[FuzzGate](https://github.com/sukwoo1234/new-bugbounty)** — AI 모델 포맷 퍼저 (Rust)
  * ONNX / safetensors / GGUF 로더의 메모리 안정성을 검증하는 Format-Aware Fuzzing 플랫폼 **단독 개발**
  * 포맷 인지 변이 → 타깃 하네스 실행 → 3회 재현 검증 → 취약점 등급화 → 자동 리포트 파이프라인
  * SARIF / SIEM 이벤트 출력으로 기존 DevSecOps·보안 관제 파이프라인 통합 지원
  * 논문에서 제안한 아키텍처를 직접 구현해 재현 가능한 크래시 2건 발견, huntr 제보 (심사 중)
    — ONNX Runtime SIGSEGV / ONNX shape inference SIGFPE

- **[청대 시그널](https://github.com/sukwoo1234/cheongdae-signal)** — 교내 매칭 웹 서비스 (TypeScript)
  * Next.js + Supabase 기반. 설계 문서 작성부터 배포·운영까지 단독 수행
  * 학교 이메일 인증 기반 가입 통제, 미들웨어 라우트 보호, 관리자 권한 분리
  * Vercel 자동 배포 · 운영 중 → https://cheongdae-signal.vercel.app

- **[Iris Feature Extraction API]**
  * CNN(ArcFace) 기반 3488-bit 홍채 특징 추출 모듈 개발 및 API 서버 통합

---

### 📄 Publications

- **[제1저자]** AI 모델 공급망 보안을 위한 Format-Aware Fuzzing 기반 검증 아키텍처 FuzzGate
  — 한국정보보호학회 CISC-S 2026
- **[제1저자]** 유무선 네트워크 환경에 따른 Google reCAPTCHA v2의 취약점 분석 연구
  — 한국정보보호학회 CISC-S 2026
- **[공저]** 상수시간으로 구현된 BCH 기반 퍼지추출기의 타이밍 공격 취약성 실험 분석
  — 정보보호학회논문지(JKIISC), 2026

  ---

### 📫 Contact
- **Email:** wind6712@hanmail.net
