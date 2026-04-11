# Google Stitch Prompts — SnapLogic 사이트 리디자인

> 아래 3개 프롬프트를 순서대로 Stitch에 입력하세요.
> 각 라운드에서 생성된 HTML/CSS 코드를 Export하여 저장합니다.

---

## Round 1 — Hero + Trust Bar + Core Modules (Screen 1~3)

```
Design a premium B2B SaaS landing page for "SnapLogic", an automotive E/E (Electrical/Electronic) engineering design platform. The brand identity uses a blue-to-teal gradient (#1A73E8 → #0D9488), with dark navy (#0B1120) accents and clean white surfaces.

Generate 3 connected screens:

SCREEN 1 — HERO SECTION
- Full-viewport hero with a subtle radial gradient background (light blue fading to white)
- Floating decorative orbs/blobs in the background for depth
- Small pill badge at top: "Now available — SnapVex Logic v1.0" with a green pulsing dot
- Large headline (display font, tight letter-spacing): "From architecture design to series production"
- The words "series production" should have a blue-to-teal gradient text effect
- Subtitle text (Korean): "요구사항 정의부터 아키텍처, 와이어링 하네스 설계까지 — 차량 E/E 개발의 전 과정을 하나의 플랫폼으로 통합합니다."
- Two buttons: "Request Demo →" (primary blue, pill shape) and "Watch Video" (outline with play icon)
- Below buttons: a macOS-style window mockup (with red/yellow/green dots in title bar) containing a product screenshot placeholder
- The mockup should have a large shadow and subtle border glow

SCREEN 2 — TRUST BAR
- Thin horizontal strip with light background
- Label: "Trusted by leading E/E engineering teams" (small, uppercase, muted)
- Five company logos in a row (text-only at 35% opacity): Hyundai, BMW, Volvo, Continental, Aptiv
- Subtle top and bottom border lines

SCREEN 3 — CORE MODULES GRID
- Section label: "CORE MODULES" with a short horizontal line before it
- Title: "하나의 플랫폼, 완전한 E/E 설계"
- Description: "회로도의 전기적 의도부터 물리적 하네스 도면까지 — 네 개의 핵심 모듈이 끊김 없이 연결됩니다."
- 4 cards in a responsive grid (2x2 on tablet, 1 column on mobile):
  Card 1: Icon ⚡ on blue bg (#E8F0FE), title "Logic", tag "Design intent" in blue
  Card 2: Icon 🔗 on teal bg (#CCFBF1), title "Integrator", tag "Data sync" in teal
  Card 3: Icon 📐 on orange bg (#FFF3E0), title "Harness Drawing", tag "Documentation" in orange
  Card 4: Icon 🎛️ on purple bg (#EDE9FE), title "Variant / Config", tag "Flexibility" in purple
- Each card has a white background, subtle border, rounded corners (20px), and lifts on hover with a shadow

Typography: Use a modern geometric display font (like Outfit or Inter) for headings, and a clean sans-serif (like Noto Sans KR) for body. Monospace font for technical labels.

Style: Clean, minimal, professional. Think Linear.app meets Stripe — generous whitespace, subtle animations, precision typography.
```

---

## Round 2 — Feature Sections + Workflow (Screen 1~5)

```
Continue the SnapLogic design system (blue #1A73E8, teal #0D9488, orange #E8710A, purple #7C3AED, dark navy #0B1120, white surfaces).

Generate 5 connected screens:

SCREEN 1 — FEATURE: LOGIC MODULE
- Alternating layout: RIGHT side = product screenshot in a rounded frame with shadow, LEFT side = text content
- Section label (blue): "SNAPLOGIC LOGIC"
- Title: "전기적 설계 의도의 Source of Truth"
- Description paragraph about circuit design intent
- 4 checklist items with teal circle checkmarks:
  • 전기적 연결 정의 — 신호가 어떤 디바이스 핀에서 어디로 전달되는지
  • 기능 설계 표현 — 회로도를 통해 시스템 동작을 표현
  • 설계 규칙 및 전기적 제약 정의 — 전압, 전류, 신호 타입
  • 단일 기준 데이터 역할 — 하네스 설계의 신뢰 가능한 소스

SCREEN 2 — FEATURE: INTEGRATOR MODULE
- Same alternating layout but REVERSED (text LEFT, screenshot RIGHT)
- Light gray background (#F0F2F6)
- Section label (teal): "SNAPLOGIC INTEGRATOR"
- Title: "논리 설계와 3D 번들의 동기화"
- 4 checklist items about data integration, harness generation, design consistency, topology filtering

SCREEN 3 — FEATURE: HARNESS DRAWING
- Same layout as Screen 1 (screenshot right)
- Section label (orange): "SNAPLOGIC HARNESS DRAWING"
- Title: "상세 하네스 도면 자동 생성"
- 4 checklist items about drawing generation, plug symbols, bundle diameter, variant filtering

SCREEN 4 — FEATURE: VARIANT / DRC / BOM
- Same layout as Screen 2 (reversed, gray bg)
- Section label (purple): "VARIANT / DRC / BOM"
- Title: "구성 관리와 품질 검증"
- 4 checklist items about variant management, vehicle configuration, DRC rules, BOM reports
- TWO stacked screenshots instead of one

SCREEN 5 — WORKFLOW (DARK SECTION)
- Full-width dark background (#0B1120) with subtle dot grid pattern overlay
- Section label (teal): "DESIGN WORKFLOW"
- Title (white): "설계에서 양산까지, 하나의 흐름"
- Description (muted gray): "각 단계의 데이터가 자동으로 다음 단계에 전달되어, 수작업 변환 없이 일관된 설계를 보장합니다."
- 4 steps in a horizontal row, connected by a gradient line:
  Step 01 (blue): "회로 설계" — circular number badge with colored border
  Step 02 (teal): "토폴로지 통합"
  Step 03 (orange): "하네스 도면"
  Step 04 (purple): "검증 & 출력"
- Each step has a number circle, title (white), and short description (gray)
- On tablet: 2x2 grid, connector line hidden
- On mobile: single column

Make all sections fully responsive. Use consistent spacing and the same design language as the previous round.
```

