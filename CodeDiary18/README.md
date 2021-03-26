# CodeDiary18 폴더

## [Data set](https://github.com/CodeDiary18/Commercial-Districts-Analysis/blob/main/CodeDiary18/data)
[소상공인시장진흥공단_상가(상권)정보](https://www.data.go.kr/data/15012005/fileData.do), [seoul_municipalities_geo_simple.json](https://github.com/CodeDiary18/Commercial-Districts-Analysis/blob/main/CodeDiary18/data/seoul_municipalities_geo_simple.json)

### Data set 저장 위치
* 주피터 노트북이 위치한 곳에 data라는 폴더를 생성
* 다운 받은 <소상공인시장진흥공단_상가(상권)정보>의 csv 파일들을 전부 data 폴더 안에 넣어야 함
* seoul_municipalities_geo_simple.json도 data 폴더 안에 넣어야 함



## File introduction
### [상권 분석.ipynb](https://github.com/CodeDiary18/Commercial-Districts-Analysis/blob/main/CodeDiary18/%EC%83%81%EA%B6%8C%20%EB%B6%84%EC%84%9D.ipynb)
#### 요약
* data라는 폴더에서 서울과 부산의 상권 정보를 불러와 모든 상가에 대해 분석 & 서울과 부산의 스타벅스 매장에 대한 분석


#### 전처리
* data라는 폴더에서 서울과 부산의 상권 정보 csv파일을 불러와서 데이터프레임으로 저장하고 필요없는 열을 제거함


#### 분석
* 소상공인시장진흥공단_상가(상권)정보의 모든 매장
  * 도시별 매장 위도, 경도
  * 도시별 상관계수 시각화
  * 산점도(scatter) : 매장 위도, 경도로 산점도 찍기

* 스타벅스
  * 산점도(scatter) : 스타벅스의 매장 위치를 위도, 경도로 산점도 찍기
  * 막대그래프 : 각 도시별 자치구별 매장 수


### [스타벅스와 메가커피.ipynb](https://github.com/CodeDiary18/Commercial-Districts-Analysis/blob/main/CodeDiary18/%EC%8A%A4%ED%83%80%EB%B2%85%EC%8A%A4%EC%99%80%20%EB%A9%94%EA%B0%80%EC%BB%A4%ED%94%BC.ipynb)
#### 요약
* data라는 폴더에서 분석하고 싶은 도시의 상권 정보를 불러와 스타벅스와 메가커피 매장에 대한 분석


#### 전처리
* data라는 폴더에서 분석하고 싶은 도시의 csv파일을 불러와서 데이터프레임으로 저장하고 필요없는 열을 제거함


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
