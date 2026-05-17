# non-ai-design-skill-pack

[English](README.md)

AI 코딩 에이전트용 범용 디자인 스킬 팩입니다.

`non-ai-design-skill-pack`은 AI 코딩 에이전트가 일반적인 AI 생성물처럼 보이는 UI가 아니라, 의도적이고 제품 맥락에 맞으며 접근성과 유지보수성을 갖춘 웹 인터페이스를 만들도록 돕는 Markdown 기반 지침 모음입니다.

프론트엔드 코딩, UI 리디자인, 인터페이스 리뷰, 디자인 시스템 가이드, 랜딩페이지, 대시보드, SaaS 제품, 브라우저 확장 프로그램 페이지, 포트폴리오 사이트, 기술형 도구, AI 보조 웹앱 제작에 사용할 수 있습니다.

## 왜 필요한가

AI가 생성한 UI는 다음과 같은 문제를 자주 보입니다.

- 흔한 보라색-파란색 그라데이션
- 반복적인 벤토 그리드
- 무작위 글래스모피즘
- 장식용 신경망 그래픽
- 가짜 대시보드 수치
- 약한 정보 위계
- 과도하게 둥근 카드
- 기본 컴포넌트 라이브러리 느낌
- 부족한 모바일 대응
- hover, focus, loading, empty, error 상태 누락
- 실제 제품 디자인이 아니라 프롬프트 출력물처럼 보이는 인터페이스

이 스킬 팩은 AI 에이전트에게 더 엄격한 디자인 및 구현 기준을 제공하여, 생성된 UI가 명확한 시각적 방향, 일관된 디자인 토큰, 사용 가능한 구조, 접근 가능한 상호작용, 검토 가능한 품질 기준을 갖추도록 합니다.

## 핵심 개념

좋은 AI 보조 디자인은 프롬프트 결과물이 아니라 제품 결정처럼 보여야 합니다.

좋은 인터페이스는 다음을 갖춰야 합니다.

- 구체적인 디자인 방향
- 명확한 제품 논리
- 강한 시각적 위계
- 일관된 시각 토큰
- 접근 가능한 컨트롤
- 반응형 동작
- 실제적인 컴포넌트 상태
- 유지보수 가능한 프론트엔드 코드

목표는 모든 인터페이스를 화려하게 만드는 것이 아닙니다. 목표는 모든 인터페이스가 사람이 의도적으로 설계한 것처럼 보이고, 일관되며, 유용하고, 제품 맥락에 맞게 느껴지도록 만드는 것입니다.

## 파일 구조

```txt
non-ai-design-skill-pack/
├─ README.md
├─ README-KR.md
├─ SKILL.md
├─ DESIGN.md
├─ references/
│  └─ UI_REVIEW_CHECKLIST.md
└─ examples/
   ├─ vibe-coding-platform.html
   ├─ saas-analytics-dashboard.html
   └─ developer-newsletter.html
```

## 파일 설명

### `SKILL.md`

핵심 에이전트 스킬 파일입니다.

AI 코딩 에이전트에게 다음 작업을 요청할 때 사용합니다.

- 웹 인터페이스 제작
- 기존 UI 리디자인
- 프론트엔드 완성도 개선
- AI스러운 디자인 제거
- 실사용 가능한 프론트엔드 코드 생성
- 인터페이스 품질 검토
- 디자인 시스템을 코드에 적용

이 파일은 다음 항목을 정의합니다.

- 스킬이 활성화되어야 하는 상황
- 피해야 할 디자인 실수
- 디자인 방향을 선택하는 방법
- 레이아웃, 타이포그래피, 색상, 컴포넌트, 모션 구성 방식
- 접근성과 유지보수성을 고려한 프론트엔드 구현 기준
- 최종 출력 전 결과물을 검토하는 방법

### `DESIGN.md`

디자인 시스템 가이드 파일입니다.

