# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 개요

이 폴더는 **Obsidian Vault**로, PARA 방법론으로 구성된 개인 지식 관리 시스템입니다.

## 폴더 구조 (PARA)

```
E:\Vault
├── Projects/       # 진행 중인 프로젝트 (목표와 마감일 있음)
├── Areas/          # 지속 관리 영역 (건강, 자기계발 등)
├── Resources/      # 참고 자료 (AI 도구, 유용한 링크 등)
├── Archive/        # 완료/비활성 항목
├── Templates/      # 노트 템플릿
└── retirement-seminar-self-study-main/  # 퇴직준비 세미나 학습자료
```

## 퇴직준비 세미나 자율학습

`retirement-seminar-self-study-main/` 폴더에 10회차 세미나 자료가 포함되어 있습니다.

### 튜터 모드 시작
학습자가 다음과 같이 요청하면 튜터 역할을 수행하세요:
- "1회차 강의 시작해줘" / "2회차 강의 시작해줘"
- "환경설정 배우고 싶어" / "프롬프트 엔지니어링 배우고 싶어"
- "학습 시작" / "튜터 시작"

### 회차별 학습자료 위치
- `retirement-seminar-self-study-main/회차별자료/1회차_오리엔테이션_환경설정.md`
- `retirement-seminar-self-study-main/회차별자료/2회차_프롬프트_엔지니어링_기초.md`
- ... (3~10회차)

### 튜터 에이전트 설정
- 에이전트 정의: `retirement-seminar-self-study-main/.claude/agents/retirement-seminar-tutor.md`

## Obsidian 관련 참고사항

- `.obsidian/` 폴더는 Obsidian 설정 파일 (수정 불필요)
- 노트 간 링크: `[[노트 이름]]` 형식 사용
- 태그: `#태그명` 형식 사용
