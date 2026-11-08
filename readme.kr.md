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

> AI 관련 연구 및 기술 실험을 수행 시점에 따라 정리했습니다.

> ---

### 📌 추천하는 AI관련 글들

<h3 id="AURIX">AURIX</h3>

<details>
<summary><strong>AURIX는 Automated User Reflection for Intelligent eXperience의 약어로, 자동화된 기능으로 사용자의 편의를 탐구하는 프로젝트입니다. </strong></summary>

#### AURIX 이전

> [Todo Dashboard](https://github.com/ulsidae/dev_logs/blob/main/Frontend%26Client-side/Todo%20Dashboard/index.html):

- Daily Routines, Today's Tasks, Long-Term Goals 기반의 작업 분류 및 관리 기능을 구현했습니다.
- 사용자 3명을 대상으로 [초기 사용성 평가 및 제품 만족도 조사](https://github.com/ulsidae/RSVP-systems/blob/main/%F0%9F%8C%8DFocusBoard%20User-Validation/readme.md)를 진행했습니다.
- 사용자 피드백을 바탕으로 UI, 작업 우선순위, 알림 및 생산성 분석 관련 개선점을 도출했습니다.
- 평가 결과를 기반으로 향후 AI 기반 생산성 분석 시스템으로의 확장 방향을 수립해 AURIX 프로젝트를 시작했습니다.

> [CLI for robi](https://github.com/ulsidae/dev_logs/tree/main/AI/CLI%20for%20robi)

- AURIX C++의 기반이 된 프로젝트입니다.

#### C++로 만들어진 AURIX

> [AURIX](https://github.com/ulsidae/AURIX):

- Todo Dashboard의 사용자 검증 결과를 바탕으로 단순 작업 관리에서 개인의 행동 분석 및 개선을 지원하는 AI Productivity Coach로 프로젝트 방향을 설정했습니다.
- C++ 기반 프로토타입을 개발하며 Local LLM, 로컬 데이터 관리 및 시스템 자원 제어를 실험했습니다.
- 이 과정에서 개발 규모 확장에 따른 유지보수 복잡성, 메모리 안전성 및 보안 관리의 한계 [분석](https://github.com/ulsidae/AURIX/blob/main/old_version/alpha/information.md?plain=1)도 수행했습니다.
- 기존 C++ 구현의 한계를 바탕으로 메모리 안전성과 유지보수성을 고려한 Rust 기반 아키텍처로 전환(=Pivot) 및 후속 개발을 진행했습니다.

#### Rust로 새롭게 시작된 AURIX(진행중):

> [AURIX for Rust](https://github.com/ulsidae/AURIX-for-Rust)

- Rust 기반의 Privacy-first AI Productivity Coach 및 Local LLM 활용 구조의 프로토타입을 개발했습니다.
- 기존 C++ 프로토타입의 연구 결과를 바탕으로 메모리 안전성, 유지보수성 및 아키텍처 개선을 위한 재설계를 위해 Rust를 선택했습니다.
- 기본 생산성 기능과 사용자 맞춤형 AI 기능을 구분한 무료·유료 서비스 모델 및 사업화 방향을 수립했습니다.
- 이를 기반으로 하여 Alpha 프로토타입 공개를 통한 기술적 가능성 검증, 개발 과정 문서화 및 초기 사용자 피드백을 확보했습니다. (추후 관련 문서 추가 예정)

> ---
</details>

<h3 id="RepoLens">RepoLens</h3>

<details>
<summary><strong>RepoLens는 GitHub 데이터를 기반으로 개발자 및 PM 관점의 포트폴리오를 분석·평가하고, 진단 및 개선을 지원하기 위해 개발한 AI 기반 분석 도구입니다. </strong></summary>

> [RepoLens](https://github.com/ulsidae/RepoLens/tree/main)

- GitHub 프로필 및 공개 저장소의 README를 수집·분석하는 AI 기반 포트폴리오 분석 도구인 RepoLens 개발했습니다.
- 수집한 데이터를 구조화된 프롬프트로 변환하여 PM 및 개발자 관점의 포트폴리오 평가 기능을 구현했습니다.
- Google Gemini API와 Ollama를 연동하여 클라우드 및 로컬 AI 추론 환경을 지원하도록 설계했습니다.
- 저장소별 분석, 개선점 도출, LinkedIn 게시글 초안 생성 및 다국어 보고서 출력 기능을 구현했습니다.
- Streamlit 기반 웹 인터페이스를 구축하고 Streamlit Community Cloud를 통해 온라인 서비스 배포 역시 수행했습니다.

> ---
</details>

<h3 id="cori_tts">cori_tts</h3>

<details>
<summary><strong>cori_tts는 Piper TTS를 기반으로 음성 합성 과정의 기술적 진입장벽을 낮추고, 비전문가도 쉽게 사용할 수 있는 환경을 제공하기 위해 개발한 UX 중심의 TTS wrapper입니다.</strong></summary>

#### cori_tts 이전

> (My own voice TTS)[https://github.com/ulsidae/dev_logs/tree/main/AI/My%20own%20voice%20TTS]

- .wav 형식의 파일을 넣고 이를 재생하는 방식을 활용했습니다.
- @(at sign)을 활용해 0.1초 출력을 정지하는 기능을 통해 원시적인 파서(parser)를 구현했습니다.

#### python으로 만든 cori_tts

> [cori_tts](https://github.com/ulsidae/cori_tts)

- Piper TTS를 기반으로 텍스트 파일을 음성으로 변환하는 Windows용 TTS wrapper를 개발했습니다.
- GUI 기반 인터페이스를 구현하여 모델 선택 및 음성 합성 과정의 사용 편의성 개선을 시도했습니다.
- Piper TTS의 upstream 개발자와 프로젝트 구조 및 GPL 라이선스 관련 문의를 진행하고 오픈소스 호환성을 검토했습니다.
</details>

> ---

### ⚡️ AI 관련 글들


<h3 id="Newton-Raphson">Newton-Raphson Chat Prototype</h3>

<details>
<summary><strong>고등학생 때 구상한 뉴턴 랩슨 방법을 통한 대화 예시를 정리해두었습니다. </strong></summary>

> [Newton-Raphson](https://github.com/ulsidae/dev_logs/tree/main/AI/Newton-Raphson)

- 뉴턴 랩슨 방법을 통해 한정된 메세지 내용으로 자연스럽게 대화하는 방법을 탐색해보았습니다.

</details>


<h3 id="Local_AI">Local AI</h3>

<details>
<summary><strong>Ollama 관련 내용 정리, 자작 모델 테스트 결과 등을 기록해두었습니다.</strong></summary>

> [pr_Ollama-max](https://github.com/ulsidae/dev_logs/tree/main/AI/pr_Ollama-max)

- Ollama를 통한 Modelfile예시, 개인적으로 상황에 맞게 사용하기 좋은 AI model 추천 등을 기록해두었습니다.

<br>

> [DFS & BFS with AI](https://github.com/ulsidae/dev_logs/tree/main/AI/DFS%20%26%20BFS%20with%20AI)

- Ollama를 통해 생성한 커스텀 모델을 BFS,DFS 알고리즘을 작성하도록 해 테스트해보았습니다.

</details>

<h3 id="felyxorine">Virtual AI</h3>

<details>
<summary><strong>local AI 연구에 모델링 기술을 더해서 최소한의 기능을 갖춘 버츄얼 AI를 만들어보았습니다.</strong></summary>

#### project felyxorine 이전

> [Hand Capture Prototype](https://github.com/ulsidae/dev_logs/tree/main/idea-notes/Hand%20Capture%20Prototype%20(Legacy))

- 고등학생 때 동작을 컴퓨터가 인식하는 것에 관심을 가지게 되었고, 가상 캐릭터인 버츄얼 캐릭터 설계에 대해 탐구했습니다.

> [test](https://github.com/ulsidae/dev_logs/blob/main/idea-notes/AI-test/main.py)

- Ollama에 대해 간단하게 테스트를 해보았습니다

#### project_felyxorine

> [project_felyxorine](https://github.com/ulsidae/dev_logs/tree/main/AI/project_felyxorine)

- 코드를 실행 시 필요 의존성을 다운로드를 받아서 실행할 수 있도록 환경을 설계했습니다.
- three-vrm을 통해 vrm 모델 파일을 불러올 수 있도록했습니다.
- felyxorine의 모델링을 직접 vroid studio를 통해서 제작했습니다.
- ollama와의 연동을 통한 대화 창을 설계하고, 이를 구현했습니다.

</details>

<h3 id="curriculum_neuroevolution">curriculum neuroevolution</h3>

<details>
<summary><strong>예측 불가능한 환경 변화와 반복적으로 발생하는 불리한 상황을 AI 에이전트의 미로 탐색 및 진화 과정으로 풍자적으로 표현한 개인 실험입니다.</strong></summary>

> [curriculum_neuroevolution.py](https://github.com/ulsidae/dev_logs/blob/main/AI/EVO-1/curriculum_neuroevolution.py)

- 무작위 장애물, 이동하는 목표 지점 및 제한된 자원 등 예측하기 어려운 환경 요소를 구현했습니다.
- 신경망 기반 에이전트와 유전 알고리즘을 결합하여 반복적인 학습 및 진화 과정을 구성했습니다.
- 환경 난이도와 에이전트의 성과에 따라 학습 조건이 변화하는 적응형 시뮬레이션 구현했습니다.

</details>

<h3 id="translate_system_test">deep_translator(GoogleTranslator API wrapper)를 통해 한국어-영어 번역 시스템을 설계해보았습니다</h3>

<details>
<summary><strong>번역기 아이디어</strong></summary>

> [translate system test](https://github.com/ulsidae/dev_logs/tree/main/AI/translate%20system%20test)
  
</details>

---

<h2 id="2">⚙️ RSVP-systems</h2>

> 학생회 활동 등을 통해 시스템적 사고와 문제 해결 역량을 발전시킨 경험을 정리했습니다.

> ---

<h3 id="System_Thinking">System Thinking</h3>

> 일상생활에서 일어난 여러가지 일들을 시스템적인 관점에서 보는것을 시도하며 관련 내용들을 기록했습니다.

<details>
<summary><strong>학생회 경험</strong></summary>

- 사용자 중심 사고: 구성원, 관객 등의 요구 및 기대를 파악하고, 이를 바탕으로 공연과 공용 업무 환경의 개선 방향을 설정했습니다.
- 협업 및 자원 조율: 제한된 인력과 자원 속에서 구성원 간 역할을 조율하고, 공동의 목표 달성을 위한 협업을 수행했습니다.
- 문제 해결 및 운영 개선: 현장에서 발생하는 문제와 운영상의 비효율을 파악하고, 우선순위에 따라 실질적인 해결책을 실행했습니다.

**a. User-Centric Event Planning**

> [User-Centric Event Planning](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DUser-Centric%20Event%20Planning)은 학생회 공연에서 관객의 기대와 팀의 완성도를 고려해
> 공연을 준비하고, 제한된 시간 내 협업과 실행력을 발휘한 행사 기획 및 참여에 대한 글입니다.

- 학생회 공연의 관객 기대 요소를 분석하고 에너지, 동작 동기화 및 무대 표현력을 중심으로 공연 방향을 설정했습니다.
- 개인별 역량과 팀 전체의 일관성을 고려한 공연 구성 및 무대 연출 방향을 함께 소통하며 조율했습니다. 
- 반복적인 개인 연습과 자기 점검을 통해 안무 숙련도를 향상하고 공연 완성도를 개선 및 향상시켰습니다.
- 축제 직전 집중 리허설을 통해 동작 동기화 및 팀 전체의 무대 표현력을 보완했습니다.
- 그 결과, 공연 이후 학생들의 긍정적인 반응과 후속 행사에 대한 관심을 확인할 수 있었습니다.

**b. PE-flow-support**

> [PE-flow-support](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DPE-flow-support)는 학교 연합 체육 행사에서 경기 진행, 안전 지원 및 물품 관리를 수행하며, 제한된 인력과 현장 변수에 대응하는 다중 역할 기반의 현장 운영 지원 경험에 대한 글입니다.

- 축구, 농구, 피구 등 복수 종목의 원활한 경기 진행을 위한 공 회수 및 경기 흐름을 관리했습니다.
- 제한된 인력과 기상 조건 등 현장 변수에 따라 경기를 지원하고 안전 대응 및 물류 관리 역할을 유동적으로 수행했습니다.
- > 경기 중 발생한 부상 상황에 대응하고 추가 지원이 도착할 때까지 현장 안전을 지원했습니다.
- > 행사 장비 및 물품 정리, 냉장고 설치와 음료 관리 등 현장 자원 운영을 지원했습니다.
- > 여러 활동이 동시에 진행되는 환경에서 상황의 긴급성과 영향도를 고려한 업무 우선순위를 조정해 일을 수행했습니다.


**c. Operational-Improvements**

> [Operational-Improvements](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DOperational-Improvements)는 학생회 회의실의 환경적·운영상 문제를 파악하고, 공간 정비와 사무기기 문제 해결을 통해 공용 업무 공간의 기본적인 사용성과 운영 안정성을 회복한 개선 사례에 대한 글입니다.

- 회의실 내 이동 동선, 작업 공간, 냉장고, 수납공간 및 사무기기 상태를 점검하여 주요 사용성 저해 요인을 파악했습니다.
- 냉장고 내부와 책상, 수납공간 등을 정비하고 방치된 물품 및 누적 폐기물을 처리하여 공용 공간의 위생과 접근성을 개선했습니다.
- 회의실 전체를 정리하고, 폐기물 처리를 수행하여 구성원들이 공동으로 사용할 수 있는 기본 업무 환경을 복구했습니다.
- 워드프로세서의 컬러 출력 설정 문제를 파악하고 설정을 조정하여 외부 지원 없이 프린터 출력 기능을 정상화했습니다.
- 환경 정비부터 사무기기 문제 해결까지 전반적인 복구 작업을 수행하고, 공간의 기능적 사용성 회복 여부를 확인했습니다.

> ---

</details>

<details>
<summary><strong>유지보수 협업 경험</strong></summary>


> [유지보수 협업 경험 글](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DLegacy%20Servers%20%26%20PHP)

- PHP 기반 레거시 시스템의 보안 취약점 발생에 따른 긴급 대응 및 서비스 영향 최소화 작업을 수행했습니다.
- 정적 HTML 안내 페이지를 제작하여 임시 서비스 화면을 제작했습니다.
- 호스팅 업체와 긴급 보안 패치 적용 여부를 확인하고, 관련 로그 검토를 통해 침해 흔적 점검
- Client에게 장애 상황과 대응 계획을 전달하며 내부 개발진 및 외부 업체 간 커뮤니케이션을 수행했습니다.
- 유지보수 한계를 고려한 기존 시스템 제거 및 신규 대체 시스템 설계 과정에 참여했습니다.

</details>

<details>
<summary><strong>기숙사 청소 역할 분담 경험</strong></summary>

> [기숙사 청소 역할 분담 경험 글](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DShared%20Living%20Process%20Design)

- 공동생활 중 발생하는 청소 책임 불명확, 생활 패턴 충돌 및 의사소통 문제를 분석하고 근본 원인을 도출했습니다.
- 공동생활 규칙과 생활 시간대를 합의하여 일상적인 마찰을 줄이기 위한 기준을 수립했습니다.
- 공용 공간별 청소 업무를 분배하고 담당자를 명확히 지정하여 책임 소재 및 업무 수행 체계 정립했습니다.
- 반복적인 문제 해결보다 예방 가능한 운영 프로세스 구축에 중점을 두고 추가 개선 방안 역시 도출했습니다.

</details>

> ---

<h3 id="Re-engineered_Academic_Work">Re-engineered Academic Work</h3>

> 학업에서 배운 내용을 새롭게 다른 관점에서 정리하여 다양한 관점에서 한 가지 주제를 보고자 시도했습니다.

<details>
<summary><strong>Wave Function Streams</strong></summary>

> [Wave Function Streams](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%93%9AWave%20Function%20Streams)는 기존의 학업 및 학습 경험에서 얻은 아이디어를 독립적인 실험과 구현으로 확장하고, 추상적인 개념을 실제 작동하는 시스템으로 구체화하기 위해 수행한 프로젝트입니다.

- 학교에서 Streams를 플레이하며 숫자의 위치를 결정하는 과정에 내재된 불확실성과 여러 선택 가능성에 주목했습니다.
- 관측에 따라 여러 가능성 중 하나가 확정되는 Wave Function 개념에서 영감을 얻어 확률 기반 숫자 퍼즐 시스템을 구상했습니다.
- 숫자 간 인접 관계, 오름차순 흐름 및 연속성 등을 고려한 확률 계산과 제약 전파 로직을 설계하고 구현했습니다.
- 엔트로피 기반 안정성 지표와 사용자 직관의 확률적 예측 간 일치도를 활용하여 게임 내 불확실성과 상호작용을 표현했습니다.
- 구현 과정에서 실제 양자역학과의 차이, 휴리스틱 기반 확률 모델 및 지역적 제약 전파의 한계를 분석하고 향후 개선 방향을 도출했습니다.

</details>

<details>
<summary><strong>Human Resource Management for Product Management</strong></summary>

> [HRM for PM](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%93%9A%20HRM%20for%20PM)은 교양 과목으로 수강한 인적자원관리의 이론을 Product Management 관점에서 재해석하고, 조직 내 사람·커뮤니케이션·인센티브·갈등 구조를 제품팀의 운영 문제와 연결해 실무적인 조직 분석 및 시스템 사고로 확장해본 글입니다.

- 인적자원관리 강의 자료를 바탕으로 PM관점의 운영 환경을 연결하여 재구성했습니다.
- DISC 유형을 제품팀 구성원의 커뮤니케이션 성향과 협업 방식에 대한 분석 프레임워크로 재해석하고, 팀 내 역할과 상호보완 관계를 탐구했습니다.
- 서번트 리더십과 진정성 리더십을 바탕으로 공식적인 권한보다 영향력과 신뢰를 중심으로 하는 PM의 리더십 및 팀 운영 방식을 분석했습니다.
- 조직 내 자원·관계·구조적 갈등을 제품팀의 우선순위 충돌, 이해관계자 조율 및 업무 소유권 문제와 연결하고 갈등 관리와 절차적 공정성의 중요성을 탐구했습니다.
- 성과 평가, 심리적 안전감, 커뮤니케이션 및 글로벌 HRM 개념을 제품 조직의 협업 효율성과 운영 안정성 관점에서 재해석하고 실무적 시사점을 도출했습니다.

</details>

<details>
<summary><strong>Blockchain Security Re-Engineering</strong></summary>

> [Blockchain Security Re-Engineering](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%93%9ABlockchain%20Security%20Re-Engineering)는 발표 중심으로 수행했던 블록체인 보안 과제를 재검토하고, 시연을 통한 직관적 설명에서 분산 시스템과 암호학적 보안 구조를 다루는 이론 중심의 분석으로 확장해본 것을 정리한 글입니다

- 비전공자도 이해할 수 있도록 블록체인과 보안 개념을 설명하는 대학 발표 자료를 제작하고, 기술적 복잡성을 낮추기 위한 전달 방식을 설계했습니다.
- JetCoin이라는 단순화된 중앙 집중형 시뮬레이션 모델을 구축하여 트랜잭션 처리 과정과 동시성 문제를 시연했습니다.
- Race Condition 및 TOCTOU와 이중 지불(Double Spending) 문제를 통제된 환경에서 시각적으로 설명했습니다.
- 기존 발표의 직관 중심 설명과 이론적 깊이 사이의 한계를 분석하고, 블록체인 보안 구조에 대한 별도의 [분석 문서](https://ulsidae.github.io/dev_logs/Security%20&%20Crypto/Blockchain%20Security%20Analysis/)로 재구성했습니다.

</details>

<details>
<summary><strong>Case Study: Reviewing My High School README</strong></summary>

> 고등학교 지구과학 과제로 제작한 좌표 시각화 프로그램을 보존하고, 문서화·사용자 경험·코드 구조 관점에서 재검토하여 초기 개발 경험을 PM 및 Software Engineering 관점의 개선 과제로 확장한 프로젝트입니다.

- 사용자 입력을 통해 두 그룹의 좌표 데이터를 수집하고, 기준 이미지 위에 좌표와 연결선을 표시하는 Python 기반 시각화 [코드](http://github.com/ulsidae/RSVP-systems/blob/main/%F0%9F%93%9ACase%20Study%3A%20Reviewing%20My%20High%20School%20README/earth-science-portfolio/main.py)에 대해 분석했습니다.
- 기존 README의 언어 혼용, 비일관적인 문체, 프로젝트 설명 부족 및 정보 구조 문제를 분석하고 독자 중심의 문서화 개선 방향을 도출했습니다.
- 반복적인 입력 처리, 고정된 데이터 구조, 기능 간 결합도 및 입력값 검증 부재 등 기존 코드의 유지보수성과 확장성 측면의 한계를 [분석](https://github.com/ulsidae/RSVP-systems/blob/main/%F0%9F%93%9ACase%20Study%3A%20Reviewing%20My%20High%20School%20README/readme.md)했습니다.
- 문서화와 코드 구조가 사용자 경험 및 프로젝트 이해도에 미치는 영향을 정리하고, 향후 프로젝트에 적용할 개선 원칙을 도출했습니다.

</details>

> ---

<h3 id="Problem_Solving">Problem Solving (Coding Tests)</h3>

> 개인적으로 풀어본 코딩테스트 문제들 역시 새롭게 다른 관점에서 정리하여 다양한 관점에서 한 가지 주제를 보고자 시도했습니다.

<details>
<summary><strong>7-Day Intensive Log: Exploring Algorithmic Efficiency</strong></summary>

> [7-Day Intensive Log](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%A7%A90.%207-Day%20Intensive%20Log%3A%20Exploring%20Algorithmic%20Efficiency)는 알고리즘 문제 풀이 과정에서 실행 효율성과 코드 구조를 개선하기 위해 다양한 구현 방식을 실험하고, 누적 합과 다중 시그마 등 수학적 개념을 알고리즘 구조와 연결하여 분석한 집중 학습 프로젝트입니다.

- 알고리즘 교재의 예제 코드를 재구성하며 불필요한 연산과 반복 처리를 줄이고, 코드 간결성과 실행 효율성 개선 방향을 탐구했습니다.
- Python의 빠른 입출력 처리와 내장 함수 등을 활용하여 구현 방식에 따른 실행 오버헤드 및 효율성을 비교했습니다.
- 누적 합(Prefix Sum)을 수학적 시그마 표기법과 연결하여 누적 연산의 구조를 분석하고, accumulate를 활용한 구현 방식을 실험했습니다.
- 2차원 누적 합을 이중 시그마(Double Sigma) 개념으로 확장하고, 다차원 구간 합 계산 로직의 구현 방식을 탐구했습니다.
- 이산수학 학습을 통해 알고리즘의 제약 조건과 최적화의 한계를 검토하고, 실행 효율성·구현 복잡도·유지보수성 사이의 실용적인 트레이드오프를 분석했습니다.
</details>

<details>
<summary><strong>Two Sum(leet code)</strong></summary>

> [Two Sum](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%A7%A91.%20Two%20Sum(leet%20code)) 문제를 C++로 해결하며 해시 테이블을 활용한 탐색 최적화를 적용하고, 구현 순서에 따른 정확성 및 시간·공간 복잡도를 분석한 알고리즘 문제 해결 사례입니다.

- 중첩 반복문을 사용하는 Brute Force 방식의 O(N^2) 시간 복잡도를 개선하기 위해 해시 테이블 기반의 단일 순회 전략을 설계했습니다.
- 현재 원소와 목표값의 차이(Complement)를 계산하고, 이전에 탐색한 원소의 존재 여부를 조회하는 unordered_map 기반 탐색 로직을 구현했습니다.
- 표준 헤더 명시, 자료형 선언 및 코드 구조 개선을 통해 독립적인 컴파일 가능성과 가독성·유지보수성을 향상시켰습니다.
</details>

<details>
<summary><strong>Add Two Numbers(leet code)</strong></summary>

> [Add Two Numbers](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%A7%A92.%20Add%20Two%20Numbers(leet%20code))는 연결 리스트로 표현된 두 정수를 자릿수별로 더하는 문제를 반복문 기반으로 해결한 뒤 재귀 방식으로 리팩터링하고, 캐리 전달과 데이터 흐름을 함수 호출 구조로 표현한 알고리즘 문제 해결 사례입니다.

- 역순으로 저장된 두 연결 리스트의 자릿수를 순회하며 덧셈과 올림을 처리하는 반복문 기반 알고리즘을 구현했습니다.
- 서로 다른 연결 리스트 길이와 마지막 자릿수의 올림까지 고려하여 숫자 변환 없이 결과 연결 리스트를 생성했습니다.
- 기존 반복문 기반 구현을 재귀 방식으로 리팩터링하여 각 함수 호출이 하나의 자릿수 연산을 담당하도록 구조화했습니다.
- 반복문과 재귀 방식의 구조적 차이를 비교하며 연결 리스트 순회와 상태 전달을 데이터 흐름 관점에서 분석했습니다.
</details>

<details>
<summary><strong>Longest Substring Without Repeating Characters (LeetCode)</strong></summary>

> [Longest Substring Without Repeating Characters](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%A7%A93.longest%20substring%20without%20repeating%20characters(leet%20code))는 중복 문자가 없는 최장 부분 문자열을 탐색하는 문제에서 초기 구간 분할 접근의 한계를 분석하고, Sliding Window와 Hash Table을 결합한 단일 순회 알고리즘으로 개선한 문제 해결 사례입니다.

- 문자열을 중복 문자 기준으로 독립적인 구간으로 분할하는 초기 접근 방식을 구상하고, 구간 간 중복 문자가 발생하는 상황에서 해당 방식의 한계를 확인했습니다.
- 기존 구간을 초기화하는 대신 유효한 탐색 범위의 시작점만 이동하는 Sliding Window 방식으로 접근 전략을 개선했습니다.
- Hash Table을 활용하여 각 문자의 마지막 등장 인덱스를 관리하고, 중복 문자 발생 시 현재 탐색 범위의 시작 위치를 갱신하는 로직을 구현했습니다.
- 초기 접근과 개선된 알고리즘을 비교하며 구간 재구성보다 경계값 관리가 효율적인 문제 해결 방식임을 분석했습니다.
</details>

---

<h2 id="3">🔒 Security & Crypto</h2>

> 정보보안 및 암호학 관련 기술 탐구와 실험을 정리했습니다. 

> ---

<h3 id="Landa">Landa — CVE-2023-41974</h3>

<details>
<summary><strong>Apple XNU 커널의 CVE-2023-41974를 중심으로 Physical Use-After-Free(PUAF)의 메모리 관리 구조와 커널 등을 분석했습니다.</strong></summary>

> [연구 프로젝트](https://github.com/ulsidae/dev_logs/tree/main/Security%20%26%20Crypto/Landa%20%E2%80%94%20CVE-2023-41974)

- CVE-2023-41974와 관련 공개 연구 자료를 바탕으로 XNU 커널의 메모리 관리 구조 및 Physical Use-After-Free(PUAF)의 개념과 작동 원리를 분석했습니다.
- Apple의 보안 권고 내용을 바탕으로 CVE-2023-41974의 영향 범위와 공개된 수정 방향을 검토하고, 공개 정보와 추론 가능한 내용을 구분하여 기술을 문서화했습니다.
- 별도의 시스템 실험으로 Apple M1 기반 iPad Air 5세대 환경에서 가상화 스택을 활용한 macOS 게스트 부팅에 성공하고 실험 결과를 기록해두었습니다.
</details>

<h3 id="totp">Time-based One-Time Password (RFC 6238)</h3>

<details>
<summary><strong>TOTP를 Python으로 구현하고, HOTP와의 관계, HMAC 기반 인증 구조 및 암호학적 보안 특성을 분석했습니다.</strong></summary>

> [구현](https://github.com/ulsidae/dev_logs/blob/main/Security%20%26%20Crypto/totp/totp.py) & [분석](https://github.com/ulsidae/dev_logs/blob/main/Security%20%26%20Crypto/totp/readme.md)

- RFC 6238을 참고하여 공유 비밀키와 시간 기반 카운터를 이용한 TOTP 생성 로직을 구현했습니다.
- HMAC-SHA1, 30초 시간 간격, 6자리 인증 코드 및 Base32 인코딩을 활용한 표준 구성 요소를 적용했습니다.
- HOTP(RFC 4226)의 이벤트 기반 카운터를 시간 기반 카운터로 확장하는 TOTP의 동작 원리를 분석했습니다.
- 일반 SHA-1의 충돌 취약점과 HMAC-SHA1의 보안 특성을 구분하고, TOTP 인증 구조에서의 암호학적 역할을 검토했습니다.
- 공유 비밀키 보호의 중요성과 알고리즘 공개를 전제로 하는 암호학적 설계 원칙을 정리하고 구현 내용을 기술 문서화해두었습니다.
</details>

---

<h2 id="4">🚀 Game</h2>

> 기획부터 구현까지 주도적으로 참여한 게임 관련 프로젝트를 정리했습니다.

> ---

<h3 id="game-modding">Game Modding</h3>

<details>
<summary><strong>자작 게임 개발 이전에 게임의 모드들을 제작한 경험이 있습니다.</strong></summary>

> [Game Modding](https://github.com/ulsidae/dev_logs/tree/main/game%20modding)

- 전투 없이 대화만으로 게임 진행하기, NPC의 주택 활용하기, 모든 방문자를 거부하는 방식 등 기존 게임 규칙을 벗어난 플레이를 시도하며 게임을 색다른 관점으로 바라보았습니다.
- 이러한 관점을 기반으로 기존 동작을 변형해 새로운 결과를 만들어보려는 모딩을 해본 경험이 있습니다.
</details> 


<h3 id="dont-take-my-gummies">Don't Take My Gummies!</h3>

<details>
<summary><strong>AI를 개발 보조 도구로 활용해 제한된 시간과 자원 안에서 아이디어를 실제 플레이 가능한 보드게임으로 구현한 팀 프로젝트입니다.</strong></summary>

> [Don't Take My Gummies!](https://github.com/ulsidae/dont-take-my-gummies/tree/main)

- 기획 및 협업: 프로젝트 리드로서 요구사항 정의, 기능 우선순위 설정, 일정 관리 및 팀원 간 작업 조율을 담당했습니다.
- QA 및 배포: 자동화 테스트 44건 통과했으며, 배포 과정에서 발생한 프랑스어 현지화 및 리소스 처리 문제를 재현·수정하고 재검증을 수행했습니다.
- 다국어 및 서비스화: 한국어·영어·프랑스어 지원하며, GitHub Pages 배포를 통해 공개했습니다.
</details>

<h3 id="Draw_and_Act">Draw and Act</h3>

<details>
<summary><strong>해커톤에서 선정되지 못한 아이디어를 포기하지 않고, 직접 웹 기반 멀티플레이 게임으로 구현한 개인 주도 프로젝트입니다.</strong></summary>

> [Draw and Act](https://github.com/ulsidae/Draw_and_Act)

- 배포 및 실행 환경: 별도 전용 백엔드 없이 브라우저에서 실행되는 웹 게임으로 구현하고 GitHub Pages에 배포했습니다.
- 멀티플레이 시스템: Codex를 활용해 로비 생성·참여, 실시간 P2P 연결 및 그림 동기화 기능을 구현했습니다.
- 다국어 지원: 한국어·영어·프랑스어·일본어 지원. 서로 다른 언어 설정을 사용하는 플레이어도 동일한 방에서 참여 가능하도록 제작했습니다.
</details>


<h3 id="Chess_with_Math">Chess with Math</h3>

<details>
<summary><strong>NegaMax를 통해서 간단한 AI 체스 게임을 만들어봤습니다.</strong></summary>

> [Source Code](https://github.com/ulsidae/dev_logs/blob/main/AI/Chess%20with%20Math/sourcecode.py)

- [itch.io](https://ulsidae.itch.io/chess-with-math)를 통해 공개했습니다.

</details>

---

<h2 id="5">📓 idea-notes</h2>

> 일상 속 문제 해결을 위한 개인적인 아이디어와 기술적 실험을 정리했습니다.

> ---

### 📌 추천하는 idea notes관련 글들

<h3 id="KeyBridge">KeyBridge</h3>

<details>
<summary><strong>Windows 10에서 노트북 키보드 사용 중 발생한 불편을 해결하기 위해 제작한 개인용 유틸리티입니다.</strong></summary>

> [KeyBridge](https://github.com/ulsidae/dev_logs/tree/main/idea-notes/KeyBridge)

- 실행 파일(KeyBridge.exe) 형태로 공개하여 다른 사용자도 활용할 수 있도록 제공했습니다.
</details>

<h3 id="AMINO_3D">AMINO 3D</h3>

<details>
<summary><strong>Python과 RDKit을 활용해 20종 표준 아미노산의 분자 구조를 3D로 시각화한 실험 프로젝트입니다.</strong></summary>

> [AMINO 3D](https://github.com/ulsidae/dev_logs/tree/main/idea-notes/AMINO_3D)

- 향후 화학 관련 프로젝트를 위한 분자 시각화 기술을 사전 탐색해보았습니다.
- 구조를 주변 친구들에게 쉽게 설명해주기 위해 만들었습니다.
</details>


### 📓 아이디어 관련 글들

<h3 id="AI_logo">AI logo generation Idea</h3>

<details>
<summary><strong>logo 생성 AI Idea를 간단하게 만들어봤습니다.</strong></summary>

> [AI logo generation Idea](https://github.com/ulsidae/dev_logs/tree/main/idea-notes/AI%20logo%20generation%20Idea)

</details>

<h3 id="Overflow_Roulette">Overflow Roulette</h3>

<details>
<summary><strong>C언어의 Overflow 개념에서 아이디어를 얻어 python으로 간단한 게임 아이디어를 구현해보았습니다.</strong></summary>

> [Overflow_Roulette](https://github.com/ulsidae/dev_logs/tree/main/idea-notes/Overflow_Roulette)

</details>

<h3 id="x86_os">x86 os</h3>

<details>
<summary><strong>어셈블리어로 간단한 x86 Bootloader를 제작해보았습니다.</strong></summary>

> [x86 os](https://github.com/ulsidae/dev_logs/tree/main/idea-notes/x86_os)

</details>

---

<h2 id="6">📚 Tutorial</h2>

> 학습한 기술과 지식을 문서화하고 다른 사람에게 전달하기 위해 제작한 자료를 정리했습니다.

> ---

<h3 id="concepts-explained">Concepts Explained</h3>

<details>
<summary><strong>현재 제작중인 튜토리얼입니다.</strong></summary>

> [Concepts Explained](https://github.com/ulsidae/concepts-explained)

- 엑셀의 기초함수에 대해 자세히 알고싶은 사람들을 위한 글을 작성해두었습니다.
- Rust, Python등의 내용도 설명할 계획입니다.
</details>

---

<h2 id="7">🦀 Web Development</h2>

> 주로 Rust를 활용한 웹 기술 구현과 관련 실험 및 설계 과정을 정리했습니다.

> ---

<h3 id="unsafe-calc">unsafe-calc</h3>

<details>
<summary><strong>Vec대신 unsafe를 활용해 계산기를 만들어보며 Rust에 대해서 탐구해보았습니다.</strong></summary>

> [unsafe-calc](https://github.com/ulsidae/unsafe-calc)

</details>

<h3 id="ulsidae_github_io">ulsidae.github.io</h3>

<details>
<summary><strong>Rust wasm을 통해 간단한 리다이렉트 페이지를 만들어보았습니다.</strong></summary>

> [ulsidae.github.io](https://github.com/ulsidae/ulsidae.github.io)

</details>

---

<h2 id="8">🖥️ Server</h2>

> 서버 아키텍처와 관련 기술을 탐구하고 구현한 실험들을 정리했습니다.

> ---

<h3 id="dynamic-archive-interface">Dynamic Archive Interface</h3>

<details>
<summary><strong>Client의 요구사항에 맞춰 시안을 제작하고 NDA를 준수해 방향성을 검증했습니다.</strong></summary>

> [Dynamic Archive Interface](https://github.com/ulsidae/dev_logs/tree/main/Server/dynamic-archive-interface)

- 데이터 관리: 메타데이터 배열을 기반으로 콘텐츠를 동적으로 렌더링하고, 데이터와 UI를 분리했습니다.
- 정렬 기능: 배열 등록 순서 및 폴더명(YYMMDD)을 활용한 최신순·오래된순 정렬을 지원합니다.
- 자산 처리: 이미지 확장자(JPG, PNG, GIF)별 대체 탐색 로직을 적용해 파일 형식이 다른 환경에 대응하도록 제작했습니다.
- 예외 처리 및 확장성: 등록된 이미지 수와 실제 자산이 일치하지 않는 경우에도 렌더링 흐름을 유지하도록 처리했습니다.

</details>

<h3 id="CRUD_test">CRUD_test(local)</h3>

<details>
<summary><strong>CRUD 기능을 간단하게 만든 후 보안 기술을 적용하는 연습을 해보았습니다.</strong></summary>

> [CRUD_test(local)](https://github.com/ulsidae/dev_logs/blob/main/Server/CRUD_test(local)/app.py)

</details>

---


> [!NOTE]
> 아래의 내용은 협동 경험, 업무 경험을 중점적으로 위의 내용들을 정리해둔 글 입니다.

---

<h2 id="a">👥 Collaboration</h2>

### 1.학생회 경험 

> 대학교 학생회 활동을 하며 협업, 우선순위 조정 등 여러가지 경험을 쌓았습니다.

> ---

**a. User-Centric Event Planning**

> [User-Centric Event Planning](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DUser-Centric%20Event%20Planning)은 학생회 공연에서 관객의 기대와 팀의 완성도를 고려해
> 공연을 준비하고, 제한된 시간 내 협업과 실행력을 발휘한 행사 기획 및 참여에 대한 글입니다.

- 학생회 공연의 관객 기대 요소를 분석하고 에너지, 동작 동기화 및 무대 표현력을 중심으로 공연 방향을 설정했습니다.
- 개인별 역량과 팀 전체의 일관성을 고려한 공연 구성 및 무대 연출 방향을 함께 소통하며 조율했습니다. 
- 반복적인 개인 연습과 자기 점검을 통해 안무 숙련도를 향상하고 공연 완성도를 개선 및 향상시켰습니다.
- 축제 직전 집중 리허설을 통해 동작 동기화 및 팀 전체의 무대 표현력을 보완했습니다.
- 그 결과, 공연 이후 학생들의 긍정적인 반응과 후속 행사에 대한 관심을 확인할 수 있었습니다.

**b. PE-flow-support**

> [PE-flow-support](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DPE-flow-support)는 학교 연합 체육 행사에서 경기 진행, 안전 지원 및 물품 관리를 수행하며, 제한된 인력과 현장 변수에 대응하는 다중 역할 기반의 현장 운영 지원 경험에 대한 글입니다.

- 축구, 농구, 피구 등 복수 종목의 원활한 경기 진행을 위한 공 회수 및 경기 흐름을 관리했습니다.
- 제한된 인력과 기상 조건 등 현장 변수에 따라 경기를 지원하고 안전 대응 및 물류 관리 역할을 유동적으로 수행했습니다.
- > 경기 중 발생한 부상 상황에 대응하고 추가 지원이 도착할 때까지 현장 안전을 지원했습니다.
- > 행사 장비 및 물품 정리, 냉장고 설치와 음료 관리 등 현장 자원 운영을 지원했습니다.
- > 여러 활동이 동시에 진행되는 환경에서 상황의 긴급성과 영향도를 고려한 업무 우선순위를 조정해 일을 수행했습니다.

**c. Operational-Improvements**

> [Operational-Improvements](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DOperational-Improvements)는 학생회 회의실의 환경적·운영상 문제를 파악하고, 공간 정비와 사무기기 문제 해결을 통해 공용 업무 공간의 기본적인 사용성과 운영 안정성을 회복한 개선 사례에 대한 글입니다.

- 회의실 내 이동 동선, 작업 공간, 냉장고, 수납공간 및 사무기기 상태를 점검하여 주요 사용성 저해 요인을 파악했습니다.
- 냉장고 내부와 책상, 수납공간 등을 정비하고 방치된 물품 및 누적 폐기물을 처리하여 공용 공간의 위생과 접근성을 개선했습니다.
- 회의실 전체를 정리하고, 폐기물 처리를 수행하여 구성원들이 공동으로 사용할 수 있는 기본 업무 환경을 복구했습니다.
- 워드프로세서의 컬러 출력 설정 문제를 파악하고 설정을 조정하여 외부 지원 없이 프린터 출력 기능을 정상화했습니다.
- 환경 정비부터 사무기기 문제 해결까지 전반적인 복구 작업을 수행하고, 공간의 기능적 사용성 회복 여부를 확인했습니다.

> ---

### 2.팀프로젝트 경험 

> 다른 개발자, 디자이너와 함께 개발 프로젝트를 주도적으로 진행한 경험이 있습니다.

> ---

> [Don't Take My Gummies!](https://github.com/ulsidae/dont-take-my-gummies/tree/main)

- 기획 및 협업: 프로젝트 리드로서 요구사항 정의, 기능 우선순위 설정, 일정 관리 및 팀원 간 작업 조율을 담당했습니다.
- QA 및 배포: 자동화 테스트 44건 통과했으며, 배포 과정에서 발생한 프랑스어 현지화 및 리소스 처리 문제를 재현·수정하고 재검증을 수행했습니다.
- 다국어 및 서비스화: 한국어·영어·프랑스어 지원하며, GitHub Pages 배포를 통해 공개했습니다.

---

<h2 id="b">🎯 Professional Experience</h2>

### 1.초안을 통한 방향 결정 

> 클라이언트의 요구사항을 확인하고 NDA를 준수해 기술 문서를 작성했습니다.

> ---

> [Dynamic Archive Interface](https://github.com/ulsidae/dev_logs/tree/main/Server/dynamic-archive-interface)

- 데이터 관리: 메타데이터 배열을 기반으로 콘텐츠를 동적으로 렌더링하고, 데이터와 UI를 분리했습니다.
- 정렬 기능: 배열 등록 순서 및 폴더명(YYMMDD)을 활용한 최신순·오래된순 정렬을 지원합니다.
- 자산 처리: 이미지 확장자(JPG, PNG, GIF)별 대체 탐색 로직을 적용해 파일 형식이 다른 환경에 대응하도록 제작했습니다.
- 예외 처리 및 확장성: 등록된 이미지 수와 실제 자산이 일치하지 않는 경우에도 렌더링 흐름을 유지하도록 처리했습니다.

> ---

### 2.유지보수 협업 경험

> [유지보수 협업 경험 글](https://github.com/ulsidae/RSVP-systems/tree/main/%F0%9F%8C%8DLegacy%20Servers%20%26%20PHP)

- PHP 기반 레거시 시스템의 보안 취약점 발생에 따른 긴급 대응 및 서비스 영향 최소화 작업을 수행했습니다.
- 정적 HTML 안내 페이지를 제작하여 임시 서비스 화면을 제작했습니다.
- 호스팅 업체와 긴급 보안 패치 적용 여부를 확인하고, 관련 로그 검토를 통해 침해 흔적 점검
- Client에게 장애 상황과 대응 계획을 전달하며 내부 개발진 및 외부 업체 간 커뮤니케이션을 수행했습니다.
- 유지보수 한계를 고려한 기존 시스템 제거 및 신규 대체 시스템 설계 과정에 참여했습니다.

