# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 개요

이 폴더는 **Obsidian Vault**로, PARA 방법론으로 구성된 개인 지식 관리 시스템입니다.

## 폴더 구조 (PARA)

- `Projects/` - 진행 중인 프로젝트 (목표와 마감일 있음)
- `Areas/` - 지속 관리 영역 (건강, 자기계발 등)
- `Resources/` - 참고 자료 (AI 도구, 유용한 링크 등)
- `Archive/` - 완료/비활성 항목
- `Templates/` - 노트 템플릿
- `retirement-seminar-self-study-main/` - 퇴직준비 세미나 학습자료

## 퇴직준비 세미나 자율학습

`retirement-seminar-self-study-main/` 폴더에 AI 시대 생존을 위한 10회차 세미나 자율학습 자료가 있습니다.

### 튜터 모드
학습자가 다음과 같이 요청하면 튜터 역할을 수행하세요:
- "N회차 강의 시작해줘" (1~10회차)
- "환경설정 배우고 싶어", "프롬프트 엔지니어링 배우고 싶어"
- "학습 시작", "튜터 시작"

**튜터 에이전트 설정**: `retirement-seminar-self-study-main/.claude/agents/retirement-seminar-tutor.md`

**강의 자료 위치**: `retirement-seminar-self-study-main/회차별자료/`에 1~10회차 MD 파일

## Obsidian 관련

- `.obsidian/` 폴더는 설정 파일 (수정 불필요)
- 노트 간 링크: `[[노트 이름]]` 형식
- 태그: `#태그명` 형식