이 파일은 AI 에이전트가 지속적으로 따라야 할 시각 정체성을 제공합니다. 포함 항목은 다음과 같습니다.

- 색상 토큰
- 타이포그래피 토큰
- 간격 토큰
- radius 값
- shadow 값
- motion 타이밍
- 컴포넌트 스타일 규칙
- 레이아웃 원칙
- 접근성 규칙
- 반응형 동작
- 다크 모드 가이드

기본 디자인 시스템 이름은 **Crafted Engineering**입니다.

다음 작업에 특히 적합합니다.

- 기술 제품
- 엔지니어링 도구
- 개발자 도구
- AI 제품 인터페이스
- 데이터 중심 대시보드
- 브라우저 확장 프로그램 페이지
- 포트폴리오 사이트
- 문서형 웹사이트
- 완성도 높은 MVP 인터페이스

다른 브랜드, 제품, 시각 방향에 맞게 사용하려면 `DESIGN.md`를 수정하거나 교체하면 됩니다.

### `references/UI_REVIEW_CHECKLIST.md`

구조화된 UI 리뷰 체크리스트입니다.

AI 에이전트에게 다음 항목을 감사하도록 요청할 때 사용합니다.

- UI 품질
- 제품 적합성
- 시각적 위계
- 접근성
- 반응형 대응
- 컴포넌트 상태
- 코드 품질
- 성능
- AI스러운 디자인 문제
- 릴리즈 준비 상태

### `examples/`

이 스킬 팩을 사용해 완성한 예시 페이지 모음입니다.

완성된 구현이 어떤 모습인지 — 디자인 결정, 토큰 사용, 컴포넌트 상태, 반응형 레이아웃이 실제로 어떻게 적용되는지 — 참고 자료로 사용합니다.

- [`vibe-coding-platform.html`](examples/vibe-coding-platform.html) — 바이브코딩 강좌 플랫폼 랜딩페이지. Crafted Engineering 디자인 시스템을 처음부터 끝까지 적용한 단일 HTML 파일.
- [`saas-analytics-dashboard.html`](examples/saas-analytics-dashboard.html) — SaaS 분석 대시보드. 사이드바 + 워크스페이스 레이아웃으로 KPI 카드, 매출 추이 차트, 플랜별 비중, 정렬·필터 가능한 고객 테이블을 포함한 단일 HTML 파일.
- [`developer-newsletter.html`](examples/developer-newsletter.html) — 개발자 뉴스레터 랜딩페이지. 에디토리얼-아카이브 레이아웃으로 이메일 구독 폼, 샘플 이슈 프리뷰, 4개 콘텐츠 영역, 추천사, 이슈 아카이브 리스트를 포함한 단일 HTML 파일.

## 권장 사용법

### 1. 프로젝트에 스킬 팩 추가

AI 코딩 도구가 읽을 수 있는 위치에 폴더를 둡니다.

예시:

```txt
your-project/
├─ app/
├─ components/
├─ public/
├─ package.json
└─ non-ai-design-skill-pack/
   ├─ SKILL.md
   ├─ DESIGN.md
   └─ references/
      └─ UI_REVIEW_CHECKLIST.md
```

### 2. AI 에이전트에게 사용 지시

예시 프롬프트:

```txt
Use `non-ai-design-skill-pack/SKILL.md` and `non-ai-design-skill-pack/DESIGN.md`.

Redesign this landing page so it no longer looks like a generic AI-generated SaaS template. Keep the existing product concept, but improve hierarchy, typography, layout, component states, accessibility, and responsive behavior.

After implementation, review the result using `references/UI_REVIEW_CHECKLIST.md`.
```

### 3. 구현 또는 리뷰 단계에서 적용

좋은 작업 예시는 다음과 같습니다.

```txt
Build a polished technical dashboard using this skill pack.
```

```txt
Refactor this React component to follow DESIGN.md and remove generic AI-looking visual patterns.
```

```txt
Create a landing page for a browser extension. Use the Crafted Engineering visual direction but adjust it for a compact utility product.
```

