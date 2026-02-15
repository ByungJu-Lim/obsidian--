# CLAUDE

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 저장소 개요

퇴직준비자 임병주의 **Obsidian Vault**. 연구 프로젝트 관리, 퇴직연금 포트폴리오 분석, AI 활용 학습 자료를 포함한다.

## PARA 폴더 구조

```
0-Projects/    # 진행 중인 프로젝트 (AI담수, 고체연료, 복합에너지과제, honeypot, 블로그)
1-Areas/       # 지속 관리 영역 (portfolios - 퇴직연금, retirement-seminar-self-study)
2-Resources/   # 참고 자료 (학습 노트, 프롬프트, 온톨로지 등)
3-Archives/    # 비활성 항목
```

새 파일/폴더 생성 시 반드시 PARA 분류에 맞는 위치에 배치한다.

## 주요 하위 프로젝트

### 퇴직연금 포트폴리오 (`1-Areas/portfolios/`)
- DC형 퇴직연금 펀드 분석 결과가 날짜별 폴더로 저장됨
- 관련 스킬: `investments-portfolio:*` 시리즈 (fund-portfolio, data-updater 등)
- 펀드 데이터는 JSON 형식 (`fund_data.json`, `fund_fees.json`, `fund_classification.json`)

### 퇴직준비 세미나 (`1-Areas/retirement-seminar-self-study/`)
- 10회차 AI 활용 세미나 자율학습 자료 (저자: 차백동, KIMM)
- 자체 CLAUDE.md와 AI 튜터 에이전트 포함 (`.claude/agents/retirement-seminar-tutor.md`)
- "N회차 강의 시작해줘"로 튜터 모드 시작

### 연구 프로젝트 (`0-Projects/`)
- **AI담수**: AI 에이전트 기반 담수화 연구 (KIMM 3차년도)
- **고체연료**: 기관별 연구내용 및 성과활용방안
- **복합에너지과제**: RFP 분석, 기획보고서, 설비현황

## Obsidian 환경

- 플러그인: obsidian-git, smart-connections, kanban, excalidraw, linter, calendar, table-editor, filename-heading-sync
- 한글 파일명 사용이 일반적 — 경로 처리 시 인코딩 주의
- Markdown 링크에 `[[위키링크]]` 문법 사용

## 언어 및 소통

- 사용자와의 대화, 문서 작성 모두 **한국어** 사용
- 기술 용어는 영어 병기 가능 (예: "퇴직연금(DC형)")
