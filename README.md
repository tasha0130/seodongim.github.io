# 포트폴리오 사이트

## 배포 방법 (GitHub Pages)

1. GitHub에서 새 레포지토리를 만듭니다.
   - 레포 이름을 `사용자명.github.io` 로 지으면 주소가 `https://사용자명.github.io` 가 됩니다.
   - 다른 이름으로 지으면 `https://사용자명.github.io/레포이름/` 이 됩니다.
   - **Public** 으로 만들어야 합니다.

2. `index.html` 파일을 레포 최상단에 업로드합니다.
   - 웹에서 `Add file → Upload files` 로 드래그하면 됩니다.

3. 레포 `Settings → Pages` 로 이동합니다.
   - Source: **Deploy from a branch**
   - Branch: **main** / 폴더: **/ (root)**
   - Save

4. 1~2분 뒤 주소가 활성화됩니다.

## 수정해야 할 곳

| 위치 | 내용 |
|---|---|
| `<title>` / `meta description` | 검색·공유 시 노출되는 문구 |
| 히어로 지표 4개 | `00%` 등 실제 수치로 교체 |
| 프로젝트 `[수치 입력]` | 성과 숫자로 교체 (절대값 대신 비율 권장) |
| `데모 보기` 링크 | 더미 데이터 버전 배포 주소 |
| 연락처 이메일 · GitHub | 실제 정보 |
| `portfolio.pdf` | PDF 버전을 같은 폴더에 업로드 |

## 이미지 추가할 때

레포에 `images/` 폴더를 만들고 업로드한 뒤, 카드 안에 넣습니다.

```html
<img src="./images/파일명.jpg" alt="설명" style="width:100%;margin-top:20px;border:1px solid var(--rule)">
```

배너나 상세페이지 이미지는 폭 1200px 내외, 파일당 300KB 이하로 줄여서 올리는 게 좋습니다.

## 주의

- 이 레포는 Public 이므로 **회사 실데이터가 담긴 파일은 절대 올리지 않습니다.**
- 스크린샷의 수치 가림은 이미지 편집 단계에서 완전히 지운 뒤 저장합니다.
