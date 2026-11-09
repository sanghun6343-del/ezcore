# EZCORE 무료 홈페이지 (PWA)

## 구성
- `index.html`: 회사 홈페이지
- `style.css`: PC/모바일 반응형 디자인
- `manifest.webmanifest`: PWA 앱 설정
- `service-worker.js`: 오프라인 캐시
- `icons/`: 홈 화면 앱 아이콘

## 무료 공개 방법 (GitHub Pages)
1. GitHub 계정으로 로그인합니다.
2. 새 Public 저장소를 만들고 이름을 `ezcore-homepage` 등으로 지정합니다.
3. 이 ZIP 파일의 압축을 풀고 안의 파일 전체를 저장소 최상위(root)에 업로드합니다.
4. 저장소의 Settings → Pages → Deploy from a branch → `main` / `/(root)` → Save를 선택합니다.
5. 생성된 `https://계정이름.github.io/ezcore-homepage/` 주소로 접속합니다.

## PWA 설치
- Android Chrome: 홈페이지 접속 → 브라우저 메뉴 → 앱 설치 또는 홈 화면에 추가
- iPhone Safari: 홈페이지 접속 → 공유 → 홈 화면에 추가

PWA 설치와 서비스워커는 HTTPS 주소에서 정상 작동합니다. GitHub Pages는 HTTPS를 지원합니다.

## 공개 전 확인할 사항
- 회사 주소, 대표 전화번호, 공식 문의 이메일이 최신인지 확인하세요.
- 실제 제품 사진, 회사 로고, 인증·품질 관련 표현은 검증된 자료로 교체하세요.
- 현재 연락처는 제공된 `shlee@ezcore.co.kr`, `www.ezcore.co.kr`를 사용했습니다.
