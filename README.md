# dongne-mart-data

우리동네 마트 장보기(토스 미니앱) 정적 데이터 호스트.

- `prices.json` — 한국소비자원 참가격 공공API 기반 생필품 최저가 비교 데이터
- 주 1회 갱신(파이프라인: `mart-price/pipeline/build_prices.py` → `curate_staples.py`)
- 출처: data.go.kr 데이터셋 3043385 (한국소비자원 생필품 가격정보)
