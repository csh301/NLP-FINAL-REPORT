# NLP PROJECT 10조

### 0. 실행 환경
- 클라우드 서버와 GPU를 제공받는 google `colab` 에서 진행.
- 런타임 유형 하드웨어 가속기 : GPU
- `tensorflow`와 `pytorch` 모두 이용


<br>

### 1. NSMC 네이버 영화 리뷰 데이터 감정 분석

`NSMC_KOELECTRA.ipynb`  
KOELECTRA 모델 사용

- <b>실행 방법</b>  
<t>1.  모든 셀 실행을 통해 <b>1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환</b> 가능.


- <b>데이터 출처</b>  
<t>[https://github.com/e9t/nsmc.git](https://github.com/e9t/nsmc.git)


- <b>참고문헌 및 코드</b>    
<t>[KoELECTRA 참고 소스 코드: https://blog.naver.com/horajjan/221739630055](https://blog.naver.com/horajjan/221739630055)

<br>


### 2. Friends 영화 대본 데이터 감정 분석

`frineds_electra.ipynb`  
ELECTRA 모델 사용

- <b>실행 방법</b>  
<t>1.  `friends_train.json`, `friends_dev.json`, `friends_test.json`을 압축한 파일 `Friends.zip`을 업로드한 후 unzip 실행  
<t>2.  이후 모든 셀 실행을 통해 <b>1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환</b> 가능.


- <b>데이터 출처</b>  
<t>[http://doraemon.iis.sinica.edu.tw/emotionlines/index.html](http://doraemon.iis.sinica.edu.tw/emotionlines/index.html)


- <b>참고문헌 및 코드</b>  
<t>[모델 학습 관련 소스코드 : https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP](https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP)


<br>

### 3. 다른 모델 및 학습방법 시도  

[trials readme로 이동](https://github.com/jiwonny/nlp_emotion_classification/tree/master/trials)  

- <b>참고 문헌 및 코드</b>  
<t>[LSTM 소스 코드 :  https://wikidocs.net/44249](https://wikidocs.net/44249)  
<t>[BERT 소스 코드 :  https://zzaebok.github.io/deep_learning/nlp/Bert-for-classification/](https://zzaebok.github.io/deep_learning/nlp/Bert-for-classification/)  
<t>[KoBERT 소스 코드 : https://github.com/SKTBrain/KoBERT](https://github.com/SKTBrain/KoBERT)  


