# 통합
### 팀 전체 의견을 통합


## File introduction
### [스타벅스_메가커피 입지비교.ipynb](https://github.com/CodeDiary18/Commercial-Districts-Analysis/blob/main/%ED%86%B5%ED%95%A9/%EC%8A%A4%ED%83%80%EB%B2%85%EC%8A%A4_%EB%A9%94%EA%B0%80%EC%BB%A4%ED%94%BC%20%EC%9E%85%EC%A7%80%EB%B9%84%EA%B5%90.ipynb)
#### 요약
* data라는 폴더에서 분석하고 싶은 도시의 스타벅스와 메가커피 매장에 대한 분석


#### 전처리
* data라는 폴더에서 분석하고 싶은 도시의 csv파일을 불러와서 데이터프레임으로 저장하고 필요없는 열을 제거함
* 불러온 데이터프레임에서 스타벅스와 메가커피에 대해서 다시 데이터를 정리해서 저장


#### 분석




### [카페 상권분석.ipynb](https://github.com/CodeDiary18/Commercial-Districts-Analysis/blob/main/CodeDiary18/%EC%B9%B4%ED%8E%98%20%EC%83%81%EA%B6%8C%EB%B6%84%EC%84%9D.ipynb)
#### 요약
* data라는 폴더에서 분석하고 싶은 도시와 분석하고 싶은 카페 브랜드 2개를 입력받고 그에 대한 매장에 대한 분석


#### 전처리
* data라는 폴더에서 분석하고 싶은 도시의 csv파일을 불러와서 데이터프레임으로 저장하고 필요없는 열을 제거함
* 불러온 데이터프레임에서 입력받은 커피 브랜드 2개에 대해서 다시 데이터를 정리해서 저장


#### 분석
* 막대그래프
  * 도시의 점포수 비교
  * 시군구별 점포수

* 산점도(scatter) : 매장 위치를 위도, 경도로 산점도 찍기
  * 두개의 브랜드
  * 각각 브랜드

* 지도
  * 지도에 circlemarker로 매장 위치 시각화
  * choropleth로 자치구별 매장수 시각화