```txt
Audit this UI using UI_REVIEW_CHECKLIST.md and return prioritized fixes.
```

## 설치 방식

AI 도구마다 프로젝트 지침을 읽는 방식이 다릅니다. 사용하는 워크플로에 맞게 선택하면 됩니다.

### 일반 프로젝트 방식

대부분의 채팅형 또는 IDE 기반 AI 에이전트에서 사용할 수 있습니다.

```txt
1. 프로젝트 안에 스킬 팩을 둡니다.
2. 프롬프트에서 `SKILL.md`, `DESIGN.md`, `UI_REVIEW_CHECKLIST.md`를 참조하도록 지시합니다.
3. AI에게 해당 파일들을 엄격하게 따르라고 요청합니다.
```

### Agent Skills 스타일

Agent Skills 방식의 폴더를 지원하는 도구에서는 다음처럼 둘 수 있습니다.

```txt
skills/
└─ non-ai-design/
   ├─ SKILL.md
   ├─ DESIGN.md
   └─ references/
      └─ UI_REVIEW_CHECKLIST.md
```

### 프로젝트 지침 방식

스킬 자동 로딩을 지원하지 않는 도구에서는 다음 순서로 붙여넣거나 첨부합니다.

```txt
Use this order:
1. Paste or attach `SKILL.md`.
2. Paste or attach `DESIGN.md`.
3. Use `UI_REVIEW_CHECKLIST.md` only during review or refinement.
```

## 권장 워크플로

### 제작 워크플로

```txt
1. 제품 맥락을 정의합니다.
2. 하나의 시각 방향을 선택합니다.
3. DESIGN.md를 읽습니다.
4. 레이아웃과 정보 구조를 계획합니다.
5. 인터페이스를 구현합니다.
6. 실제 컴포넌트 상태를 추가합니다.
7. 모바일, 태블릿, 데스크톱 동작을 점검합니다.
8. UI 리뷰 체크리스트를 실행합니다.
9. 여전히 일반적인 AI 생성물처럼 보이는 부분을 수정합니다.
```

### 리뷰 워크플로

```txt
1. 인터페이스를 시각적으로 점검합니다.
2. 흔한 AI 디자인 패턴을 찾습니다.
3. 접근성을 점검합니다.
4. 반응형 동작을 점검합니다.
5. 컴포넌트 상태를 점검합니다.
6. 코드 유지보수성을 점검합니다.
7. 구체적인 변경안을 제안합니다.
8. 수정 사항을 적용합니다.
```

## 피해야 할 디자인

명확한 제품상 이유가 없다면 다음 패턴을 피합니다.

- 보라색-파란색 그라데이션 히어로 섹션
- 무작위 글래스 카드
- 흔한 AI 뇌 그래픽
- 장식용 신경망 선
- 반복적인 아이콘 카드 그리드
- 근거 없는 glow 효과
- 가짜 분석 패널
- placeholder만 있는 폼
- label이 없는 input
- 낮은 대비의 텍스트
- 과도한 둥근 모서리
- 별도 조정 없이 사용하는 기본 컴포넌트 라이브러리 스타일
- 구조 없는 벤토 레이아웃
- 어떤 제품에도 붙일 수 있는 랜딩페이지 문구

## 권장하는 디자인

다음을 사용합니다.

- 제품 맥락에 맞는 시각 논리
- 명확한 정보 구조
- 의도적인 타이포그래피
- 토큰 기반 스타일링
- 접근 가능한 컨트롤
- 실제 컴포넌트 상태
- 목적이 있는 모션
- 유용한 정보 밀도
- 강한 레이아웃 리듬
- 현실적인 콘텐츠 구조
- 유지보수 가능한 프론트엔드 아키텍처

## 디자인 철학

이 스킬 팩은 실용적인 원칙을 따릅니다.

> 장식에서 시작하지 말고, 인터페이스의 역할에서 시작합니다.

