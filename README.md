# EMCA
classifying endometrium status &amp; carcinoma grading

# 1. 데이터 수집
: data_preparing.py

## UCEC 데이터

```
Endometrioid/
 --> test sample for histologic_type (by using modeling of classification)
 --> modeling for histologic_grade : train & test
  Grade1/
  Grade2/
  Grade3/
Serous/
Etc_carcinoma/
```

## China 데이터
```
NE/ (normal endometrium)
  Luteal/
  Menstrual/
  Follicular/
EP/ (endometrial polyp)
EH/ (endometrial hyperplasia)
  Simple/
  Complex/
EA (endometrioid adenocarcinoma)

--> modeling for classifying NE/EP/EH/EA: train & test
```

# 2. 전처리
: data_preprocessing.py, china_preprocessing.py, ucec_preprocessing.py
```
image - 파일 형식별로 그림 열기
UCEC 데이터 : .svs
China 데이터 : .JPG

labeling 확인 방법
UCEC 데이터 : 파일명 기반 리스트
China 데이터 : 파일 경로
```

# 3. 전이학습 기반 분류 학습 model 생성 및 검증
```
```

# 4. 시각화 및 결과 제공
```
model별 분류 정확도 
```

# 5. 구글 클라우드
```
model 별 예측 정확도 및 예측 결과 text 제공
```
