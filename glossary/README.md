# AX:IS AI 용어집

AI · 개발 · 인프라 핵심 용어 **191개**를 쉬운 비유로 정리했습니다. 업데이트 **2026-11-02**

- 용어마다 **한 줄 요약 · 비유 설명 · 헷갈리는 점 · 카톡 대화 예시 · 연결 용어**가 있습니다.
- 찾는 법: 아래 분류를 누르거나, 문서 안에서 `Ctrl+F`(휴대폰은 브라우저 메뉴의 '페이지에서 찾기').
- 검색 · 필터가 되는 화면판: [AI 용어집 (PC)](https://kchmok-art.github.io/axis-slides/AI_%EC%9A%A9%EC%96%B4%EC%A7%91.html)

## 분류

| 분류 | 개수 | 내용 |
|---|---:|---|
| [LLM·생성형 AI](llm.md) | 6 | GPT, Claude, Gemini 같은 대형 언어 모델과 관련된 개념. 토큰, 컨텍스트, 프롬프트, RAG 등 LLM이 작동하는 원리와 활용법 |
| [머신러닝](ml.md) | 37 | 머신러닝·딥러닝·통계 관련 개념. 모델이 데이터를 학습하는 원리, 알고리즘, 성능 평가 방법 |
| [에이전트](agent.md) | 18 | AI가 스스로 판단하고 행동하며 목표를 달성하는 구조. 루프 엔지니어링, 멀티에이전트, 자동화 워크플로 관련 개념 |
| [AX·전환](ax.md) | 3 | AI를 활용해 업무·조직·삶의 방식을 바꾸는 변화와 전략. DX에서 AX로의 전환, 업무 자동화, 생산자/소비자 구분 등 |
| [개발](dev.md) | 34 | 웹·앱 개발에 필요한 기초 개념. 프론트엔드·백엔드·API·라우팅 등 개발자가 일상적으로 사용하는 용어 |
| [인프라](infra.md) | 69 | 서버·네트워크·배포 환경 관련 개념. 서비스가 실제로 돌아가는 물리적·가상적 환경과 구조 |
| [흐름](flow.md) | 24 | 여러 단계가 이어지는 과정(사이클 · 파이프라인 · 지도)을 순서대로 정리한 항목 |

## 최근 추가

- 2026-11-02 · [흐름: 쿠버네티스 큰 주방 지도 (클러스터→노드→Pod→컨테이너)](flow.md#term-191)
- 2026-11-02 · [서비스 (Service, 쿠버네티스)](infra.md#term-190)
- 2026-11-02 · [디플로이먼트 (Deployment, 쿠버네티스)](infra.md#term-189)
- 2026-11-02 · [Pod (파드, 쿠버네티스)](infra.md#term-188)
- 2026-11-02 · [Argo CD (아르고 CD)](infra.md#term-187)
- 2026-11-02 · [노드 (Node, 클러스터의 서버 한 대)](infra.md#term-186)
- 2026-11-02 · [클러스터 (Cluster)](infra.md#term-185)
- 2026-10-31 · [흐름: Ops 패밀리 지도 (식당 비유)](flow.md#term-184)
- 2026-10-31 · [ChatOps (챗옵스)](infra.md#term-183)
- 2026-10-31 · [AgentOps (에이전트옵스)](agent.md#term-182)
- 2026-10-31 · [AIOps (에이아이옵스)](infra.md#term-181)
- 2026-10-31 · [DataOps (데이터옵스)](ml.md#term-180)
- 2026-10-31 · [SecOps (보안 운영)](infra.md#term-179)
- 2026-10-31 · [DevSecOps (데브섹옵스)](infra.md#term-178)
- 2026-10-31 · [FinOps (클라우드 비용 운영)](infra.md#term-177)

## 전체 목록

### LLM·생성형 AI (6)

[RAG](llm.md#term-005) · [Temperature (온도)](llm.md#term-053) · [Top-k](llm.md#term-054) · [레시피 (Recipe)](llm.md#term-045) · [컨텍스트](llm.md#term-004) · [토큰](llm.md#term-003)

### 머신러닝 (37)

[Bagging](ml.md#term-060) · [CNN (Convolutional Neural Network)](ml.md#term-055) · [Cut-off (컷오프)](ml.md#term-062) · [DataOps (데이터옵스)](ml.md#term-180) · [Decision Tree (결정 트리)](ml.md#term-059) · [GAN (Generative Adversarial Network)](ml.md#term-058) · [LSTM (Long Short-Term Memory)](ml.md#term-057) · [Random Forest](ml.md#term-061) · [RNN (Recurrent Neural Network)](ml.md#term-056) · [ROC-AUC](ml.md#term-161) · [SVM (Support Vector Machine)](ml.md#term-050) · [Threshold (임계값)](ml.md#term-063) · [Transformer](ml.md#term-051) · [강화학습 (Reinforcement Learning)](ml.md#term-042) · [결정 경계 (Decision Boundary)](ml.md#term-154) · [경사하강법 (Gradient Descent)](ml.md#term-165) · [과적합과 일반화 (Overfitting·Generalization)](ml.md#term-162) · [교차 엔트로피 (Cross-Entropy)](ml.md#term-157) · [교차검증 (Cross-Validation)](ml.md#term-159) · [규제 (Regularization)](ml.md#term-163) · [딥러닝 (Deep Learning)](ml.md#term-047) · [로지스틱 회귀 (Logistic Regression)](ml.md#term-150) · [분류 (Classification)](ml.md#term-043) · [선형판별분석 (LDA)](ml.md#term-151) · [어텐션 (Attention)](ml.md#term-052) · [에포크 (Epoch)](ml.md#term-046) · [역전파 (Backpropagation)](ml.md#term-153) · [우도·최대우도추정 (Likelihood·MLE)](ml.md#term-155) · [은닉층 (Hidden Layer)](ml.md#term-049) · [인공신경망 (Artificial Neural Network)](ml.md#term-048) · [전이학습 (Transfer Learning)](ml.md#term-166) · [지니 불순도 (Gini Impurity)](ml.md#term-156) · [지도학습 (Supervised Learning)](ml.md#term-044) · [퍼셉트론 (Perceptron)](ml.md#term-152) · [하이퍼파라미터 (Hyperparameter)](ml.md#term-158) · [혼동행렬·정밀도·재현율·F1](ml.md#term-160) · [활성화 함수 (Activation Function)](ml.md#term-164)

### 에이전트 (18)

[AgentOps (에이전트옵스)](agent.md#term-182) · [MCP (Model Context Protocol)](agent.md#term-147) · [n8n](agent.md#term-088) · [검증자 (Verifier)](agent.md#term-121) · [권한 프로필 (Codex Permission Profile)](agent.md#term-143) · [랄프 루프 (Ralph Loop)](agent.md#term-119) · [루프 4종 (에이전트·검증·이벤트·개선 루프)](agent.md#term-126) · [루프 안전장치 (예산 상한·사람 호출 지점)](agent.md#term-127) · [루프 엔지니어링](agent.md#term-019) · [스킬 문서 (Skill Document)](agent.md#term-123) · [위임 4단계 (턴·목표·시간·자율형)](agent.md#term-125) · [진행 상황 파일 (Progress File)](agent.md#term-122) · [컨텍스트 엔지니어링](agent.md#term-018) · [트리거 (Trigger)](agent.md#term-120) · [하네스 (Harness)](agent.md#term-064) · [하네스 엔지니어링](agent.md#term-017) · [훅 (Hook, Claude Code)](agent.md#term-148) · [휴먼 인 더 루프 / 온 더 루프 (Human in/on the loop)](agent.md#term-124)

### AX·전환 (3)

[AX](ax.md#term-014) · [온보딩](ax.md#term-116) · [워크플로](ax.md#term-021)

### 개발 (34)

[API](dev.md#term-013) · [Config (설정 파일)](dev.md#term-117) · [Credentials (크리덴셜)](dev.md#term-100) · [Git](dev.md#term-067) · [GitHub](dev.md#term-068) · [iframe](dev.md#term-026) · [URI (Uniform Resource Identifier)](dev.md#term-101) · [YAML](dev.md#term-118) · [디코딩](dev.md#term-007) · [라우터](dev.md#term-001) · [라우팅](dev.md#term-002) · [리다이렉트 (Redirect)](dev.md#term-027) · [리다이렉트 URI (Redirect URI)](dev.md#term-103) · [리디렉션 (Redirection)](dev.md#term-102) · [모달 (Modal)](dev.md#term-025) · [백엔드 (Backend)](dev.md#term-036) · [백엔드 로직 (Backend Logic)](dev.md#term-039) · [백엔드 인증 (Backend Authentication)](dev.md#term-040) · [백엔드 처리 (Backend Processing)](dev.md#term-041) · [복호화](dev.md#term-009) · [스펙 (Spec)](dev.md#term-038) · [암호화](dev.md#term-008) · [와이어프레임 (Wireframe)](dev.md#term-109) · [워커 (Worker)](dev.md#term-024) · [워크트리](dev.md#term-022) · [워크트리 (Worktree)](dev.md#term-069) · [웹앱 (Web Application)](dev.md#term-033) · [인코딩](dev.md#term-006) · [쿠키 (Cookie)](dev.md#term-106) · [큐 (Queue)](dev.md#term-023) · [풀스택 (Full Stack)](dev.md#term-037) · [프로토타입 (Prototype)](dev.md#term-110) · [프론트엔드 (Frontend)](dev.md#term-035) · [화면 목업 (Mockup)](dev.md#term-108)

### 인프라 (69)

[ACME (자동 인증서 발급 규약)](infra.md#term-137) · [AIOps (에이아이옵스)](infra.md#term-181) · [AP 서버 (Application Server)](infra.md#term-029) · [Argo CD (아르고 CD)](infra.md#term-187) · [BaaS](infra.md#term-012) · [Build (빌드 단계)](infra.md#term-077) · [ChatOps (챗옵스)](infra.md#term-183) · [CI/CD](infra.md#term-083) · [CloudOps (클라우드 운영)](infra.md#term-176) · [Code (코드 단계)](infra.md#term-076) · [DB 서버 (Database Server)](infra.md#term-032) · [Deploy (배포 단계)](infra.md#term-080) · [DevOps](infra.md#term-070) · [DevOps 사이클 (8단계)](infra.md#term-074) · [DevSecOps (데브섹옵스)](infra.md#term-178) · [Docker](infra.md#term-084) · [Dockerfile (도커파일)](infra.md#term-171) · [FinOps (클라우드 비용 운영)](infra.md#term-177) · [GitOps (깃옵스)](infra.md#term-174) · [Grafana](infra.md#term-086) · [HTTPS](infra.md#term-133) · [InfraOps (인프라 운영)](infra.md#term-175) · [ISP (Internet Service Provider)](infra.md#term-031) · [IX (Internet Exchange)](infra.md#term-030) · [Jira](infra.md#term-087) · [Kubernetes (쿠버네티스)](infra.md#term-085) · [Let's Encrypt](infra.md#term-136) · [LLMOps](infra.md#term-114) · [MLOps](infra.md#term-113) · [Monitor (모니터링 단계)](infra.md#term-082) · [nginx](infra.md#term-107) · [Operate (운영 단계)](infra.md#term-081) · [Ops (운영) — OO+Ops 이름 읽는 법](infra.md#term-173) · [PaaS](infra.md#term-011) · [Plan (계획 단계)](infra.md#term-075) · [Pod (파드, 쿠버네티스)](infra.md#term-188) · [Release (릴리즈 단계)](infra.md#term-079) · [SaaS](infra.md#term-010) · [SecOps (보안 운영)](infra.md#term-179) · [SSL/TLS](infra.md#term-132) · [Test (테스트 단계)](infra.md#term-078) · [Traefik (트래픽)](infra.md#term-139) · [UTF-8](infra.md#term-028) · [WSL interop](infra.md#term-145) · [WSL2](infra.md#term-144) · [가상 머신 (VM)](infra.md#term-146) · [관제](infra.md#term-015) · [관제 (Monitoring & Control)](infra.md#term-071) · [네트워크 (Network)](infra.md#term-072) · [노드 (Node, 클러스터의 서버 한 대)](infra.md#term-186) · [도커 이미지 (Docker Image)](infra.md#term-169) · [디플로이먼트 (Deployment, 쿠버네티스)](infra.md#term-189) · [샌드박스 (Sandbox)](infra.md#term-112) · [서버](infra.md#term-016) · [서버 3단 구조 (3-Tier Architecture)](infra.md#term-034) · [서비스 (Service, 쿠버네티스)](infra.md#term-190) · [스토리지](infra.md#term-020) · [인증 기관 (CA)](infra.md#term-135) · [인증서 (SSL/TLS Certificate)](infra.md#term-134) · [인증서 체인 (Chain of Trust)](infra.md#term-138) · [최소 권한 원칙 (Least Privilege)](infra.md#term-142) · [캐싱 (Caching)](infra.md#term-066) · [컨테이너 (Container)](infra.md#term-170) · [크론 (Cron, 예약 작업)](infra.md#term-128) · [클러스터 (Cluster)](infra.md#term-185) · [프로토콜 (Protocol)](infra.md#term-073) · [프록시 (Proxy)](infra.md#term-104) · [프록시 라우팅 (Proxy Routing)](infra.md#term-105) · [핑 (Ping)](infra.md#term-065)

### 흐름 (24)

[흐름: AI 계층 구조](flow.md#term-095) · [흐름: AI 에이전트 폴더 잠금](flow.md#term-149) · [흐름: CI/CD 파이프라인](flow.md#term-092) · [흐름: DevOps → MLOps → LLMOps 진화](flow.md#term-115) · [흐름: DevOps 사이클](flow.md#term-091) · [흐름: Google OAuth 인증](flow.md#term-099) · [흐름: HTTPS 인증서 자동 발급](flow.md#term-140) · [흐름: n8n 워크플로](flow.md#term-097) · [흐름: Ops 패밀리 지도 (식당 비유)](flow.md#term-184) · [흐름: RAG 처리](flow.md#term-093) · [흐름: TLS 핸드셰이크](flow.md#term-141) · [흐름: UI 설계 4단계](flow.md#term-111) · [흐름: 네트워크 통신](flow.md#term-096) · [흐름: 도커 앱 업데이트 (코드 수정 → 재빌드 → 재배포)](flow.md#term-172) · [흐름: 딥러닝 학습](flow.md#term-094) · [흐름: 라이프루프](flow.md#term-098) · [흐름: 루프 기본 사이클](flow.md#term-129) · [흐름: 루프 도입 첫 주](flow.md#term-131) · [흐름: 백엔드 처리](flow.md#term-090) · [흐름: 분류 모델 고르기](flow.md#term-168) · [흐름: 분류 모델 학습 (세 렌즈 공통)](flow.md#term-167) · [흐름: 서버 3단 구조](flow.md#term-089) · [흐름: 카드뉴스 루프 (2층 검사)](flow.md#term-130) · [흐름: 쿠버네티스 큰 주방 지도 (클러스터→노드→Pod→컨테이너)](flow.md#term-191)

---

AX:IS(액시스) — AI Transformation 시대를 함께 준비하고, Inspire & Share 로 함께 성장하는 AI 동아리
