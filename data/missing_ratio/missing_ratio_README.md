# missing_ratio

`missing_ratio`는 pe_data의 데이터에서 결측치를 채운 csv를 저장하는 디렉토리입니다.

결측치는 각 column에서 특정 조건에 해당되는 데이터로 채워집니다.

## 목록
각 목록은 실행되면 생성되는 데이터입니다.

1. extra_feature(PE_missing_appear).csv

    - 각 column에서 가장 많이 등장한 데이터를 결측치로 채웁니다.

2. extra_feature(PE_missing_max).csv

    - 각 column에서 가장 큰 데이터를 결측치로 채웁니다.

3. extra_feature(PE_missing_mean).csv

    - 각 column에서 평균 데이터로 결측치로 채웁니다.

4. extra_feature(PE_missing_min).csv

    - 각 column에서 가장 작은 데이터를 결측치로 채웁니다.

5. extra_feature(PE_missing_zero).csv

    - 0을 결측치로 채웁니다.

6. missing_data_ratio_heatmap.png

    - 결측치 비율을 heatmap으로 표현한 이미지입니다.