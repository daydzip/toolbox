# Toolbox

여러 독립형 HTML 유틸리티를 한곳에 모아두는 저장소입니다.

## 구조

```
toolbox/
├── index.html              # 전체 도구 목록 페이지
└── tools/
    └── <도구명>/
        └── index.html       # 개별 도구
```

## 새 도구 추가하기

1. `tools/<도구명>/index.html` 로 파일을 추가합니다.
2. 루트 `index.html`의 `tools` 배열에 이름, 설명, 경로를 추가합니다.

## 도구 목록

- [예산 비율 계산기](tools/budget-ratio-calculator/) — 월 소득 대비 항목별 예산 비율과 금액을 서로 변환해서 계산합니다.
