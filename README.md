# 아동복 사이즈 추천

아이의 키와 몸무게를 입력하면 브랜드별 추천 사이즈를 보여주는 페이지입니다.

👉 https://chickchod.github.io/size-chart/

## 브랜드 데이터 수정

브랜드별 사이즈표는 `index.html`의 `<script>` 맨 위쪽에 있는 `BRANDS` 배열에 있습니다.

- `h` = 키 cm 범위 `[최소, 최대]`
- `w` = 몸무게 kg 범위 `[최소, 최대]`
- `null` = 정보 없음