스타일링 전에 다음을 정의합니다.

- 이 인터페이스가 무엇을 위한 것인지
- 누가 사용하는지
- 사용자가 가장 먼저 해야 할 일이 무엇인지
- 어떤 감정적 톤이 적절한지
- 무엇이 기억에 남아야 하는지
- 무엇은 보이지 않게 기능 중심으로 남아야 하는지

그다음 하나의 명확한 시각 방향을 선택하고 일관되게 실행합니다.

## 기본 시각 방향

포함된 `DESIGN.md`는 **Crafted Engineering** 시각 방향을 사용합니다.

이 방향은 다음 요소를 결합합니다.

- 따뜻한 에디토리얼 표면
- 절제된 기술형 타이포그래피
- 강한 레이아웃 리듬
- 정밀한 데이터 표현
- 최소한의 accent color
- 접근 가능한 상호작용 상태
- 실사용을 고려한 컴포넌트 규칙

기술 제품, 엔지니어링 인터페이스, 대시보드, 문서형 웹사이트, 개발자 도구, 브라우저 확장 프로그램, AI 보조 유틸리티에 특히 잘 맞습니다.

## `DESIGN.md` 커스터마이징

다른 브랜드에 맞추려면 다음 항목을 수정합니다.

- `name`
- `description`
- `colors`
- `typography`
- `spacing`
- `radius`
- `shadow`
- `motion`
- `components`
- Markdown 설명 섹션

권장 규칙은 다음과 같습니다.

```txt
먼저 디자인 방향을 바꾸고, 그다음 토큰을 조정합니다.
색상이나 폰트만 무작위로 바꾸고 설명을 그대로 두지 않습니다.
```

## 예시 프롬프트: 전체 페이지 제작

```txt
Use the non-ai-design skill pack.

Task:
Create a responsive landing page for a technical browser extension.

Requirements:
- Use `SKILL.md` as the main design and implementation instruction.
- Use `DESIGN.md` as the visual system.
- Avoid generic AI/SaaS visual clichés.
- Include hero, product explanation, feature section, workflow section, proof section, and final CTA.
- Implement responsive behavior for mobile, tablet, and desktop.
- Include hover, focus, loading, empty, and error states where relevant.
- After building, review the result using `references/UI_REVIEW_CHECKLIST.md`.
```

## 예시 프롬프트: UI 리팩토링

```txt
Use the non-ai-design skill pack.

Refactor the current React UI so it feels more product-specific and less AI-generated.

Keep:
- Existing core functionality
- Existing routing
- Existing data flow

Improve:
- Layout hierarchy
- Typography
- Color system
- Component spacing
- Button states
- Form accessibility
- Mobile responsiveness
- Empty/loading/error states

Follow `DESIGN.md`.
Use `UI_REVIEW_CHECKLIST.md` before finalizing.
```

## 예시 프롬프트: 디자인 리뷰

```txt
Use `references/UI_REVIEW_CHECKLIST.md`.

Review this interface and return:
1. Overall status
2. Design thesis
3. Top 5 issues by severity
4. Accessibility problems
5. Responsive problems
6. Anti-AI aesthetic problems
7. Concrete implementation fixes

Do not give vague design feedback. Every issue must include a specific fix.
```

## 예시 프롬프트: 대시보드 제작

```txt
Use the non-ai-design skill pack.

Build a responsive analytics dashboard for a technical product.

Requirements:
- Use `DESIGN.md` for visual tokens.
- Avoid decorative fake metrics.
- Include realistic loading, empty, and error states.
- Use tabular numbers for metrics.
- Right-align numeric table values.
- Include filters and clear active states.
- Make the mobile layout usable, not just compressed.
- Review the final result using `UI_REVIEW_CHECKLIST.md`.
```

## 예시 프롬프트: 브라우저 확장 프로그램 랜딩페이지