---

## Round 3 — AI + Stats + Gallery + Integrations + CTA + Footer (Screen 1~5)

```
Continue the SnapLogic design system. Same colors, fonts, and design language.

Generate 5 connected screens:

SCREEN 1 — AI ASSISTANT SECTION
- Soft gradient background (light blue tint → white)
- Two-column layout:
  LEFT column:
    - Section label: "AI ASSISTANT"
    - Title: "자연어로 설계를 탐색하다"
    - Description about MCP-based AI assistant
    - 4 checklist items (teal checkmarks):
      • 와이어 정보 즉시 조회 — 굵기, 색상, 재질, 연결 경로
      • 커넥터별 연결/미연결 와이어 자동 분석
      • 설계 오류 사전 탐지 및 수정 제안
      • OpenAI API 연동 — 사내 LLM 교체 가능
    - Below the list: a product screenshot frame
  RIGHT column:
    - A chat UI mockup (like a messaging app):
      - Header bar with green status dot, "SnapLogic AI" name, "MCP Connected" label
      - Chat bubbles:
        User (blue bg, right-aligned): "BA91 Wire 정보를 부탁해."
        AI (light gray bg, left-aligned): "BA91 와이어는 0.5mm² 굵기이며, 색상은 녹색(G), AVSS 재질입니다.\n출발: UH_BOX 핀 18\n도착: UH_BOX 핀 88" — with inline code styling
        User: "UH_BOX에 연결된 Wire를 보여주고, 연결이 안 된 Wire를 알려줘?"
        AI: "UH_BOX 연결 와이어 12개 확인.\n미연결 와이어 3개 발견 — BA95, BA97, BC01.\nDRC 리포트에 반영할까요?"
      - Rounded corners, subtle shadow, clean white card appearance

SCREEN 2 — STATS SECTION
- White background, centered layout
- Section label (centered): "IMPACT"
- Title (centered): "측정 가능한 설계 혁신"
- 4 stat cards in a row:
  "70%" — 설계 시간 단축 (large blue number, display font)
  "24" — DRC 검증 규칙
  "100%" — 논리-하네스 일관성
  "Zero" — 수동 데이터 변환
- Each card: white bg, subtle border, rounded corners, centered text
- The number should be very large (48px+) in the primary blue color

SCREEN 3 — INTEGRATIONS SECTION
- Light gray background
- Section label: "ECOSYSTEM"
- Title: "기존 도구와 완벽하게 연결"
- 5 integration cards in a single row:
  Git (⤴ icon) — "버전 관리 & 협업" — available
  DXF/DWG (◻ icon) — "CAD 포맷 임포트" — available
  AI/MCP (✦ icon) — "LLM 연동 프로토콜" — available
  Jira (▦ icon) — "프로젝트 관리" — "Coming soon" orange badge
  Creo/SOLIDWORKS (⬡ icon) — "3D CAD 브릿지" — "Coming soon" orange badge
- Cards hover with lift effect

SCREEN 4 — CTA SECTION
- Dark background (#0B1120) with a large radial blue glow behind the content
- Centered layout:
  Title (white): "E/E 설계 워크플로우를 혁신할 준비가 되셨나요?"
  Subtitle (gray): "SnapLogic 데모를 신청하고, 맞춤형 솔루션을 경험하세요."
  Email form: input field (dark translucent bg, white text, placeholder "업무 이메일을 입력하세요") + blue "데모 신청 →" button
  Both input and button have pill shape (border-radius: 100px)

SCREEN 5 — FOOTER
- Dark background (#0B1120), slightly lighter than CTA, with top border line
- 4-column grid:
  Column 1 (wider): Brand name "SnapLogic" + tagline "From architecture design to series production."
  Column 2: "Product" — Logic, Integrator, Harness Drawing, AI Assistant
  Column 3: "Resources" — Gallery, Workflow, Integrations
  Column 4: "Company" — About, Contact
- Bottom bar with copyright "© 2026 SnapLogic" and "Privacy · Terms · Security"
- All text in muted gray/white, links brighten on hover

Ensure all screens are fully responsive and maintain the established design system.
```

---

## 사용 가이드

1. [stitch.withgoogle.com](https://stitch.withgoogle.com) 접속 → Google 로그인
2. **Round 1** 프롬프트 입력 → 생성 → `<>` 아이콘으로 HTML/CSS Export → 저장
3. **Round 2** 프롬프트 입력 → 동일하게 Export
4. **Round 3** 프롬프트 입력 → 동일하게 Export
5. 3개 Export 파일을 Claude에게 전달 → 기존 JS 로직과 병합

## 팁
- **Experimental Mode** (Gemini 2.5 Pro)를 사용하면 더 높은 품질
- 생성 결과가 마음에 들지 않으면 부분 수정 프롬프트로 반복: "Make the hero section taller" / "Use more whitespace in the cards"
- 각 스크린을 개별적으로 Export할 수 있음
