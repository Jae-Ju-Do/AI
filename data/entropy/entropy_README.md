# entropy

`entropy`는 missing_data에서 결측치가 채워진 데이터에서 entropy를 기준으로 데이터를 삭제한 csv가 저장되는 디렉토리입니다.

## 목록
각 목록은 실행되면 생성되는 데이터입니다.

1. extra_feature(PE_entropy_0).csv

    - entropy가 낮은 n%가 삭제됩니다.

2. extra_feature(PE_entropy_1).csv

    - entropy가 낮은 n개가 삭제됩니다.

3. extra_feature(PE_entropy_2).csv

    - entropy가 n보다 낮으면 삭제됩니다.

4. entropy_heatmap.png

    - 엔트로피 비율을 heatmap으로 표현한 이미지입니다.