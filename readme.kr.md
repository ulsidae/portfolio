# Project Categories Overview

<details>
<summary><strong>1. 프로젝트 유형별 분류 (클릭하여 펼치기)</strong></summary>


> 각 항목의 분류 부분을 클릭하면 해당 카테고리의 상세 내용으로 이동합니다.

| 분류 | 설명 |
| :--- | :--- |
| [⚡️ AI](#1) | AI 관련 연구 및 기술 실험을 수행 시점에 따라 정리했습니다. |
| [⚙️ RSVP-systems](#2) | 학생회 활동 등을 통해 시스템적 사고와 문제 해결 역량을 발전시킨 경험을 정리했습니다. |
| [🔒 Security & Crypto](#3) | 정보보안 및 암호학 관련 기술 탐구와 실험을 정리했습니다. |
| [🚀 Game](#4) | 기획부터 구현까지 주도적으로 참여한 게임 관련 프로젝트를 정리했습니다. |
| [📓 idea-notes](#5) | 일상 속 문제 해결을 위한 개인적인 아이디어와 기술적 실험을 정리했습니다. |
| [📚 Tutorial](#6) | 학습한 기술과 지식을 문서화하고 다른 사람에게 전달하기 위해 제작한 자료를 정리했습니다. |
| [🦀 Web Development](#7) | 주로 Rust를 활용한 웹 기술 구현과 관련 실험 및 설계 과정을 정리했습니다. |
| [🖥️ Server](#8) | 서버 아키텍처와 관련 기술을 탐구하고 구현한 실험들을 정리했습니다. |

---

</details>



<details>
<summary><strong>2. 경험 유형별 분류 (클릭하여 펼치기)</strong></summary>


> 각 항목의 분류 부분을 클릭하면 해당 카테고리의 상세 내용으로 이동합니다.

| 분류 | 설명 |
| :--- | :--- |
| [👥 Collaboration](#a) | 공동 목표 달성을 위해 다른 구성원들과 협력하고 문제를 해결한 경험을 정리했습니다. |
| [🎯 Professional Experience](#b) | 재직 중 수행한 주요 업무와 프로젝트를 NDA 및 기밀유지 의무를 준수하는 범위에서 정리했습니다. |

</details>

---

<h2 id="1">⚡️ AI</h2>

| 순서 |
| :--- | 
| [1 AURIX](#AURIX) | 
| [2 RepoLens](#RepoLens) |  
| [3 cori_tts](#cori_tts) |  

> ---

<h3 id="AURIX">AURIX</h3>

> AURIX는 Automated User Reflection for Intelligent eXperience의 약어로, 자동화된 기능으로 사용자의 편의를 탐구하는 프로젝트입니다.

#### 1. AURIX 이전에 있었던 [Todo Dashboard](https://github.com/ulsidae/dev_logs/blob/main/Frontend%26Client-side/Todo%20Dashboard/index.html):

- Daily Routines, Today's Tasks, Long-Term Goals 기반의 작업 분류 및 관리 기능을 구현했습니다.
- 사용자 3명을 대상으로 [초기 사용성 평가 및 제품 만족도 조사](https://github.com/ulsidae/RSVP-systems/blob/main/%F0%9F%8C%8DFocusBoard%20User-Validation/readme.md)를 진행했습니다.
- 사용자 피드백을 바탕으로 UI, 작업 우선순위, 알림 및 생산성 분석 관련 개선점을 도출했습니다.
- 평가 결과를 기반으로 향후 AI 기반 생산성 분석 시스템으로의 확장 방향을 수립해 AURIX 프로젝트를 시작했습니다.

#### 2. C++로 만들어진 [AURIX](https://github.com/ulsidae/AURIX):

- Todo Dashboard의 사용자 검증 결과를 바탕으로 단순 작업 관리에서 개인의 행동 분석 및 개선을 지원하는 AI Productivity Coach로 프로젝트 방향을 설정했습니다.
- C++ 기반 프로토타입을 개발하며 Local LLM, 로컬 데이터 관리 및 시스템 자원 제어를 실험했습니다.
- 이 과정에서 개발 규모 확장에 따른 유지보수 복잡성, 메모리 안전성 및 보안 관리의 한계 [분석](https://github.com/ulsidae/AURIX/blob/main/old_version/alpha/information.md?plain=1)도 수행했습니다.
- 기존 C++ 구현의 한계를 바탕으로 메모리 안전성과 유지보수성을 고려한 Rust 기반 아키텍처로 전환(=Pivot) 및 후속 개발을 진행했습니다.

#### 3. Rust로 새롭게 시작된 [AURIX for Rust](https://github.com/ulsidae/AURIX-for-Rust):

- Rust 기반의 Privacy-first AI Productivity Coach 및 Local LLM 활용 구조의 프로토타입을 개발했습니다.
- 기존 C++ 프로토타입의 연구 결과를 바탕으로 메모리 안전성, 유지보수성 및 아키텍처 개선을 위한 재설계를 위해 Rust를 선택했습니다.
- 기본 생산성 기능과 사용자 맞춤형 AI 기능을 구분한 무료·유료 서비스 모델 및 사업화 방향을 수립했습니다.
- 이를 기반으로 하여 Alpha 프로토타입 공개를 통한 기술적 가능성 검증, 개발 과정 문서화 및 초기 사용자 피드백을 확보했습니다. (추후 관련 문서 추가 예정)

> ---

<h3 id="RepoLens">RepoLens</h3>

> [RepoLens](https://github.com/ulsidae/RepoLens/tree/main)는 GitHub 데이터를 기반으로 개발자 및 PM 관점의 포트폴리오를 분석·평가하고, 진단 및 개선을 지원하기 위해 개발한 AI 기반 분석 도구입니다.

- GitHub 프로필 및 공개 저장소의 README를 수집·분석하는 AI 기반 포트폴리오 분석 도구인 RepoLens 개발했습니다.
- 수집한 데이터를 구조화된 프롬프트로 변환하여 PM 및 개발자 관점의 포트폴리오 평가 기능을 구현했습니다.
- Google Gemini API와 Ollama를 연동하여 클라우드 및 로컬 AI 추론 환경을 지원하도록 설계했습니다.
- 저장소별 분석, 개선점 도출, LinkedIn 게시글 초안 생성 및 다국어 보고서 출력 기능을 구현했습니다.
- Streamlit 기반 웹 인터페이스를 구축하고 Streamlit Community Cloud를 통해 온라인 서비스 배포 역시 수행했습니다.

> ---

<h3 id="cori_tts">cori_tts</h3>

> [cori_tts](https://github.com/ulsidae/cori_tts)는 Piper TTS를 기반으로 음성 합성 과정의 기술적 진입장벽을 낮추고, 비전문가도 쉽게 사용할 수 있는 환경을 제공하기 위해 개발한 UX 중심의 TTS wrapper입니다.

- Piper TTS를 기반으로 텍스트 파일을 음성으로 변환하는 Windows용 TTS wrapper를 개발했습니다.
- GUI 기반 인터페이스를 구현하여 모델 선택 및 음성 합성 과정의 사용 편의성 개선을 시도했습니다.
- Piper TTS의 upstream 개발자와 프로젝트 구조 및 GPL 라이선스 관련 문의를 진행하고 오픈소스 호환성을 검토했습니다.

---

<h2 id="2">⚙️ RSVP-systems</h2>

| 순서 |
| :--- | 
| [1  System Thinking](#System_Thinking) | 
| [2 Re-engineered Academic Work](#Re-engineered_Academic_Work) |  
| [3 Problem Solving (Coding Tests)](#Problem_Solving)) |  

> ---

> TODO: 이어서 작성할 것. 


---

<h2 id="a">👥 Collaboration</h2>

### 1.학생회 경험 
> 대학교 학생회 활동을 하며 협업, 우선순위 조정 등 여러가지 경험을 쌓았습니다.
<details>
<summary><strong>학생회에서 한 일들 (클릭하여 펼치기)</strong></summary>
  
</details>

### 2.팀프로젝트 경험 
> 다른 개발자, 디자이너와 함께 개발 프로젝트를 주도적으로 진행한 경험이 있습니다.
<details>
<summary><strong>성과 등 상세 내용 (클릭하여 펼치기)</strong></summary>
  
</details>

### 3.회사 협업 경험 
> 회사에서 업무를 다른 사람들과 수행하면서 역할 분배에 대해 체득했습니다.
<details>
<summary><strong> 역할 분배 관련 글들 확인하기 (클릭하여 펼치기)</strong></summary>
  
</details>

<h2 id="b">🎯 Professional Experience</h2>

### 1.초안을 통한 방향 결정 
> 클라이언트의 요구사항을 화인
<details>
<summary><strong>성과 등 상세 내용 (클릭하여 펼치기)</strong></summary>
  
</details>

### 2.보안을 고려한 설계 
> 대학교 학생회 활동을 하며 협업, 우선순위 조정 등 여러가지 경험을 쌓았습니다.
<details>
<summary><strong>학생회에서 한 일들 (클릭하여 펼치기)</strong></summary>
  
</details>