```txt
Use the non-ai-design skill pack.

Create a landing page for a browser extension.

The page should feel like a compact, trustworthy technical utility rather than a generic SaaS landing page.

Include:
- Hero section
- Extension workflow
- Feature explanation
- Browser compatibility section
- Privacy/security section
- FAQ
- Final CTA

Follow `DESIGN.md`.
Avoid generic AI visual patterns.
```

## 호환성

이 스킬 팩은 의도적으로 순수 Markdown으로 구성되어 있습니다.

다음 방식으로 사용할 수 있습니다.

- 스킬 폴더를 지원하는 AI 코딩 에이전트
- IDE 기반 AI 어시스턴트
- 채팅형 AI 도구
- 프로젝트 지침 파일
- 저장소 단위 코딩 가이드라인
- 수동 복사·붙여넣기 워크플로

사용 중인 도구가 자동 스킬 로딩을 지원하지 않는다면, 필요한 파일 내용을 프롬프트나 프로젝트 지침에 붙여넣으면 됩니다.

## 권장 사용 사례

적합한 작업은 다음과 같습니다.

- 랜딩페이지
- SaaS 대시보드
- 관리자 패널
- 개발자 도구
- 브라우저 확장 프로그램 페이지
- 포트폴리오 사이트
- AI 제품 인터페이스
- 기술 문서 사이트
- 데이터 중심 인터페이스
- 엔지니어링 도구
- MVP UI 완성도 개선
- 바이브코딩 결과물 개선

덜 적합한 작업은 다음과 같습니다.

- 순수 백엔드 작업
- 일반 글쓰기
- 브랜드 아이덴티티 전체 설계
- 인쇄 디자인
- 모션 중심 크리에이티브 코딩
- 별도 플랫폼 규칙이 없는 네이티브 모바일 앱 디자인

## 리뷰 기준

완성된 결과물은 세 가지 테스트를 통과해야 합니다.

### 제품 테스트

사용자가 제품이 무엇인지, 다음에 무엇을 해야 하는지 이해할 수 있어야 합니다.

### 디자인 테스트

디자이너가 시각적 방향을 파악하고, 그 방향이 일관되게 적용되었는지 확인할 수 있어야 합니다.

### 엔지니어링 테스트

개발자가 임의의 스타일링 결정을 역추적하지 않고도 코드를 유지보수할 수 있어야 합니다.

## 한계

이 스킬 팩은 다음을 대체하지 않습니다.

- 실제 브랜드 전략
- 완전한 제품 디자인 프로세스
- 사용자 리서치
- 실제 보조공학 도구를 활용한 접근성 테스트
- 브라우저 기반 시각 QA
- 성능 프로파일링
- 숙련된 디자이너의 디자인 리뷰

이 스킬 팩은 AI 보조 프론트엔드 디자인과 리뷰를 위한 실용적인 지침 계층입니다.

## 배포 전 체크리스트

저장소를 공개하기 전에 다음을 확인합니다.

- `README.md`가 존재합니다.
- 한국어 문서가 필요하다면 `README-KR.md`가 존재합니다.
- `SKILL.md`에 올바른 front matter가 있습니다.
- `DESIGN.md`에 명확한 디자인 방향과 일관된 토큰이 있습니다.
- `references/UI_REVIEW_CHECKLIST.md`가 포함되어 있습니다.
- 예시 프롬프트가 정확합니다.
- 라이선스를 선택했습니다.
- 비공개 프로젝트 정보가 남아 있지 않습니다.
- 유료 폰트, 비공개 자산, 제한된 브랜드 자산이 포함되어 있지 않습니다.

## 라이선스

MIT License. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하십시오.

## 크레딧

이 스킬 팩은 현대적인 Agent Skills 워크플로, AI 코딩 에이전트 지침 패턴, 디자인 시스템 문서화 방식, 프론트엔드 UI 리뷰 체크리스트에서 영감을 받아 구성되었습니다.

특정 AI 모델이나 특정 벤더에 종속되지 않습니다.
