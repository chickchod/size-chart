# 아동복 사이즈 가이드

아이의 키와 몸무게를 입력하면 브랜드별 추천 사이즈를 보여주는 페이지입니다.

- 핑도라: https://chickchod.github.io/size-chart/pingdora/
- 오트리: https://chickchod.github.io/size-chart/otree/
- 첫 화면(쇼핑몰 선택): https://chickchod.github.io/size-chart/

## 데이터 수정

각 쇼핑몰 페이지(`pingdora/index.html`, `otree/index.html`)의 `<script>` 맨 위쪽에 설정과 데이터가 있습니다.
두 파일은 서로 독립적이라 **수정할 때는 두 파일을 각각 고쳐야 합니다.**

- `SHOP` = 쇼핑몰 설정
  - `brands: null` → 전체 브랜드 표시
  - `brands: ['더랄라', '멜멜']` → 목록에 있는 브랜드만 표시
- `BRANDS` = 브랜드별 사이즈표
  - `h` = 키 cm 범위 `[최소, 최대]`
  - `w` = 몸무게 kg 범위 `[최소, 최대]`
  - `null` = 정보 없음
