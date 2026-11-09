# 조선대학교 일반대학원 수료요건 체크리스트

학과·학위과정을 선택하면 해당하는 수료요건과 졸업요건을 확인하는 단일 HTML 페이지입니다. 외부 라이브러리와 서버 없이 동작하며, 입력 내용은 사용자 브라우저(localStorage)에만 저장됩니다.

## GitHub Pages 배포
1. 새 저장소를 만들고 `index.html`, `.nojekyll`, `README.md`를 올립니다.
2. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save
3. 1~2분 뒤 `https://<계정>.github.io/<저장소>/` 에서 열립니다.

## 매년 수정할 곳 (`index.html` 의 `CONFIG` 블록)
- `basisDate` : 수료요건 기준일
- `deptYear` : 학과 목록 기준 학년도
- `storageKey` : 값을 바꾸면 이전 입력 기록이 초기화됨
- `depts` : [학과명, 운영 과정(m=석사 d=박사 i=통합), 석사 논문면제 시행(1/0)]
- `tel`, `contacts` : 문의처
