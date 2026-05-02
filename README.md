# 계산기

가볍고 간단한 웹 기반 계산기 애플리케이션입니다.

## 개요

이 프로젝트는 브라우저에서 직접 실행되는 간단한 계산기를 제공합니다. 설치나 서버가 필요 없으며, HTML 파일을 열기만 하면 바로 사용할 수 있습니다.

## 기능

- 기본 산술 연산 (덧셈, 뺄셈, 곱셈, 나눗셈)
- 깔끔하고 직관적인 사용자 인터페이스
- 반응형 디자인
- 외부 의존성 없음

## 시작하기

### 요구사항

- 최신 웹 브라우저 (Chrome, Firefox, Safari, Edge 등)

### 사용 방법

1. **방법 1: 파일 직접 열기**
   - 프로젝트 디렉토리로 이동
   - `index.html` 파일을 더블클릭하여 기본 브라우저에서 열기

2. **방법 2: PowerShell (Windows)**
   ```powershell
   Start-Process .\index.html
   ```

3. **방법 3: 터미널 명령어**
   ```bash
   # Linux/macOS
   open index.html
   
   # Windows (git bash가 설치된 경우)
   start index.html
   ```

## 프로젝트 구조

```
calculater/
├── index.html      # 계산기 애플리케이션
├── README.md       # 이 파일
└── agents.md       # 에이전트 설정 정보
```

## 개발

이 프로젝트는 단일 파일로 구성되어 있습니다. 모든 HTML, CSS, JavaScript 코드는 `index.html`에 포함되어 있습니다.

계산기를 수정하려면:
1. `index.html`을 텍스트 에디터로 열기
2. 원하는 부분 수정
3. 파일 저장
4. 브라우저 새로고침하여 변경사항 확인

## 라이선스

이 프로젝트는 오픈소스이며 개인 및 교육 목적으로 자유롭게 사용할 수 있습니다.

## 저장소

- GitHub: [kwtae1113/calculater](https://github.com/kwtae1113/caculater.git)
