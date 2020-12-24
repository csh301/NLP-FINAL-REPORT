# NLP for Digital Finance Engineering Final Test
## (NSMC & Friends Dataset 감정분석) 

### 0. 실행 환경
- google `colab pro` 에서 진행(클라우드 제공 gpu 사용)
- CPU : Intel(R) Xeon(R) CPU @ `2.30GHz` 
- 런타임 유형 하드웨어 가속기 : GPU `tesla v100 or p100`
- 런타임 구성 : 고용량 램 `25.51GB`
- `tensorflow`와 `pytorch` 모두 이용


<br>

### 1. NSMC 네이버 영화 리뷰 데이터 감정 분석

`NSMC_KoElectra_v6.ipynb`  
KOELECTRA 모델 사용(오픈소스 이용)

- <b>실행 방법</b>  
<t>1.  모든 셀 실행을 통해 <b>1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환</b> 가능.


- <b>데이터 출처</b> 

   <t>[NSMC 데이터셋][https://github.com/e9t/nsmc.git](https://github.com/e9t/nsmc.git)
   
   <t>[테스트파일]</b> https://www.kaggle.com/c/korean-sa-competition-dfe610/data

  
- <b>참고문헌 및 코드</b> 

   <t>[박장원님의 KoElectra-small 사용] https://github.com/monologg/KoELECTRA
   
   <t>[KoELECTRA 참고 소스 코드]: https://colab.research.google.com/drive/1JZ-pXlmgRIYHm8yPLYY68Q28l9OYAL6H?usp=sharing

<br>


### 2. Friends 영화 대본 데이터 감정 분석

`Friends(Electra).ipynb`  
ELECTRA 모델 사용(오픈소스 이용)

- <b>실행 방법</b>  
<t>1.  `friends_train.json`, `friends_dev.json`, `friends_test.json`, `en_data.csv`를 압축한 파일 `Friends.zip`을 업로드한 후 unzip 실행  
<t>2.  이후 모든 셀 실행을 통해 <b>1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환</b> 가능.


- <b>데이터 출처</b>

   <t>[Friends 데이터셋][http://doraemon.iis.sinica.edu.tw/emotionlines/index.html](http://doraemon.iis.sinica.edu.tw/emotionlines/index.html)
   
   <t>[테스트파일]  https://www.kaggle.com/c/english-sa-competition-dfe610/data


- <b>참고문헌 및 코드</b>  
<t>[모델 학습 관련 소스코드 : https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP](https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP)


<br>

### 3. LDA 토픽모델링 감정분석 
`Friends(Electra).ipynb`  
Gensim LDA모델 이용(오픈소스 여러개 참조 변형)
[모델구축 관련 참조 : 트위터자료 토픽모델링 https://happy-obok.tistory.com/5](https://happy-obok.tistory.com/5)
[분석모델 관련 참조 : 게임리뷰데이터분석 https://github.com/Jungjaeyoon/gamereviewTextmining](https://github.com/Jungjaeyoon/gamereviewTextmining)
[시각화관련 참조 : https://joyhong.tistory.com/138#topic=0&lambda=1&term=](https://joyhong.tistory.com/138#topic=0&lambda=1&term=)

### 4. 다른 모델 및 학습방법 시도(성능비교 및 참조  

<t>    [※trials readme로 이동※](https://github.com/csh301/NLP-FINAL-REPORT/tree/main/Trials)  

- <b>참고 문헌 및 코드</b>  
<t>[LSTM 소스 코드 :  https://wikidocs.net/44249](https://wikidocs.net/44249)  
<t>[BERT 소스 코드 :  https://zzaebok.github.io/deep_learning/nlp/Bert-for-classification/](https://zzaebok.github.io/deep_learning/nlp/Bert-for-classification/)  
<t>[KoBERT 소스 코드 : https://github.com/SKTBrain/KoBERT](https://github.com/SKTBrain/KoBERT)  


