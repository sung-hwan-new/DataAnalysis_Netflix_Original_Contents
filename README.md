# Netflix 데이터를 통한, 오리지널 콘텐츠 제작 방향 분석

![image](https://github.com/user-attachments/assets/a35aa66d-bde8-4675-b87d-fc7845d78af2)

### 목적
전 세계 OTT 1위, 바로 Nexflix입니다. 한 번쯤 들어봤을 오징어게임도 넷플릭스의 오리지널 시리즈 중 하나입니다. 오징어게임은 공개된 지 3년이 지났음에도 2억 6천만회 시청 수로 영화/TV 부문 1위를 사수하고 있습니다. 이러한 인기에 힘입어 오징어게임 시즌2가 올해 공개된다고 합니다. 다양한 오리지널 시리즈로 전 세계인의 시간을 사로잡는 Netflix, 넷플릭스는 한국을 포함한 다양한 국가에서 오리지널 콘텐츠를 제작하고 있습니다. 캐글에 공개된 데이터를 통해 넷플릭스 오리지널 콘텐츠의 제작 방향을 분석해 보았습니다.

### 문제설정 1: 넷플릭스 오리지널 콘텐츠 제작 방향(장르)
- 가설설정
  - 신규 오리지널 콘텐츠는 드라마 장르로 제작되어야 한다.
- 검증
  - 장르별 평점, 런타임, 작품수 비교
- 결과
  - 넷플릭스는 'MAU 향상'이 주요 운영 전략 중 하나라고 예상
  - 평점 ↑ → 끝까지 시청할 가능성 ↑ → MAU ↑
  - 평점차이는 미미하지만, 런타임이 1.5배 긴 드라마 장르 지속 출시는 MAU 향상에 기여할 것이라고 예상

### 문제설정 2: 넷플릭스 오리지널 콘텐츠 제작 방향(출시요일)
- 가설설정
  - $H0$ 귀무가설: 금요일 콘텐츠 공개와 평점은 관계가 없다.
  - $H1$ 대립가설: 금요일 콘텐츠 공개와 평점은 관계가 있다.
- 검증
  - t-test를 통한 통계적 가설 검증 (유의수준 0.05 / 이분산 가정)
- 결과
  - p-value: 0.0816
  - 기각 조건: 유의수준 ＜ p-value 
  - p-value가 유의수준보다 크므로, 귀무가설 채택.
  - ∴ 금요일 콘텐츠 출시와 평점은 관계가 없다.

### 세부 내용
[<img src="https://img.shields.io/badge/Velog-1EBC8F?style=for-the-badge&logo=velog&logoColor=white" />](https://velog.io/@sung_hwan_new/netflix)
