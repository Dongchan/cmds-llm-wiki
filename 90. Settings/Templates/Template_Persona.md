---
type: persona
aliases:
  - "{Name} Persona"
description: "Compiled persona of {Name} — worldview, voice, heuristics, and a verbatim quote bank grounded in Raw Sources, for perspective-taking and simulated consultation."
author:
  - "{Agent}"
model: "{exact-session-model-id}"
effort: "{actual-effort-or-default}"
date created: { date }
date modified: { date }
tags:
  - persona
  - "{person-slug}"
personaOf: "[[{Entity Name}]]"
personaMaturity: seed
personaDomains:
  - "{domain the persona can credibly speak on}"
source:
  - "[[{raw source}]]"
related:
  - "[[MOC-Personas]]"
confidence: low
layer: personas
explored: false
claimType: interpretive
evidenceScope: single-source
verificationStatus: unverified
---

# Persona-{Name}

> [!tip] Key Insight
> {이 인물의 사고·발화를 한 문장으로 — 근거 있는 본질만}

## Identity Anchor

[[{Entity Name}]] — {2~3줄. 사실 기록은 entity 페이지가 담당하고, 이 카드는 "어떻게 사고하고 말하는가"만 담는다.}

## Worldview & Core Positions

- **{입장 제목}** ({YYYY-MM-DD}): {입장 요약} — [[{raw source}]]

## Voice & Style

- {어조·수사 패턴·자주 쓰는 어휘 — 반드시 Quote Bank 의 실측 인용에서 도출}

## Heuristics

- {이 인물이 반복 적용하는 판단 규칙 — 각 항목에 근거 source}

## Quote Bank

> [!quote] {주제} ({YYYY-MM-DD}, [[{raw source}]])
> {verbatim 인용 — Raw Source `## Original Content` 에서 grep 대조 가능해야 함}

## Position Timeline

| Date | Position | Source |
|------|----------|--------|
| {YYYY-MM-DD} | {입장} | [[{raw source}]] |

## Simulation Boundary

> [!warning] Simulation Boundary
> 이 페르소나는 {N}개 Raw Source ({기간})의 발화만 근거로 한다. 다음은 **커버하지 않는다**: {미커버 주제}. 시뮬레이션 시 이 경계 밖 주제에 대한 발화를 생성하지 말 것 — "이 페르소나의 증거 범위 밖" 이라고 답한다. 실존 인물의 견해를 날조하는 것은 인용 날조와 같은 급의 실패다.

## Accumulation Log

- {YYYY-MM-DD} · [[{raw source}]] → {추가된 것: 인용 N개, 입장 1개, …}
