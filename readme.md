
### 구글시트 연계 프롬프트
```md
https://docs.google.com/spreadsheets/d/1Q656QCrACV5c2_bg0wu-qqszmJh6jtbuiPv95DRKsWM/edit?usp=sharing

이 링크의 “가계부” 시트에 있는 데이터를 기반으로 근사한 가계부 대시보드 만들어줘

이 링크의 데이터를 접근하기 위해서 아래 형태로 데이터에 접근해봐
https://docs.google.com/spreadsheets/d/{시트id}/gviz/tq?&sheet={시트명}tq=select *
```


### 구글시트 데이터 활용 샘플
```md
https://docs.google.com/spreadsheets/d/1QL22r4yJhefK8UaPh_uFvlGGNcBpt4ZptK7nbuno3hI/gviz/tq?tq=select%20*)1Q656QCrACV5c2_bg0wu-qqszmJh6jtbuiPv95DRKsWM[/gviz/tq?&sheet=가계부&tq=select *
```
→ 이걸 브라우저에 붙여서 실행해보면 JSON이 나옴






### 데이터 출처

1. 서울시 행정구 공간정보 : https://github.com/southkorea/seoul-maps/tree/master
2. 가계부 데이터 : 제미나이 생성
3. 서울시 연령별 데이터 : https://jumin.mois.go.kr/#
4. 서울 한파쉼터 데이터 : https://data.seoul.go.kr/dataList/OA-21066/S/1/datasetView.do
