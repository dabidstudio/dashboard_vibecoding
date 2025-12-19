
### 실습용 구글시트 링크
https://docs.google.com/spreadsheets/d/1Q656QCrACV5c2_bg0wu-qqszmJh6jtbuiPv95DRKsWM/copy?

### 구글시트 연계 프롬프트

※ 구글시트 링크가 있는 모든 사용자가 볼 수 있도록 공개 설정이 되어 있어야 함

```md
https://docs.google.com/spreadsheets/d/1Q656QCrACV5c2_bg0wu-qqszmJh6jtbuiPv95DRKsWM/edit?usp=sharing

이 링크의 “가계부” 시트에 있는 데이터를 기반으로 근사한 가계부 대시보드 만들어줘

이 링크의 데이터를 접근하기 위해서 아래 형태로 데이터에 접근해봐
https://docs.google.com/spreadsheets/d/{시트id}/gviz/tq?&sheet={시트명}tq=select *
```


### 구글시트 데이터 활용 샘플
```md
https://docs.google.com/spreadsheets/d/1Q656QCrACV5c2_bg0wu-qqszmJh6jtbuiPv95DRKsWM/gviz/tq?&sheet=가계부tq=select *
```
→ 이걸 브라우저에 붙여서 실행해보면 구글시트 데이터가 다운로드됨



