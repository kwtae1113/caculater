# 전국 날씨 지도

대한민국 17개 시도 행정구역 지도에서 지역을 클릭하면 오늘 날씨 상세와 1주일 예보를 확인할 수 있는 단일 HTML 웹앱입니다.

## 기능

- 실제 시도 경계 기반 대한민국 지도 표시
- 지도 영역 또는 지역 목록 클릭으로 지역 선택
- 현재 기온, 체감온도, 습도, 바람, 강수량, 강수확률 표시
- 오늘 시간대별 상세 예보 제공
- 1주일 예보 탭 제공
- API 키 없이 Open-Meteo 날씨 API 사용

## 사용 방법

`index.html` 파일을 브라우저에서 열면 바로 실행됩니다.

```powershell
Start-Process .\index.html
```

## 데이터 출처

- 지도 경계 데이터: southkorea/southkorea-maps, 통계청 2018 시도 경계 TopoJSON
- 날씨 데이터: Open-Meteo Forecast API

## 파일 구성

```text
caculater/
|-- index.html
|-- README.md
`-- agents.md
```
