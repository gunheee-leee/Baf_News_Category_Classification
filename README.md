# 뉴스 카테고리 분류
![image](https://github.com/gunheee-leee/Baf_News_Category_Classification/assets/143998370/fcecd4b4-894f-4080-a54e-3c2b2a714042)

## 1. 전처리
![image](https://github.com/gunheee-leee/Baf_News_Category_Classification/assets/143998370/2abeeb77-f1b0-4763-bc2d-98969a126efa)
1. 정규표현식을 활용하여 기사 내의 \t, \n 등의 특수문자, 탭, 개행문자들을 제거해주었다.
2. Okt 형태소 분석기를 사용하여 뉴스 기사를 분류 하는 데에 큰 영향을 미치는 명사, 동사, 형용사만 태깅해주었다.
3. TF-IDF 벡터화를 통해 희소문자의 가중치는 크게 주고, 자주 나타나는 문자에는 가중치를 적게 두어 성능을 높여주었다.
## 2. 나이브 베이즈 분류기
![image](https://github.com/gunheee-leee/Baf_News_Category_Classification/assets/143998370/39b75d90-64a5-4802-9f2d-97a86f878066)
1. 베이즈 정리를 기반으로 한 분류기
2. 문서 분류 문제의 경우 좋은 성능을 보임
3. 라플라스 스무딩을 적용해 분류 정확도를 높임
## 2-1. 나이브 베이즈 실제 적용 결과
![image](https://github.com/gunheee-leee/Baf_News_Category_Classification/assets/143998370/709c2434-3b69-4a23-b7b3-512800b72a9c)
![image](https://github.com/gunheee-leee/Baf_News_Category_Classification/assets/143998370/3f071893-132f-468f-93c6-9605b097a4fc)
