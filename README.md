# project2_quaero
UBION 금융 빅데이터 4기 Project 2 팀 quaero

### 주요 코드 파일 : 
- preprocess_final                    - 전처리
- raw_normality_test                  - raw data 정규성 검정
- rbscaled_normality_test             - RobustScaler 후 정규성 검정
- feature_selection_rbscaled          - Feature Selection
- dataset1_stratified_win+robust      - 층화표본 dataset1 모델링
- dataset2_stratified_win+robust      - 층화표본 dataset2 모델링
- dataset3_stratified_win+robust      - 층화표본 dataset3 모델링
- dataset4_stratified_win+robust      - 층화표본 dataset4 모델링
- dataset5_stratified_win+robust      - 층화표본 dataset5 모델링

### 주요 csv 파일 : 
- data/데이터셋/dataset1_general.csv                                데이터셋1
- data/데이터셋/dataset2_확장기_ver1.csv                            데이터셋2
- data/데이터셋/dataset3_수축기_ver1.csv                            데이터셋3
- data/데이터셋/dataset4_확장기_ver2.csv                            데이터셋4
- data/데이터셋/dataset5_수축기_ver2.csv                            데이터셋5
- data/유의성/dataset1_raw_logit_vif.csv                            정규성검정
- data/유의성/dataset1_raw_rb_logit_vif.csv                         정규성검정
- data/선택된피처/dataset1_general_raw+robust.csv                   피처셀렉션
- data/층화표본/층화표본_train_dataset1_general_win+robust.csv       리샘플링
- data/테스트셋/Ver1_test_확장기1.csv                                리샘플링
- data/테스트셋/Ver1_test_수축기1.csv                                리샘플링
- data/테스트셋/Ver1_test_확장기2.csv                                리샘플링
- data/테스트셋/Ver1_test_수축기2.csv                                리샘플링
