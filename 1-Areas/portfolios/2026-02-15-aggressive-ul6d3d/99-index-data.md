# 지수 데이터 수집 결과

**수집일시**: 2026-02-15
**데이터 기준일**: 2026-02-14 (주식 지수는 2026-02-13 종가, 금요일 마감)
**상태**: SUCCESS
**검증 기준**: 3개 출처 교차검증, 허용 편차 1% 이내

---

## 주요 지수

| 지수      |         값 | 단위  | 전일 대비  |  검증  |  편차   |
| :------ | --------: | :-: | :----: | :--: | :---: |
| S&P 500 |  6,836.17 | pt  | +0.05% | PASS | 0.00% |
| NASDAQ  | 22,546.67 | pt  | -0.22% | PASS | 0.00% |
| KOSPI   |  5,507.01 | pt  | -0.28% | PASS | 0.00% |
| KOSDAQ  |  1,106.08 | pt  | -1.77% | PASS | 0.00% |

## 환율

| 통화쌍 | 값 | 단위 | 검증 | 편차 |
|:-------|---:|:----:|:----:|:----:|
| USD/KRW | 1,443.30 | KRW | PASS | 0.22% |
| EUR/KRW | 1,709.20 | KRW | PASS | 0.19% |
| JPY/KRW | 9.413 | KRW/JPY | PASS | 0.22% |

---

## 출처 목록

### 1차 데이터 소스
- **Yahoo Finance API** (query1.finance.yahoo.com) - 전 지수/환율 커버
- **Stooq** (stooq.com) - S&P 500, NASDAQ, KOSPI, USD/KRW, EUR/KRW, JPY/KRW
- **Fawaz Ahmed Currency API** (cdn.jsdelivr.net) - USD/KRW, EUR/KRW, JPY/KRW

### 교차검증 결과
- 모든 지수/환율이 출처 간 1% 이내 일치 확인
- 최대 편차: 0.22% (USD/KRW, JPY/KRW)
- KOSDAQ: Stooq 미제공, Yahoo Finance API 복수 쿼리(3회) 동일값 반환으로 보완

---

## 비고

- 주식시장 데이터는 2026-02-13(금) 종가 기준 (2/14 토요일 휴장)
- 환율 데이터는 2026-02-14 기준 (외환시장은 토요일에도 일부 거래)
- 상세 원문 인용은 `index-data.json` 참조
