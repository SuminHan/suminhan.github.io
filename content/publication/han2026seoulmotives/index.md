---
title: '시간대별 OD 데이터로 본 서울 수도권 이동의 잠재 동기'

authors:
  - admin

date: '2026-10-02T00:00:00Z'
publishDate: '2026-10-02T00:00:00Z'

# Hugo Blox (CSL) 출판물 유형. 정식 게재 전이므로 preprint.
publication_types: ['preprint']
publication: '초안 (Working paper), 한국과학영재학교'
publication_short: 'Working paper'

abstract: >-
  통신 기록에 기반한 생활이동 데이터는 행정동 사이 시간대별 이동량을 촘촘히 제공하지만 사람들이 왜 움직였는지는 보여주지 않는다.
  서울시·KT 수도권 생활이동 데이터(2024년으로 학습하고 2025년에 그대로 적용, 노드 481개)를 소수의 잠재 이동 동기가 만들어낸 흐름으로 분해하는 푸아송 모델을 제안한다.
  각 동기는 출발지 분포, 도착지 분포, 평일·주말별 하루 리듬, 거리 감쇠 척도를 갖는다. 학습에는 이동량만 쓰고, 이동 목적·내외국인·거리 라벨은
  평가에만 쓴다. 동기 6개(파라미터 6천 개)로 46만 파라미터 정적 OD 모델과 같은 검증 편차에 도달하고, 8개에서는 12% 낮다.
  통근 동기의 일별 세기는 교통카드 지하철 승하차의 같은 요일 잔차와 0.66–0.77의 상관을 보이며, 불꽃축제와 여의도 집회가 있던 날에는
  모델이 설명하지 못하는 초과 도착이 여의동에 +44–56% 집중된다. 반면 목적 라벨 복원은 시간대만 쓴 예측을 소폭(+1.6%p)만 넘었고,
  단기외국인 동기는 분리되지 않았다. 부수적으로 2023–2026년 서울 출근 거리는 늘지 않았다.

summary: 서울 수도권 시간대별 이동 흐름을 여덟 가지 숨은 동기로 분해하고, 모델이 보지 못한 라벨·교통카드·사건일로 그 동기를 시험했다.

tags:
  - Human Mobility
  - Origin-Destination Flow
  - Mobile Phone Data
  - Poisson Factorization
  - Seoul

featured: true

url_pdf: 'han2026seoulmotives.pdf'
url_code: ''
url_dataset: 'https://data.seoul.go.kr/dataList/OA-22300/F/1/datasetView.do'
url_slides: ''


---

{{< video src="seoul_breathes.mp4" controls="yes" >}}
