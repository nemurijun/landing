# MINMIN CAFE Landing Page

간단한 카페 소개용 원페이지 랜딩페이지입니다. 순수 HTML/CSS/JavaScript로 제작되어 별도 빌드 과정 없이 바로 열어볼 수 있습니다.

## 구성

- `index.html` — 페이지 구조 (홈, 소개, 메뉴, 오시는 길, 문의)
- `style.css` — 전체 스타일 및 반응형 레이아웃
- `script.js` — 모바일 내비게이션 메뉴 토글

## 실행 방법

별도 설치 없이 `index.html` 파일을 브라우저로 열면 됩니다.

```bash
# 예: VSCode Live Server 사용 시
# 또는 아래처럼 정적 서버로 실행
npx serve .
```

## 섹션 안내

| 섹션 | 설명 |
| --- | --- |
| Home | 카페 소개 문구와 메인 CTA |
| About | 카페의 특징 3가지 소개 |
| Menu | 대표 음료 및 디저트 메뉴 |
| Location | 주소, 영업시간, 연락처 |
| Contact | 문의용 CTA |

## 커스터마이징

- `style.css` 상단 `:root` 변수(`--color-brand` 등)를 수정하면 전체 컬러 톤을 쉽게 바꿀 수 있습니다.
- `index.html`의 메뉴 항목(`.menu-grid`)을 추가/삭제하여 실제 판매 메뉴로 교체하세요.
